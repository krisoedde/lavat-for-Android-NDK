# lavat for Android NDK

A native Android build of [lavat](https://github.com/AngelJumbo/lavat).

A terminal lava lamp simulator, compiled for ARM64 Android using Android NDK.

## Overview

- **Architecture:** ARM64 (AArch64)
- **Platform:** Android
- **Build system:** Android NDK r29
- **Compiler:** Clang 21
- **Compile target API:** Android 15 (API 35)
- **Binary:** Native ELF executable
- **Author:** kRiSOED

## Installation

1. Download the module ZIP from Releases.
2. Open KernelSU/Magisk.
3. Navigate to Modules.
4. Select the ZIP and install it.
5. Reboot your device.

## Usage

Open your terminal and run:

    lavat

Enjoy your lava lamp!

## Compatibility

Built for ARM64 Android devices.

The executable is dynamically linked against Android system libraries (Bionic).

## Credits

- Original project: [AngelJumbo/lavat](https://github.com/AngelJumbo/lavat)
- Android NDK: Google
- Android build and module packaging: **kRiSOED**
