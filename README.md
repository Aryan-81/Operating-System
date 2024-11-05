# OS Lab Assessment

## Overview
This project is a simple, minimalistic operating system built from scratch. It includes a basic bootloader, a kernel written in C, and essential drivers for basic functionality. This OS serves as an educational project to understand the inner workings of how operating systems interact with hardware and manage low-level processes.

## Project Structure

```plaintext
my_os_project/
├── boot/
│   ├── boot.asm            # Assembly file for the bootloader
│   └── linker.ld           # Linker script for memory layout
├── kernel/
│   ├── kernel.c            # Main kernel code in C
│   ├── kernel.h            # Kernel headers
│   └── drivers/
│       ├── screen.c        # Basic screen driver
│       └── screen.h        # Screen driver header
├── include/
│   ├── io.h                # I/O handling headers
│   ├── stdio.h             # Basic standard I/O
│   └── stdlib.h            # Basic standard library functions
├── build/
│   └── Makefile            # Makefile for building the OS
└── README.md               # Project overview and setup instructions
```

## Features
- to be added

## Getting Started

<!-- ### Prerequisites
- **Assembler**: [NASM](https://www.nasm.us/) - for assembling the bootloader.
- **C Compiler**: [GCC](https://gcc.gnu.org/) - for compiling the kernel.
- **Linker**: `ld` - for linking object files.
- **Emulator** (optional but recommended): [QEMU](https://www.qemu.org/) - for testing the OS without needing a physical machine.

### Building the Project
To compile and link the bootloader and kernel, run:

```bash
cd build/
make
```

This will generate a bootable binary, `myos.bin`.

### Running the OS
If you have QEMU installed, you can test your OS by running:

```bash
qemu-system-i386 -drive format=raw,file=myos.bin
```

This will start the OS in an emulated environment, ideal for debugging and testing.

### Cleaning Up
To remove build artifacts, use:

```bash
make clean
``` -->
