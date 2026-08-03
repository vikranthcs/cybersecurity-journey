# Day 2 – Operating Systems

---

# What is an Operating System?

**Definition:**

An **Operating System (OS)** is system software that manages computer hardware resources and provides services to applications and users.

**Simple Definition:**

> OS = Manager of the Computer

**Examples:**

* Windows
* Linux
* macOS

---

# Why Do We Need an Operating System?

Applications cannot directly access hardware.

### Example

```text
Chrome
   ↓
Operating System
   ↓
Hardware
```

The Operating System acts as a bridge between software and hardware.

---

# Main Functions of an Operating System

## 1. Process Management

Manages running programs.

**Examples:**

* Chrome
* VS Code
* Spotify

**Responsibilities:**

* Create Processes
* Schedule Processes
* Terminate Processes

---

## 2. Memory Management

Manages RAM.

**Example:**

* Chrome → 2 GB RAM
* VS Code → 500 MB RAM
* Virtual Machine → 4 GB RAM

**Responsibilities:**

* Allocate Memory
* Release Memory
* Prevent Memory Conflicts

---

## 3. File Management

Manages:

* Files
* Folders
* Storage Devices
* Permissions

**Example:**

```text
C:\Users\vikra\Documents
```

---

## 4. Device Management

Controls hardware devices through drivers.

**Examples:**

* Keyboard
* Mouse
* Printer
* Network Card
* Monitor

---

## 5. Security Management

Provides:

* Authentication
* Authorization
* Access Control
* User Permissions

---

# Kernel

## Definition

The **Kernel** is the core component of an Operating System.

### Responsibilities

* Hardware Communication
* CPU Management
* Memory Management
* Device Control

### Diagram

```text
Applications
      ↓
Operating System
      ↓
Kernel
      ↓
Hardware
```

---

# Process

## Definition

A **Process** is a program that is currently running in memory (RAM).

### Example

```text
chrome.exe
    ↓ Open
Chrome Process
```

### Examples

* Chrome
* VS Code
* Spotify
* Notepad

---

# Service

## Definition

A **Service** is a background process that runs automatically without direct user interaction.

### Examples

* Windows Update
* Windows Defender
* DHCP Client
* DNS Client

---

# Process vs Service

## Process

* Usually started by the user
* Visible to the user

**Example:** Chrome

## Service

* Usually starts automatically
* Runs in the background

**Example:** Windows Update

---

# User Space

## Definition

User Space is where normal applications run.

### Examples

* Chrome
* VS Code
* Discord
* Spotify

### Characteristics

* Limited Privileges
* Cannot Directly Access Hardware

---

# Kernel Space

## Definition

Kernel Space is where the Kernel runs.

### Examples

* Drivers
* Memory Manager
* Process Scheduler

### Characteristics

* Full System Privileges
* Direct Hardware Access

---

# User Space vs Kernel Space

```text
User Space
│
├── Chrome
├── VS Code
├── Spotify
│
▼
System Calls
│
▼
Kernel Space
│
├── Kernel
├── Drivers
├── Memory Manager
└── Process Scheduler
│
▼
Hardware
```

---

# System Calls

## Definition

A **System Call** is a request made by a program to the Operating System Kernel.

### Example

```text
Chrome
   ↓
System Call
   ↓
Kernel
   ↓
Read File
```

### Purpose

Allows applications to safely access hardware resources.

---

# CPU Scheduling

## Definition

CPU Scheduling is the process of deciding:

* Which process runs
* When it runs
* For how long it runs

---

# Multitasking

## Definition

The ability of an Operating System to run multiple processes at the same time.

### Example

* Chrome Open
* VS Code Open
* Music Playing
* File Download Running

---

# File System

## Definition

A File System is the method used by the Operating System to organize and store files.

### Windows

**NTFS**

### Linux

**ext4**

### Functions

* Organize Files
* Manage Permissions
* Manage Storage

---

# Drivers

## Definition

A Driver is software that enables the Operating System to communicate with hardware devices.

### Examples

* Network Driver
* Graphics Driver
* Audio Driver
* Printer Driver

### Diagram

```text
Operating System
       ↓
Driver
       ↓
Hardware
```

---

# Windows vs Linux

## Windows

* Closed Source
* Easier for Beginners
* Common on Personal Computers

## Linux

* Open Source
* Highly Customizable
* Dominates Cloud Servers
* Widely Used in Cybersecurity

---

# Boot Process

```text
Power On
   ↓
BIOS / UEFI Starts
   ↓
POST
   ↓
Boot Loader
   ↓
Kernel Loads
   ↓
Operating System Starts
   ↓
Login Screen
```

---

# Quick Revision

| Term          | Meaning                     |
| ------------- | --------------------------- |
| Kernel        | Core of the OS              |
| Process       | Running Program             |
| Service       | Background Process          |
| System Call   | Request to Kernel           |
| Driver        | OS ↔ Hardware Communication |
| File System   | Organizes Files             |
| CPU Scheduler | Decides CPU Time            |

---

# Interview Questions

1. What is an Operating System?
2. Why do we need an Operating System?
3. What is a Kernel?
4. What is a Process?
5. What is a Service?
6. Difference between Process and Service?
7. What is User Space?
8. What is Kernel Space?
9. What is a System Call?
10. What is CPU Scheduling?
11. What is Multitasking?
12. What is a Driver?
13. What is a File System?
14. Difference between Windows and Linux?
15. Explain the Boot Process.

---

# What I Learned Today

* Operating System Fundamentals
* Kernel
* Processes
* Services
* User Space
* Kernel Space
* System Calls
* CPU Scheduling
* Drivers
* File Systems
* Windows vs Linux
* Boot Process

---

# Doubts

None
