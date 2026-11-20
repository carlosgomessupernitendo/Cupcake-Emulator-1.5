
# Cupcake Emulator 1.5 - Engine

## Objective

Create an emulator engine capable of running the original Android 1.5 Cupcake operating system.

## Target system

- Android version: 1.5 Cupcake
- API level: 3
- Linux kernel: 2.6.27
- CPU architecture: ARM
- Virtual hardware: Goldfish

## Emulation engine

The project will investigate and adapt the classic Android QEMU emulator.

## Required components

- QEMU Android modifications
- Goldfish virtual hardware
- Android 1.5 compatible kernel
- Boot image
- System image
- User data image
- Virtual SD card

## Mobile integration

The engine must eventually run inside the Cupcake Emulator Android application.

Planned integration:
- Android NDK
- C/C++
- JNI
- Touchscreen input
- Virtual keyboard
- Audio
- Persistent storage

## Compatibility adaptations

Modern host features will be adapted without replacing the original Android 1.5 guest system.

## Current status

Research and architecture preparation.

No executable emulator engine has been integrated yet.
