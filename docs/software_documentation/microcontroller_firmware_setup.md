# Microcontroller Firmware Setup for Motion Capture and Control

### Prerequisites

- STM32 IDE to compile firmware (STM32CubeIDE recommended)
- Clone Mcontroller-v7-firmware repository from GitHub

### Refactor Firmware

- Change `#define USE_MAG` from 1 to 0
- Change `#define USE_ODOMETRY` from 0 to 1
- Change `#define USE_MOTION` from 0 to 1
- Change `#define USE_ODOM_Z` from 0 to 1

### Compile and build firmware with STM32CubeIDE

Note that compiling the `Mcontroller-v7-FanciSwarm` software repository will require a dependency package called `libMcontroller-v7-firmware.a`. While the `libMcontroller-v7-firmware.a`static file may already exist at the root of the repository, you will still need to replace it with the newly updated version, which can be downloaded online from `https://www.fancinnov.com/downloads` under the **Mcontroller V7 Firmware and Dependency Packages** section.

