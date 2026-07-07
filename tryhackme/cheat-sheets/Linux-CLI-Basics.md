# Linux CLI Basics

## What is CLI
Command-Line Interface (CLI) is a text-based interface for controlling am operating system, text is input into the "Terminal". It uses text/syntaxes to control what you need on the computer.
This would be how early operating systems would work before the invention of Graphical User Interfaces (GUI)

### Some perks of using Terminal
- It's faster than clicking around a GUI
- Much more control over the computer
- Many security tools only run in the terminal

## 👾 ** Standard commands (Basic) **
### Directories
1. PWD | Print Working Directory, I used this to see which directory I'm in so I can navigate from there, to my file.
2. ls | List Contents, I used this to see which files and folders are contained in my current working directory.
3. ls -L | List Contents in detail, I used this to see more info on my files/folders. I.e. file sizes, permissions, dates etc.
4. ls -al | List all contents, I used this to show all "Hidden but not really" files and folders. Linux hides these files as they start with a "."
5. cd | Change Directory, I used this to change from my original working directory, into the /Documents folder.
6. cd .. | Back a level, I used this to go back to my original working directory, it can be used to go back if you go one step too far.
7. find | Find a file, I used this to locate my mission brief file. You need to input a starting point/directory  before inputting file name. I.e the symbol ~ indicates the home directory.
I.E. (find ~ -name mission_brief.txt)

### System
1. whoami | prints which user you're logged in as.
2. uname -a | Provides a full line of system info

### Disk/Storage
1. df -h | This provides a breakdown of disk usage as well as available space. -h stands for human readable. Tmpfs are temporary file systems stored on RAM, not the physical disk/drive. SHM is shared memory.




