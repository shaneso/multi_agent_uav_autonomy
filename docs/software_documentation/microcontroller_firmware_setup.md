# Microcontroller Firmware Setup for Motion Capture

### Prerequisites

- STM32 IDE to compile firmware (STM32CubeIDE recommended)
- Clone Mcontroller-v7-firmware repository from GitHub

### Refactor Firmware

- Change `#define USE_MAG` from 1 to 0
- Change `#define USE_ODOMETRY` from 0 to 1
- Change `#define USE_MOTION` from 0 to 1
- Change `#define USE_ODOM_Z` from 0 to 1

# Compile and build firmware with STM32CubeIDE

