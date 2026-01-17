# linux
The name given OS that are built around Linux kernel
Different OS that use the Linux kernal are called Linux Disrtos
distros include other sets of common tools
Linux is free and open source

# Linux is felxible
Every linux system has:
a kernal
a userspace
files and resources
core tools
security boundries

# The Linux Kernal
The core of Linux Distros
open source, with many contributors
Originally released be Linus Torvalds in 1991
Permissive lincensing enables broad use
Is software that communicates with computer hardware
can run on its own, but isn't very useful that way
A kernel is requuired to run software on a PC
can run on a wide range of hardware
can be built to include for varied hardware or specific hardware (pcs, mobile devices, and even cars)
not interacted with directly most users
can be edited to make changes

# A Linux System
requires a linux kernel
uses other software to control the boot process and manage running systems
offers a large amount of customization for those who are interested in exploring it

# Interacting with a Linux System
1) graphical or desktop Env
2) shell or CMD-line Env

* windows and mac us gaphical Env
* linux use multiple Envs

# Linux Desktop Env
We can install and switch between various desktop env
many distros make a choice about which desktop they use
popular desktop envs include GNOME shell, KDE Plasma Desktop, LXQt, Cinnamon, MATE, and Xfce (most commonly used)
some taks require a desktop env, but others require a text-based shell

# Linux shell
The software we interact with when typing commands and veiw returned text
popular shells include Bash, Zsh, csh, fish, ksh
bash is a good start

# Terminal Emulators
A shell can run inside of a terminal emulator in a GUI evn, or i text mode
Windows and mac OS have terminal emulators, can be used with SSH to connect remotely to Linux

* Its good to be familiar with shell, reguardless of what you use the Linux system for

some task require GUI
use SSH to connect to remote systems

#  Core Tools
A kernel by itself isn't very useful
Linux Distros come with command-line tools to perform tasks
Most Linux Distros include GNU core utilsities (coreutils)
Manipulate files, set access permissions, very system status, etc.
These allow a basiic Linux install to be functional and provide standard tool sets

# Using the coreutils
Learning linux command
common commands should be memorized
many are for very specific use cases and are otfen not used
genereally pre-installed on any Linux Distro
not shell, no worries

# BusyBox
some systems use busybox istead of GNU coreutils
BusyBox is often in embedded/ lightweight systems
offers similar commands to GNU coreutils

* Software can be added to a linux system in a variety of ways

# install for repos
repos are collections of software pkges
using pkge managment software, search repo pkges and install, remove, & update them
pkge management tools usually handle dependencies
A system's security updates come from repos, many systems will automatically check and install sec updates

# package managment tools
There are few different pkge management ecosystems, like APT and DNF
Choice of pkge management echosystem is a core part of defining a distribution
Modern pkge management tools will:
  retrieve pkges from repos
  Follow instructions in the pkges to put the pkges files in appropriate places

# The role of source code
Software in pkges are built or compiled from source code
We can compile source code 
Create/ download source code
Use a compiler to create executable programs
Complex source code may require extensive tooling to build manually

# sandbox packages
Allow software to be installed in platform-dependent ways
Solutions include snaps, flatplak, and appimage
Manages software as monolithic, isolated apps instead of installing various files throughout our system files
These have advantages and drawbacks

  
