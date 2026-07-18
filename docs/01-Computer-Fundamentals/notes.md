# Computer Fundamentals

## Overview

Computer Fundamentals form the foundation of Computer Science and Cybersecurity. Every operating system, network, web application, and security tool runs on a computer. Understanding how computers work makes it easier to understand Linux, Networking, Web Security, Cloud, and Malware Analysis.

---

# What is a Computer?

A computer is an electronic device that accepts input, processes data using instructions, stores information, and produces output.

### Main Components

- CPU
- RAM
- Storage (SSD/HDD)
- Motherboard
- Power Supply Unit (PSU)
- Input Devices
- Output Devices

---

# Hardware, Software and Firmware

## Hardware

Physical components that can be touched.

### Examples

- CPU
- RAM
- SSD
- HDD
- Keyboard
- Mouse
- Monitor
- Motherboard

---

## Software

Programs that tell the hardware what to do.

### Examples

- Windows
- Linux
- macOS
- Chrome
- VS Code

---

## Firmware

Software permanently stored inside hardware.

It starts before the operating system and initializes hardware.

### Examples

- BIOS
- UEFI
- Router Firmware
- Keyboard Firmware

---

# CPU (Central Processing Unit)

The CPU is known as the **brain of the computer**. It executes instructions and performs calculations.

## Components

### ALU (Arithmetic Logic Unit)

Performs

- Arithmetic calculations
- Logical operations

---

### Control Unit (CU)

Controls and coordinates all CPU operations.

Responsibilities

- Fetch instructions
- Decode instructions
- Execute instructions

---

### Registers

Very small and extremely fast memory inside the CPU.

Used to temporarily store data being processed.

---

### Cache Memory

Small high-speed memory located inside the CPU.

Stores frequently used data to reduce access time.

Levels

- L1 Cache
- L2 Cache
- L3 Cache

---

# Core vs Thread

## Core

A physical processing unit inside the CPU.

More cores allow more tasks to run simultaneously.

---

## Thread

A logical execution unit inside a CPU core.

Threads improve multitasking performance.

Example

- 4 Cores / 8 Threads
- 8 Cores / 16 Threads

---

# Clock Speed

Clock speed determines how many cycles a CPU performs every second.

Measured in

- MHz
- GHz

Higher clock speed generally means faster execution.

---

# Memory

## RAM (Random Access Memory)

Temporary memory.

Stores running programs and currently used data.

Characteristics

- Fast
- Volatile
- Data is lost after shutdown

---

## ROM (Read Only Memory)

Permanent memory.

Stores firmware.

Characteristics

- Non-volatile
- Data remains after power off

---

# Storage

## HDD (Hard Disk Drive)

Mechanical storage device.

Advantages

- Cheap
- Large capacity

Disadvantages

- Slow
- Moving parts

---

## SSD (Solid State Drive)

Flash memory storage.

Advantages

- Very fast
- No moving parts
- More reliable

Disadvantages

- More expensive

---

# Boot Process

When the power button is pressed:

1. Power Supply provides power.
2. BIOS/UEFI starts.
3. POST (Power-On Self Test) checks hardware.
4. Bootloader loads.
5. Operating System Kernel loads.
6. Device Drivers load.
7. Login screen appears.

---

# 32-bit vs 64-bit

## 32-bit

- Supports limited RAM
- Older architecture

---

## 64-bit

- Supports much more RAM
- Better performance
- Modern architecture

---

# File and Directory

## File

Stores information.

Examples

- notes.txt
- image.png
- report.pdf

---

## Directory (Folder)

Stores files and other directories.

Example

```
Documents/
    notes.md
    image.png
```

---

# Paths

## Absolute Path

Starts from the root directory.

### Linux

```bash
/home/mohak/Documents/notes.md
```

### Windows

```text
C:\Users\Mohak\Documents\notes.md
```

---

## Relative Path

Starts from the current working directory.

Example

```bash
Documents/notes.md
```

---

# Disk, Partition and Filesystem

## Disk

Physical storage device.

Examples

- HDD
- SSD

---

## Partition

Logical division of a disk.

A single disk can contain multiple partitions.

---

## Filesystem

Method used to organize and store files.

Common Filesystems

- NTFS (Windows)
- FAT32 (USB Drives)
- exFAT
- ext4 (Linux)

---

# What Happens When You Delete a File?

Deleting a file usually removes its reference from the filesystem.

The actual data often remains on the storage device until it is overwritten.

In Windows, deleted files are first moved to the Recycle Bin unless permanently deleted.

---

# Why Computer Fundamentals Matter in Cybersecurity

Understanding computer fundamentals helps security professionals:

- Understand Operating Systems
- Understand Linux and Windows Internals
- Learn Networking
- Analyze Malware
- Understand Memory Attacks
- Learn Digital Forensics
- Understand Web Security
- Understand Cloud Computing

Without computer fundamentals, advanced cybersecurity concepts become much harder to understand.

---

# Summary

Topics Covered

- Computer Basics
- Hardware
- Software
- Firmware
- CPU
- Core
- Thread
- Registers
- Cache
- RAM
- ROM
- HDD
- SSD
- Boot Process
- 32-bit vs 64-bit
- Files
- Directories
- Paths
- Disk
- Partition
- Filesystem
- Importance in Cybersecurity