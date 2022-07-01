## What exactly is Linux?

Technically, we don't call it Linux; instead, we call it GNU/Linux and that's what it was called originally.
Because Linux is the kernel developed by Linus Torvalds. <br>
The Linux kernel, utilities, and programmes built by GNU and other independent developers combinely forms the GNU/Linux Operating System.


## What is the Linux operating system?

1. Bootloader - <br>
The software that manages the boot process of your computer. It also executes the kernel, because the kernel is the first thing that loads before the main operating system.

2. Kernel - <br>
This is one piece of the whole that is actually called Linux. The kernel is the core of the system and manages the CPU, memory, and peripheral devices.

3. Init system - <br>
This is a sub-system that bootstraps the user space and is charged with controlling daemons. One of the most widely used init systems is systemd. Which also happens to be one of the most controversial. It is the init system that manages the boot process, once the initial booting is handed over from the bootloader (i.e. GRUB or GRand Unified Bootloader).

4. Daemons - <br>
These are background services (printing, sound, scheduling, networking, bluetooth, etc.) that either start up during boot or after you log into the desktop.

5. Graphical server - <br>
This is the sub-system that displays the graphics on your monitor. It is commonly referred to as the X server or just X.

6. Desktop environment - <br>
This is the piece that the users actually interact with. There are many desktop environments to choose from (GNOME, Cinnamon, Mate, KDE, XFCE, etc.). Each desktop environment includes built-in applications (such as file managers, configuration tools, web browsers, and games).

7. Applications - <br>
Desktop environments do not offer the full array of apps. Just like Windows and macOS, Linux offers thousands upon thousands of high-quality software titles that can be easily found and installed. Such as file managers, video/audio players, image viewers, browsers, etc.


## When we turn on the computer:
The very first BIOS/UEFI loads which makes sure all hardware (such as RAM, HDD, Keyboard, etc.) is properly connected and working (that's why we see light blink just after turning on the CPU cabinet) and then -

- BIOS/UEFI executes GPT/MBR
- GPT/MBR executes GRUB
- GRUB executes kernel
- Kernel executes init system
- Init system executes run level programs

And then, finally, we booted into the OS. <br>
So the Linux distro consists of these 7 things.


## What is a Linux Distro or Distribution?
As we know, Linux consists of the above 7 things. So different people/teams with their own/forked base, package manager and different choice of apps, and above things created their own Linux version called as Linux distro.

For example, <br>
The Linux mint team uses systemd as init, debian as base (apt package manager) and created their own distro. <br>
The Arch Linux with its own independent base, pacman package manager and systemd init made their own distro. <br>
So there are many distros viz Arch, Ubuntu, Manjaro, Fedora, Void etc. with their own base/source, apps and features.


## What is a Desktop Environment?
DE are things we actually look at and interact with. Different people/teams have created their own taste of DE with their own taste apps which they suite.

For example, <br>
XFCE has a thunar file manager, parole media player, restreto image and XFCE terminal. Its theme is based on gtk. <br>
Cinnamon has nemo file manager, rythombox audio player, gnome terminal and inbuilt theming app, applets and extensions. <br>
Both are created by different people and teams as per their needs.


## Why are there so many ISOs with different versions of a Linux distribution?
Because of the above reasons, every distro has different versions according to different desktop environments they offer, <br>
Like Linux Mint offers Linux Mint XFCE, Linux Mint Cinnamon, etc. Same with Manjaro KDE, Manjaro XFCE, etc.
