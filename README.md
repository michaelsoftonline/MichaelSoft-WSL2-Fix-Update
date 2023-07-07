**Do note that antivirus had to be turned off as it will break this update.**
steps:
1. Press Windows button and search for "Windows Security"
2. Select "Virus & Threat Protection"
3. Under "Virus & Threat Protection Settings", select "Manage Settings"
4. Turn off all of the options
5. You may need to restart your computer to process the patch

# MichaelSoft-WSL2-Fix-Update
WSL2 fix for Windows Docker.

Download the zip file, extract and run wsl2-fix.exe

Comparing WSL 1 and WSL 2

This guide will compare WSL 1 and WSL 2, including exceptions for using WSL 1 rather than WSL 2. The primary differences between WSL 1 and WSL 2 are the use of an actual Linux kernel inside a managed VM, support for full system call compatibility, and performance across the Linux and Windows operating systems. WSL 2 is the current default version when installing a Linux distribution and uses the latest and greatest in virtualization technology to run a Linux kernel inside of a lightweight utility virtual machine (VM). If your distribution is currently running WSL 1 and you want to update to WSL 2, see update from WSL 1 to WSL 2.

Prerequisites

    Ensure your machine is running Windows 10, updated to version 2004, Build 18362 or later.
    Install WSL and set up a user name and password for your Linux distribution running in WSL 2.
    Install Visual Studio Code (optional). This will provide the best experience, including the ability to code and debug inside a remote Docker container and connected to your Linux distribution.
    Install Windows Terminal (optional). This will provide the best experience, including the ability to customize and open multiple terminals in the same interface (including Ubuntu, Debian, PowerShell, Azure CLI, or whatever you prefer to use).
    Sign up for a Docker ID at Docker Hub (optional).
    See the Docker Desktop license agreement for updates on the terms of use.

