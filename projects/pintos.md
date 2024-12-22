---
layout: project
type: project
image: img/Pintos.jpeg
title: "Pintos"
date: 2024
published: true
labels:
  - Operating Systems
  - Unix
  - C
summary: "An educational operating system framework designed to teach core concepts like threading, memory management, system calls, and file systems through hands-on kernel programming assignments."
---

Pintos is a lightweight educational operating system designed for teaching core operating system concepts through practical programming assignments. It provides a simple kernel that students extend and improve by implementing features like thread management, synchronization, system calls, process management, virtual memory, and file systems. Typically run on simulators like QEMU or Bochs, Pintos offers a hands-on experience with low-level programming in C, allowing students to explore how operating systems manage hardware and software interactions. It is widely used in university courses to deepen understanding of operating system design and development.

## Project A: Threads

Project A focuses on enhancing Pintos' thread management capabilities by implementing features like priority scheduling, synchronization primitives (e.g., locks, semaphores, and condition variables), and efficient handling of thread states. Students begin by analyzing the basic thread implementation provided by Pintos and then modify it to support advanced scheduling policies, such as priority donation to avoid priority inversion. This project emphasizes concurrency and synchronization, requiring students to debug and resolve issues like race conditions and deadlocks while gaining a deeper understanding of multithreading and kernel-level programming.

## Project B: User Programs

Project B: introduces the concept of running user-level programs on the Pintos operating system. Students implement system calls to allow communication between user programs and the kernel, enabling functionalities like file I/O, process creation, and termination. The project involves creating a robust system call interface, managing program execution through proper loading and termination mechanisms, and ensuring security and isolation between user programs. Key challenges include implementing argument parsing, validating user memory access, and handling multiple processes concurrently. This project deepens understanding of process management and the interaction between user-space and kernel-space in an operating system.

## Project C: Virtual Memory

Project C focuses on implementing demand paging and improving memory management in Pintos. Students enhance the operating system's ability to handle larger programs by loading pages into memory on demand rather than all at once, optimizing memory usage. This project involves designing and managing a page table, implementing page replacement policies, and handling page faults efficiently. Additional features may include support for memory-mapped files and swapping pages between memory and disk. Students face challenges like managing concurrency, ensuring correct data synchronization, and optimizing performance, gaining a deeper understanding of virtual memory systems and resource allocation in an operating system.

## Project D: File System

Project D focuses on extending and improving Pintos' file system capabilities to support more advanced features. Students enhance the basic file system by implementing functionalities like subdirectories, file growth, persistence, and synchronization for concurrent access. This project requires designing and managing directory structures, maintaining metadata, and ensuring crash recovery mechanisms. Key challenges include handling file system consistency, implementing efficient data allocation strategies, and optimizing disk I/O. Through this project, students gain hands-on experience with file system design, data structures for storage management, and integrating complex components into a functional operating system.
