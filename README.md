# Operating-System
Code repository for Operating System Project

## 🚀 Project Overview

This OS project is designed for learning and experimentation. It includes a custom bootloader, kernel, and supporting utilities to build a minimal working operating system.

It showcases:
- Boot process using Assembly
- Kernel initialization in C
- Basic graphics rendering
- Input handling
- Font rendering system
- Custom build system using Makefile

---

## 📁 Project Structure
bin/ -> Compiled binaries
utilities/ -> Helper utilities
boot.asm -> Bootloader (Assembly)
kernel_entry.asm -> Kernel entry point
main.c -> Main kernel logic
final.c -> Core system implementation
graphics.c/h -> Graphics rendering engine
font.c -> Font rendering system
input.c -> Keyboard/input handling
makefile -> Build automation
os.img -> Generated OS image
vbe-modex.txt -> VESA/VBE graphics mode info


---

## ⚙️ Requirements

To build and run this OS, you need:

- `gcc` (cross-compiler recommended: i686-elf-gcc)
- `nasm` (Netwide Assembler)
- `make`
- `qemu` (for testing the OS)

---

## 🔧 Build Instructions

Run the following commands:

```bash
make clean
make

This will:

Assemble bootloader and kernel
Compile C source files
Link everything together
Generate os.img



This project is for educational purposes only.
