
# Bootlin Training 
https://bootlin.com/docs/
https://elixir.bootlin.com/linux/latest/source

## All Training
1. 	https://bootlin.com/doc/training/autotools/
2. 	https://bootlin.com/doc/training/boot-time/
3. 	https://bootlin.com/doc/training/buildroot/
4. 	https://bootlin.com/doc/training/buildroot-stm32/
5. 	https://bootlin.com/doc/training/debugging/
6. 	https://bootlin.com/doc/training/embedded-linux/
7. 	https://bootlin.com/doc/training/embedded-linux-bbb/
8. 	https://bootlin.com/doc/training/embedded-linux-qemu/
9. 	https://bootlin.com/doc/training/embedded-linux-4d/
10. https://bootlin.com/doc/training/graphics/
11. https://bootlin.com/doc/training/linux-kernel/
12. https://bootlin.com/doc/training/preempt-rt/
13. https://bootlin.com/doc/training/yocto/
14. https://bootlin.com/doc/training/yocto-stm32/

## All Sources
### 1. [ARM Trusted Firmware (TF-A)](https://elixir.bootlin.com/arm-trusted-firmware/latest/source)
is a reference implementation of secure world software for ARMv7-A, ARMv8-A, and ARMv8.1-A processors. It provides a set of secure software components that enable TrustZone technology for ARM processors, including Secure Boot, Secure Monitor, and Trusted Board Boot Requirements (TBBR).
> ARM Trusted Firmware is a set of firmware components for ARM-based systems that implement various security features, such as secure boot, Trusted Execution Environment (TEE), and Secure Monitor. It is designed to work with ARM processors and provides a secure foundation for building trusted systems.

### 2. [OP-TEE (Open Portable Trusted Execution Environment)](https://elixir.bootlin.com/op-tee/latest/source) 
is a software stack that provides a secure execution environment for trusted applications on ARM-based systems. It utilizes the ARM TrustZone technology to isolate and protect critical code and data from untrusted applications running on the same system.
> OP-TEE (Open Portable Trusted Execution Environment) is a TEE (Trusted Execution Environment) for ARM-based processors. It provides a secure environment for running trusted applications, such as mobile payments and secure boot, and is designed to work with ARM Trusted Firmware.

### 3. [U-Boot](https://elixir.bootlin.com/u-boot/latest/source) 
is a widely used open-source bootloader for embedded systems and devices. It can load and boot various operating systems and applications from different storage devices, and provides a flexible and customizable boot environment with support for various hardware configurations and features.
> U-Boot (Universal Bootloader) is a bootloader that is used to load operating systems on embedded systems. It provides a command-line interface for configuring and booting the system, as well as support for a wide range of hardware.

### 4. [Linux](https://elixir.bootlin.com/linux/latest/source) 
is a widely used open-source Unix-like operating system kernel. It provides the core functionality and services for running user-space applications and managing system resources, including process and memory management, file systems, networking, and device drivers.
> Linux is a free and open-source operating system kernel. It is used as the foundation for many different operating systems, such as Android, Chrome OS, and various Linux distributions. Linux provides a wide range of features, such as memory management, process scheduling, and file systems.

### 5. [Amazon FreeRTOS](https://elixir.bootlin.com/amazon-freertos/latest/source)
is an open-source operating system for microcontrollers that makes small, low-power edge devices easy to program, deploy, secure, connect, and manage. It includes an MQTT broker, Wi-Fi and Bluetooth connectivity, over-the-air updates, and built-in security.
> Amazon FreeRTOS is an open-source operating system for microcontrollers that enables developers to easily and securely connect IoT devices to the cloud. It includes libraries that provide support for AWS services, such as AWS IoT Core, as well as a kernel for managing the microcontroller's resources.

### 6. [Barebox](https://elixir.bootlin.com/barebox/latest/source) 
is a versatile and customizable bootloader that supports a wide range of hardware architectures and configurations. It can load and boot operating systems such as Linux, Android, and others from various storage devices, including flash, SD card, network, and USB.
> Barebox is a bootloader that supports a wide range of processors and platforms. It is designed to be fast, flexible, and easy to use. Barebox provides a command-line interface for configuring and booting the system, as well as a scripting language for more complex tasks.

### 7. [BlueZ](https://elixir.bootlin.com/bluez/latest/source) 
is the official Linux Bluetooth protocol stack. It provides support for core Bluetooth layers such as L2CAP, RFCOMM, and the Bluetooth Low Energy (BLE) protocol. It also includes many user-space utilities for Bluetooth device management and configuration.
> Bluez is the official Bluetooth stack for Linux. It provides support for the Bluetooth protocol and enables communication between Bluetooth devices and the host system. Bluez includes a number of utilities for managing Bluetooth devices, such as pairing, scanning, and connecting.

### 8. [BusyBox](https://elixir.bootlin.com/busybox/latest/source) 
is a collection of Unix utilities designed for embedded systems and low-resource environments. It includes small versions of common shell utilities such as cp, mv, and ls, as well as other common utilities like grep, awk, and sed, all combined into a single binary.
> BusyBox is a collection of Unix utilities that are designed to be small and efficient. It provides a single binary that includes many common Unix utilities, such as ls, cp, and grep. BusyBox is often used in embedded systems where space and resources are limited.

### 9. [coreboot](https://elixir.bootlin.com/coreboot/latest/source)
is an open-source firmware replacement for the BIOS (Basic Input/Output System) or UEFI (Unified Extensible Firmware Interface) in modern PCs. It provides a lightweight and customizable boot environment that can support various operating systems and hardware configurations.
> Coreboot is an open-source firmware that replaces the proprietary firmware (BIOS or UEFI) found on most PCs. It is designed to be lightweight, fast, and customizable. Coreboot supports a wide range of hardware and can be configured to boot a variety of operating systems.

