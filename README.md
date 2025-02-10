# Own Vulkan C++ examples and demos



## Introduce

This repository  base on  https://github.com/SaschaWillems/Vulkan , I use it to build own vulkan demos and change the base framework.



## Cloning
This repository contains submodules for external dependencies and assets, so when doing a fresh clone you need to clone recursively:

```
git clone --recursive https://github.com/VanityNie/Vulkan-Demo.git
```

Existing repositories can be updated manually:

```
git submodule init
git submodule update
```

## Building

The repository contains everything required to compile and build the examples on <img src="./images/windowslogo.png" alt="" height="22px" valign="bottom"> Windows, <img src="./images/linuxlogo.png" alt="" height="24px" valign="bottom"> Linux, <img src="./images/androidlogo.png" alt="" height="24px" valign="bottom"> Android, <img src="./images/applelogo.png" alt="" valign="bottom" height="24px"> iOS and macOS (using MoltenVK) using a C++ compiler that supports C++20.

See [BUILD.md](BUILD.md) for details on how to build for the different platforms.

## 



## Shaders

Vulkan consumes shaders in an intermediate representation called SPIR-V. This makes it possible to use different shader languages by compiling them to that bytecode format. The primary shader language used here is [GLSL](shaders/glsl) but most samples also come with [HLSL](shaders/hlsl) shader sources.




## 

## Credits and Attributions
See [CREDITS.md](CREDITS.md) for additional credits and attributions.
