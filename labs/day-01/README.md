# Day 1 — Cloud & Linux Foundations

**Date:** 01 September 2026

##  Objectives

- Understand Virtual Machines and virtualization
- Understand hypervisors
- Understand Linux and the Linux kernel
- Understand Ubuntu and Linux distributions
- Learn the Linux filesystem hierarchy
- Set up an Ubuntu VM using VirtualBox
- Practise basic Linux commands

---

##  Concepts Learned

### Virtual Machine

A Virtual Machine (VM) is a software-based computer that runs inside a physical computer. It uses virtualized CPU, RAM, storage and other resources provided by the physical machine.

### Hypervisor

A hypervisor creates and manages Virtual Machines and allocates physical resources to them.

There are two main types:

- **Type 1:** Runs directly on physical hardware.
- **Type 2:** Runs on top of an existing operating system.

**VirtualBox is a Type 2 hypervisor.**

### Linux

Linux is technically an open-source kernel. It manages hardware resources and provides an interface between hardware and software.

### Linux Kernel

The Linux kernel is the core component responsible for managing:

- CPU
- Memory
- Processes
- Hardware devices
- Networking

### Ubuntu

Ubuntu is a Linux distribution that uses the Linux kernel along with system utilities, libraries, package management and other software.

---

##  Linux Filesystem

| Path | Purpose |
|---|---|
| `/` | Root of the filesystem |
| `/home` | Personal directories of regular users |
| `/etc` | Configuration files |
| `/var` | Variable data |
| `/var/log` | System and application logs |
| `/tmp` | Temporary files |
| `/root` | Home directory of the root user |

---

##  Hands-on Setup

### Virtualization Environment

- Host OS: Windows
- Hypervisor: VirtualBox
- Guest OS: Ubuntu
- Virtual Disk: 32 GB
- RAM allocated: 4 GB
- CPU allocated: 2 cores

### Linux Commands Practised

```bash
pwd
ls
cd
mkdir
touch