### 10. [DPDK (Data Plane Development Kit)](https://elixir.bootlin.com/dpdk/latest/source) 
is a set of libraries and drivers for fast packet processing in user-space. It allows applications to bypass the kernel network stack and communicate directly with the network hardware, enabling high-performance networking applications such as routers, gateways, and load balancers.
> It is designed to run on Intel x86 processors and enables applications to bypass the kernel network stack and interact directly with the network hardware.

### 11. [glibc (GNU C Library)](https://elixir.bootlin.com/glibc/latest/source) 
is the standard C library for the GNU operating system and other Unix-like systems. It provides the basic building blocks for writing C programs, including memory allocation, string and math functions, file input/output, and network communication.
> glibc (GNU C Library) is the standard C library for Linux. It provides a set of functions and macros that are commonly used by C programs, such as memory allocation, string manipulation, and file I/O.

### 12. [GRUB (Grand Unified Bootloader)](https://elixir.bootlin.com/grub/latest/source) 
is a widely used boot loader for Linux and other Unix-like operating systems. It can load and boot various operating systems from different storage devices, including hard drives, CD/DVDs, and network. It also provides a flexible and customizable boot environment with support for themes and various boot options.
> GRUB (Grand Unified Bootloader) is a bootloader that is used to load operating systems on PCs. It provides a menu that allows the user to select which operating system to boot, as well as configuration options for the kernel and boot parameters.

### 13. [LLVM (Low-Level Virtual Machine)](https://elixir.bootlin.com/llvm/latest/source) 
is a collection of modular and reusable compiler and toolchain technologies. It includes a compiler front-end for various programming languages, a code optimizer, a code generator, and various analysis and debugging tools.
> LLVM (Low-Level Virtual Machine) is a compiler infrastructure that is used to build a wide range of programming languages. It provides a set of libraries and tools for optimizing, compiling, and linking code. LLVM is often used in conjunction with Clang, a C/C++ compiler that uses LLVM as its back end.

### 14. [Mesa](https://elixir.bootlin.com/mesa/latest/source) 
is an open-source implementation of the OpenGL and Vulkan graphics APIs. It provides a set of user-space libraries and drivers that allow applications to interact with 3D graphics hardware and render high-quality graphics on various platforms.
> Mesa is an open-source implementation of the OpenGL and Vulkan graphics APIs. It provides drivers for a wide range of hardware and enables applications to render 3D graphics on Linux and other operating systems.

### 15. [musl](https://elixir.bootlin.com/musl/latest/source) 
is a lightweight and fast C library designed for embedded and low-resource systems. It provides a subset of the standard C library functions and features, optimized for size, speed, and security.
> musl is a lightweight C library that is designed to be small and fast. It provides a subset of the POSIX API and is often used in embedded systems where space and resources are limited.

### 16. [oFono](https://elixir.bootlin.com/ofono/latest/source) 
is an open-source telephony stack for mobile devices running Linux. It provides a set of user-space libraries and daemons that handle various aspects of mobile telephony, such as voice calls, SMS messaging, and mobile data.
> Ofono is a telephony stack for Linux. It provides support for mobile broadband and voice communication, as well as messaging and phonebook management. Ofono is often used in embedded systems, such as automotive infotainment systems and IoT devices.

### 17. [QEMU (Quick Emulator)](https://elixir.bootlin.com/qemu/latest/source) 
is a free and open-source emulator and virtualizer that can run a wide range of operating systems and hardware platforms. It can emulate different CPUs, devices, and network interfaces, and support various virtualization modes such as full virtualization, para-virtualization, and hardware-assisted virtualization.
> QEMU (Quick EMUlator) is a virtual machine emulator that can run a variety of guest operating systems on a host system. It provides support for a wide range of architectures, including x86, ARM, and PowerPC, and can emulate a variety of devices, such as disks, network cards, and USB controllers.

### 18. [Toybox](https://elixir.bootlin.com/toybox/latest/source) 
is a small and modular implementation of common Unix utilities designed for embedded systems and low-resource environments. It provides a set of lightweight and customizable tools such as ls, cp, mv, and chmod, that can be used to build custom Linux distributions or systems.
> Toybox is a collection of Unix utilities that are designed to be small and lightweight. It provides a single binary that includes many common Unix utilities, such as ls, cp, and grep, and is often used in embedded systems.

### 19. [uClibc-ng (Micro C Library Next Generation)](https://elixir.bootlin.com/uclibc-ng/latest/source) 
is a lightweight and optimized C library designed for embedded and low-resource systems. It provides a subset of the standard C library functions and features, optimized for size, speed, and memory footprint.
> uClibc-ng (Micro C Library Next Generation) is a lightweight C library that is designed to be small and fast. It provides a subset of the POSIX API and is often used in embedded systems where space and resources are limited.

### 20. [Zephyr](https://elixir.bootlin.com/zephyr/latest/source) 
is an open-source real-time operating system (RTOS) designed for resource-constrained and connected devices. It provides a small and flexible kernel, with support for various hardware architectures and connectivity protocols. It also includes various components for device management, security, and connectivity.
> Zephyr is an open-source real-time operating system (RTOS) for embedded systems. It is designed to be scalable, modular, and secure, and provides support for a wide range of hardware platforms. Zephyr is often used in IoT devices, wearables, and other embedded systems.
