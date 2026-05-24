Pintos Project 2: User Programs
Overview
This repository contains the implementation of Project 2 (User Programs) for the Pintos operating system.

In this project, we expand the capabilities of the Pintos kernel to support running user programs. While the base code provided the foundation for loading and executing programs, it lacked support for Input/Output (I/O) and interaction with the operating system. Our task was to implement system calls and manage the complexities of process execution, memory management, and scheduling within the userprog directory.

Key Features
System Call Implementation: Enabling user programs to interact with the kernel safely.

Process Management: Managing multiple processes simultaneously while maintaining the illusion that each program has full control over the machine.

Kernel-User Interface: Ensuring the kernel correctly handles user program requests and adheres to the specified interface requirements.

Resource Management: Handling memory allocation, scheduling, and state management for concurrent processes.

Development Context
Target Directory: userprog/

Environment: The project builds upon the Pintos operating system infrastructure.

Scope: This project focuses on the interaction between user-space applications and the kernel, ensuring robust and correct OS behavior under multi-process execution.
