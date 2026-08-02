# Day-1

# How a Computer Works

## What is a Computer?

A computer is an electronic device that receives input, processes data, stores information, and produces output.

### Input → Process → Output

Example:

* Input: Clicking the Chrome icon
* Process: CPU executes instructions
* Output: Chrome opens on the screen

Flow:

Input → Processing → Output

---

# CPU (Central Processing Unit)

The CPU is the brain of the computer. It executes instructions and performs calculations required by programs and the operating system.

Examples:

* Opening applications
* Running programs
* Executing operating system tasks
* Processing network traffic

## Core

A core is an individual processing unit inside the CPU.

Example:

* Dual-Core CPU = 2 cores
* Quad-Core CPU = 4 cores
* Octa-Core CPU = 8 cores

More cores allow the CPU to handle more work simultaneously.

## Thread

A thread is the smallest unit of execution handled by the CPU.

Many modern CPUs support two threads per core.

Example:

* 6 Cores
* 12 Threads

This usually means each core can manage two execution streams.

## Cache

Cache is a very small and extremely fast memory located inside or very close to the CPU.

Purpose:

* Stores frequently used data and instructions
* Reduces the need to access slower RAM

Speed Comparison:

Cache > RAM > SSD > HDD

Example:

Cache is like a paper in your hand while studying. RAM is your study table, and SSD is your bookshelf.

---

# RAM (Random Access Memory)

RAM is the temporary working memory of a computer.

Programs and operating systems are loaded into RAM before they are executed by the CPU.

Examples:

* Chrome
* VS Code
* VirtualBox
* Kali Linux VM

All use RAM while running.

## Volatile Memory

RAM is volatile memory.

This means:

Power Off → Data Lost

Unsaved work stored only in RAM disappears when the computer shuts down unexpectedly.

---

# Storage

Storage is used to permanently save data.

Examples:

* Operating Systems
* Documents
* Videos
* Applications
* Logs

## HDD (Hard Disk Drive)

Characteristics:

* Uses spinning magnetic disks
* Lower cost
* Slower performance

Advantages:

* Cheap
* Large capacity

Disadvantages:

* Slower
* Mechanical parts can wear out

## SSD (Solid State Drive)

Characteristics:

* Uses flash memory
* No moving parts
* Faster than HDD

Advantages:

* Fast boot times
* Faster application loading
* More reliable

Disadvantages:

* More expensive per GB

---

# Motherboard

The motherboard is the main circuit board of a computer.

It connects all hardware components and allows them to communicate.

Connected Components:

* CPU
* RAM
* SSD/HDD
* Network Interface Card
* USB Devices
* Graphics Card

Without the motherboard, hardware components cannot communicate with each other.

---

# Network Interface Card (NIC)

NIC stands for Network Interface Card.

Its purpose is to connect a computer to a network.

Functions:

* Provides Wi-Fi connectivity
* Provides Ethernet connectivity
* Sends and receives network traffic

Without a NIC:

* No Internet
* No Wi-Fi
* No Ethernet connection

NIC is extremely important in networking, cloud computing, and cybersecurity.

---

# Computer Boot Process

The boot process is the sequence of steps that occurs when a computer is powered on.

## Step 1: Power On

Electricity is supplied to:

* Motherboard
* CPU
* RAM
* Storage Devices

## Step 2: BIOS / UEFI Starts

BIOS or UEFI firmware starts running.

Responsibilities:

* Detect hardware
* Initialize hardware
* Prepare the system for booting

## Step 3: POST (Power-On Self-Test)

The system checks critical hardware:

* CPU
* RAM
* Storage

If hardware problems are detected, the boot process may stop.

## Step 4: Boot Loader

The boot loader locates the operating system.

Example:

* Windows Boot Manager

## Step 5: Operating System Loading

Operating system files are loaded from storage into RAM.

## Step 6: CPU Executes OS Instructions

The CPU begins executing operating system instructions.

## Step 7: Login Screen Appears

The operating system becomes available for use.

Boot Sequence:

Power On → BIOS/UEFI → POST → Boot Loader → OS Loading → Login Screen

---

# Virtualization

Virtualization allows multiple operating systems to run on a single physical computer.

It is one of the most important technologies in cloud computing and cybersecurity.

## Host OS

The main operating system installed on the physical machine.

Example:

* Windows 11

## Guest OS

The operating system running inside a virtual machine.

Example:

* Kali Linux

## Hypervisor

A hypervisor is software that creates and manages virtual machines.

Examples:

* VirtualBox
* VMware
* Hyper-V

Example Setup:

Host OS: Windows 11

Hypervisor: VirtualBox

Guest OS: Kali Linux

## Why Cybersecurity Professionals Use Virtual Machines

* Safe testing environment
* Malware analysis labs
* Linux practice
* Network labs
* Easy recovery if something breaks

---

## My System Specifications

CPU: AMD Ryzen AI 5 330 w/ Radeon 820M
Cores: 4
Threads: 8

RAM: 16GB

Storage: SSD: 512GB

Operating System:
Windows 11

---

# Interview Questions

1. What is a CPU?
2. What is the difference between a core and a thread?
3. What is cache memory?
4. What is RAM?
5. What is volatile memory?
6. What is the difference between RAM and SSD?
7. What is the difference between HDD and SSD?
8. What is a motherboard?
9. What is a NIC?
10. What is POST?
11. What is virtualization?
12. What is a hypervisor?
13. What is the difference between Host OS and Guest OS?
14. Explain the computer boot process.

---

# Summary

A computer receives input, processes data, stores information, and produces output. The CPU performs processing, RAM provides temporary working memory, and storage permanently saves data. The motherboard connects all hardware components, while the NIC enables network communication. During startup, the system follows a boot process consisting of BIOS/UEFI, POST, boot loader, and operating system loading. Virtualization allows multiple operating systems to run on one physical machine using a hypervisor such as VirtualBox.
