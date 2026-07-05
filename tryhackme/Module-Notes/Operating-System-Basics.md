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

## Operating System Security
Every OS acts as a security foudation. Before any antivirus, firewall, or security tool is introduced, the OS is already enforcing protections in the background.

Basic level OS operations:-
- Authentication: Verifies who you are through login passwords and biometrics
- Permissions: Controls exactly what each user and app is allowed to read, write, or execute
- Isolation: Keeps every process in its own protected box (kernel/user space separation)
- System Protection: Safeguards critical system files and settings from unauthorized changes

## OS Interfaces
The OS can be interacted with in two ways. The GUI (Graphical User Interface) and the CLI (Command Line Interface)

The GUI is what most people will be accustomed to using. It's a graphical representation of the information you're trying to access on your computer. I.e. folder icons, windows for your apps and settings menus.

The CLI is the same principle, but instead of using graphical buttons, you issue text-based commands. This system is faster, especially for advanced use cases however it requires familiarity with the syntax and specific commands required.
Think of it as inputting coordinates on your Sat Nav rather than using the GUI icons.

## The OS landsacpe

| OS Type | Primary Use Case | Key Characteristics |
|---------|------------------|---------------------|
| Desktop | Personal computers, daily work, gaming, content creation | Rich graphic interface, runs many apps at once, user-focused. |
| Server | Web hosting, databases, cloud services, back-end | Headless (no GUI), maximum uptime, multi-user, remote access. |
| Mobile | Smartphones and tablets | Touch-based UI, power efficient, always connected, app sandboxing. |
| Embedded | Appliances, cars, IoT devices, smart TVs, routers | Tiny footprint, runs on limited hardware. |
| Virtual/Cloud | Lab machines, containers, cloud instances | Lightweight, scalable, rapid deployment. |

## Real world OS

### Popular OS based on type

- Desktop / Laptop
    - Windows - Most common and widely used
    - MacOS - Most polished GUI and widley known for its intergration with other Apple devices.
    - Linux - A family of open-source operating systems like Ubuntu, Fedora.

- Server
    - Windows - large networks, data centres and corporate environments
    - Linux - Vast majority of servers use this. Reliable and open-source
    - Unix - Large enterprises, government, telecom and finance.

- Mobile
    - Android
    - iOS

- Embedded and IoT devices
    - Embedded Linux - Specialised OS built into devices with dedicated function ie, smart bulbs
    - Real-Time OS - Designed for apps which require guarenteed response times, i.e. aircraft controls.

- Virtual and Cloud
    - Cloud/VM - Massive data centres which host websites, applications and streaming services.
    - Container optimised - Lightweight alternatives to VMs that package just an app and its depndencies.


