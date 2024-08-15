# Arch-Offline-Installer (WIP)
A completely offline, vanilla Arch Linux installer.

### Preview: 

![VirtualBox_Archboot_15_08_2024_00_04_25](https://github.com/user-attachments/assets/e5ee9972-2c11-4920-aa98-132df79c46ef)

# About this project:

This project aims to simplify the process of installing vanilla Arch Linux on x86-64 systems, by releasing fully fledged, offline isos with everything already prepacked for a daily use.

No extra apps will ever added, but the base arch + barebones to have a functional system. Drivers for AMD, Intel, Nvidia (wip), and wireless cards are already integrated, so you don't need to add it yourself after a minimal, barebones base Arch installation. it should work as intended on most sytems.
Additionally, the ISOs can be used to rescue already installed systems, as those include all the neccesary tools to troubleshoot. you can chroot, clone, partition and more if you ever have the need, while still keeping the Arch KISS philosophy. 

The isos boot into a live enviroment from where the user can live test the system, do troubleshooting, or proceed to install, by using the Calamares Installer framework.


### Note: This is a solo project work in progress, being done on my free time.

*releases will be added once enough testing is done.*
*automated monthly releases are planned.*


# Help wanted
- to configure planned WMs spins
- to write project documentation and changelogs.
- beta testers with real hardware, mostly nvidia users.
- need help configuring boot entries, so users can boot either with open source drivers, nomodeset for fallback, and nvidia for nvidia users.
- help adding more features to calamares, like a package chooser.
- help with reviewing and improving the code.

# FAQ
1. Q: Are you making your own custom Arch-based distro?
   A: No. This project goal isn't becoming an Arch based full fledged distro, but rather remain as close as possible to the vanilla base, but completely offline + minor tweaks inspired by Archboot project (https://archboot.com).
   
3. Q: Will you add X feature?
   A:
   
5. Q: Can I install Arch with your ISO even if I have internet?
   R: Yes, you can. the system will still not require internet to be installed nor use it at all. having an internet connection will not affect the installation process.
   
7. Q: How can I install this on my system?
8. A: I highly recommend using Ventoy (https://ventoy.net) to create your USB bootable media, as it's multiboot feature will come handy so you can try several spins of this project at once. once you create the bootable media, reboot to your USB and try the live desktop. on it, there's a desktop icon with the installer. double click it to begin the installation. follow the steps on screen.

9. Q: *placeholder*
   A: *placeholder*
10. Q: *placeholder*

------------
# Project Background:
I started this project for myself, because after installing Arch countless times, using both the wiki, aka manual way, and the official archinstall script I thought:

- "What if the internet connection becomes unstable or just disconnects on the Wiki manual process?" 
- "what if official archinstall script is unable to properly configure the mirrors to the closest one to the user, giving errors, halting the installation, resulting on an unusable system?"
- "What if I just want to save bandwidth and time, by just using a local mirror so the process is more express?"
- "What if I want an express installation for testing Arch on a VM?"
- "What if I don't want to setup my system from the ground up, the wiki way all the time that I'm going to reinstall Arch, but have a quick, express way to have barebones, vanilla Arch?"

### So, to cover all those scenarios, mostly the internet requirement, I began my research, ending on this project. 
Taking inspiration from Archboot project (https://archboot.com/), which has a local mirrors ISO, and using EZArcher code as base, this project began to be.

------------
# Credits:
1. Main code forked from EZArcher by EZnix on SourceForge, without him and his advice, this project would had never came to be.
Source project: https://sourceforge.net/projects/ezarch/
2. Main idea inspired by Archboot project, thanks to them for giving me advice and the base concepts and ideas to begin this project.
3. Calamares Installer framework team
  Github: https://github.com/calamares/calamares
  Website: https://calamares.io/
4. Arch Linux dev team: for making such flexible, powerful distro. Homepage: https://archlinux.org
5. ArchWiki: one of the greatest Linux knowledge base on the web. without it I would not had been able to figure out things required for this project. visit it at https://wiki.archlinux.org/
6. Mostly aknowledgements to HikariNeee for their help with autologin, fixing scripts, helping finding reference manuals, code file structures, and great support with this project.


