# 🔥 DirectX 11 Graphics Portfolio - Crimson Desert Trailer Recreation

<p align="center">
  <img src="https://github.com/user-attachments/assets/662b69d9-9f4e-419c-8732-aa3b77327447" width="800" />
</p>

🎞️ [Watch Video (YouTube)](https://www.youtube.com/watch?v=e3Tg7toK84Y)  
📘 [Personal Study Blog (Tistory, Korean)](https://pdy0930.tistory.com/)

---

## 🧪 Project Overview

This portfolio is a DirectX 11-based graphics demo that recreates a scene from the **Crimson Desert** trailer by Pearl Abyss.  
It implements a wide range of real-time rendering techniques, shader programming, volume rendering, tessellation, and other fundamental graphics technologies.

---

## 🖥️ Test Environment & Performance Note

- CPU: Intel(R) Core(TM) i5-8265U (1.6GHz)  
- GPU: Intel UHD Graphics 620 (Integrated)  
- RAM: 8GB

> ⚠️ This project was developed and tested on a **low-end laptop** environment.  
> Especially in computationally intensive areas such as **volume rendering and terrain generation**, frame drops can occur.  
> Optimization strategies were applied to ensure it runs even in constrained environments.

---

## 🛠️ Implemented Technologies

- **PBR (Physically Based Rendering)**
- **HDR + Tone Mapping**
- **Tessellation**
- **Volumetric Cloud Rendering** (ported from ShaderToy examples)
- **Perlin Noise-based Grass Placement and Animation**
- **Shadow Techniques**: PCF, PCSS
- **MSAA (Multisample Anti-Aliasing) + Resolve Pass**
- **Post-processing with Gamma Correction**
- **Bloom with Up/Down Sampling for Anti-Aliasing**
- **Auto Texture Format Detection and Loading System**

> 🔍 Debug Tool: **RenderDoc**

---

### 📌 References for Cloud Rendering Improvements

- ShaderToy cloud rendering explanation video:  
  👉 [YouTube - ShaderToy Volumetric Cloud Explanation](https://www.youtube.com/watch?v=BFld4EBO2RE)

- Noise theory used for cloud shaping and terrain formation:  
  👉 [FBM (Fractional Brownian Motion) Explanation](https://iquilezles.org/articles/fbm/)  
  👉 [Improved Noise and Terrain Shaping](https://iquilezles.org/articles/morenoise/)

- To further understand cloud rendering, it is essential to explore ShaderToy and Unreal Engine examples that demonstrate various forms of clouds.

---

## 🔭 Future Study and Improvements

- **Review and apply 3D Fluid Simulation techniques (e.g., smoke simulation)**  
  → Based on finite difference methods, PDEs, and implicit integration using compute shaders

- **Analyze and implement practical usage of Curl Noise**

- **Understand and apply the principle of Deferred Shading**

- **Port the project to DirectX 12**

---

## 📚 References and Resources

### 1. 👨‍🏫 Lectures and Base Code
- [Honglab Graphics Lectures (Korean)](https://www.honglab.ai/collections)

### 2. 📘 LearnOpenGL References
- [PBR Theory](https://learnopengl.com/PBR/Theory)  
- [Gamma Correction](https://learnopengl.com/Advanced-Lighting/Gamma-Correction)  
- [Peter Panning Artifact Fix](https://learnopengl.com/Advanced-Lighting/Shadows/Shadow-Mapping)

### 3. 🌩️ ShaderToy Example Code
- [Perlin Noise](https://www.shadertoy.com/view/3dVXDc)  
- [Volumetric Clouds](https://www.shadertoy.com/view/4ttSWf)  
- [Cook-Torrance + Oren-Nayar PBR](https://www.shadertoy.com/view/MsSczh)

### 4. 🧬 Other Resources
- [Wave + Fractal Brownian Motion Theory](https://thebookofshaders.com/13/?lan=kr)  
- [C++ Perlin Noise Open Source](https://github.com/Reputeless/PerlinNoise)  
- [PBR Shader Code](https://github.com/Nadrin/PBR)  
- [MSAA Post-Processing & HDR Handling](https://github.com/Microsoft/DirectXTK/wiki/Using-HDR-rendering)
