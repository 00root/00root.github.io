---
title: serive now interview
tags:
---
# System
kernel, syscalls, performanace

A kernel is a complex piece of software that manages the processes and process interactions that take place within an operating system.

The general steps when any modern computer is truned on:
- The CPU initializes its internal hardware state, loads microcode etc.
- The CPU commences execution of the initial boot code, eg The BIOS on x86 or the boot-loader on ARM.
- The boot code loads and executes the kernel. x86 systems generally use the BIOS to load an intermediate loader such as GRUB or syslinux, which then
fetches and starts the kernel.
- The kernel configures the hardware and executes the init process.
- The init process executes other processes to get all the required software running.

The kernel's role in the system is to provide a generic interface to programs, and arbitrate access to resources.

The first process is provided by a program named /sbin/init


What is a kernel panic?
It is an action taken by linux kernel when it experiences a situation form where it can't recover saftely.
It can be caused due to various reasons:
1. Hardware failure
2. Software bus in the OS.
3. During booting the kernel panic can happen due to one of the reasons-
a.Kernel not correctly configured, compiled or installed.
b.Incompatibility of OS, hardware failure including RAM.
c.Missing device driver
d.Kernel unable to locate root file system
e.After booting if init process dies.
