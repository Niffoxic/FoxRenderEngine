# Fox Render Engine

This is a Windows-specific graphics project built using **Vulkan** and the **Win32 API**, designed to test and experiment with:

- Physically-Based Rendering (PBR)
- Custom shaders (GLSL/HLSL to SPIR-V)
- Vulkan raytracing extensions

---

## Requirements

- Windows 10/11
- Vulkan SDK (1.3+)
- CMake 3.20+
- Visual Studio 2019/2022 or MSVC toolchain
- GPU with raytracing support (RTX 20xx+/RX 6000+ recommended)

---

## Build Instructions

> Recommended: Use the GUI installer for first-time setup. It handles everything — installing CMake (if missing), Vulkan SDK, compiling shaders, and building the project.

### 🔄 Quick Start with GUI Installer

```bash
cd FoxRenderEngine/setup
pip install -r requirements.txt
python main.py
```

`Note: I will update how to build it without gui installer just in case if anyone don't trust me with .exe file XD (I will do it later tho I gotta go back to the main vulkan stuff`
