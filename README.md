# smashpc4
smashpc4 is a decompalation project of the game [Super Smash Bros 64]

## Overview
- Native PC compilation without emulation
- Modding support for characters, stages, and mechanics
- Research into N64 game development techniques

## Key Features
- **Full source code** reconstruction from original assembly
- **Modern build system** (Make/CMake)
- **Hardware-agnostic rendering** (OpenGL/Vulkan support)
- **Asset extraction tools** for textures and audio

## Legal Notice
This project does not distribute copyrighted Nintendo assets. Users must provide their own legally obtained ROM:
- All code is original work (clean-room reverse engineering)
- No Nintendo proprietary code is included in this repository

## Building
1. Clone this repository
2. Place legal `baserom.z64` in project root
3. Run `make` (Linux/macOS) or use provided Visual Studio solution (Windows)
