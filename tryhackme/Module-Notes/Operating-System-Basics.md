# Operating System Basics

## What is an operating system (OS)
An operating system is the main software which coordiantes all computer activity. It acts as the invisible manager that keeps everything run as one main system. Without an OS, each application would need direct control over the CPU, memory, files, devices, and security. This would quickly cause conflicts.

![alt text](image-1.png)

## System Privilege Layers

Inside a modern computer, different parts of the system operate at various permission levels. Some components can communicate directly with the hardware, while regular applications run in a safer, restricted environment. This separation is intentional and helps prevent conflicts and security issues.

- Kernel Space:- This is the privellaged, locked-down core of the OS. This is where the Kernel, which manages hardware and system resources, runs. It has unrestricted access to all hardware.
- User Space:- This is where all standard applications run. All applications within this space deliberatley prevented from accessing hardware directly. When they want to open or save a file, play soun/music or connect to wifi, they must make a call to the system and request that the kernel acts on their behalf. 

## Operating System Duties
| OS Responsibility | What the OS does | Example |
|-------------------|------------------|---------|
| Process Management|Creates, schedules, prioritizes, and terminates running programs. The OS decides how much CPU time each process gets, making multitasking feel seamless | Opening multiple apps, like your browser, music player, and social media, without your computer freezing.	
| Memory Managmenet | Allocates RAM to processes, protects the app's memory from other processes, and reclaims memory when apps are closed. When RAM runs low, the OS uses virtual memory to keep your system stable. | Opening multiple app at once, the OS allocates RAM to each one and keeps them isolated so they don’t interfere or crash each other. |
| File System Managements | Organizes files into directories, handles naming, paths, permissions, metadata (name, size, type, timestamps) | Creating a new folder, saving a photo, or setting a file to "read only" |
| User Management | Handles multiple user accounts, authentication, and permissions to determine who can access what. | Logging in with your password and keeping your files inaccessible to other user accounts. |
| Device Management | Loads drivers and provides a universal interface (hardware abstraction layer), so apps can say “print this” or “play this sound” | Plugging in a new mouse, printer, or external hard drive and having it work immediately. |


