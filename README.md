# Arch-Offline-Installer (WIP)
A completely offline, vanilla Arch Linux installer.

### Preview: 

![VirtualBox_Archboot_15_08_2024_00_04_25](https://github.com/user-attachments/assets/e5ee9972-2c11-4920-aa98-132df79c46ef)

# About this project:

### This project aims to enable users to quickly live test/install vanilla Arch Linux on their system, without the internet requirement of the official methods, by offering ISOs that come prepacked with everything needed OOTB.

## Features:

- Live session desktop enviroment, making Arch more accesible to new and old users. 
- For already existing Arch users, troubleshooting tools included.
- Drivers for AMD, Intel, Nvidia (wip), and wireless cards integrated.
- Vanilla Arch Linux base and a set of minimal desktop and CLI apps for a clean, functional system.
- No extra or additional apps like KDE Gear.
- Complete freedom of installing additional apps by the user after installation.
- Flatpak package included. On KDE Plasma, you can use discover to manage flatpak apps.
- Multilib repository enabled.
- Monthly ISO releases, keeping the system always up to date by following official Arch release schedule.
- Calamares Install Framework: making the installation process easier and more flexible.

### Note: This is a solo project work in progress, being done on my free time.

### Looking for the ISO? check out the releases section on this page. (soon)

*releases will be added once enough testing is done.*

# Help wanted
- to configure planned WMs spins
- to write project documentation and changelogs.
- beta testers with real hardware, mostly nvidia users.
- need help configuring boot entries, so users can boot either with open source drivers, nomodeset for fallback, and nvidia for nvidia users.
- help adding more features to calamares, like a package chooser.
- help with reviewing and improving the code.

# FAQ
1. Q: Are you making your own custom Arch-based distro?
   - A: No. This project goal isn't becoming an Arch based full fledged distro, but rather remain as close as possible to the vanilla base, but completely offline + minor tweaks inspired by Archboot project (https://archboot.com).
   
3. Q: Will you add X feature?
   - A: *placeholder*
   
5. Q: Can I install Arch with your ISO even if I have internet?
   - A: Yes, you can. the system will still not require internet to be installed nor use it at all. having an internet connection will not affect the installation process.
   
6. Q: How can I install this on my system?
   - A: I highly recommend using Ventoy (https://ventoy.net) to create your USB bootable media, as it's multiboot feature will come handy so you can try several spins of this project at once. once you create the bootable media, reboot to your USB and try the live desktop. on it, there's a desktop icon with the installer. double click it to begin the installation. follow the steps on screen.

7. Q: *placeholder*
   - A: *placeholder*
8. Q: *placeholder*

------------
# Project Background:
I started this project for myself, because after installing Arch countless times, using both the wiki, aka manual way, and the official archinstall script I thought:

- "What if the internet connection becomes unstable or just disconnects on the Wiki manual process?" 
- "what if official archinstall script is unable to properly configure the mirrors to the closest one to the user, giving errors, halting the installation, resulting on an unusable system?"
- "What if I just want to save bandwidth and time, by just using a local mirror so the process is more express?"
- "What if I want an express installation for testing Arch on a VM?"
- "What if I don't want to setup my system from the ground up, the wiki way all the time that I'm going to reinstall Arch, but have a quick, express way to have barebones, vanilla Arch?"

### So, to cover all those scenarios, mostly the internet requirement, I began my research, ending on this project. 
Taking inspiration from Archboot project (https://archboot.com/), which has a local mirrors ISO, and using EZArcher code as base, I began working on this project.

------------
# Credits:
1. Main code forked from EZArcher by EZnix on SourceForge, without him and his advice, this project would had never came to be.
   - Source project: https://sourceforge.net/projects/ezarch/
2. Main idea inspired by Archboot project, thanks to them for giving me advice and the base concepts and ideas to begin this project.
   - Website: https://archboot.com
3. Calamares Installer framework team
   - Github: https://github.com/calamares/calamares
   - Website: https://calamares.io/
4. Arch Linux dev team: for making such flexible, powerful distro. 
   - Homepage: https://archlinux.org
5. ArchWiki: one of the greatest Linux knowledge base on the web. without it I would not had been able to figure out things required for this project. 
    - https://wiki.archlinux.org/
6. Mostly aknowledgements to HikariNeee for their help with autologin, fixing scripts, helping finding reference manuals, code file structures, and great support with this project.


