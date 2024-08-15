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
- to configure WMs/write documentation
- beta testers with real hardware, mostly nvidia users
- need help adding an nvidia boot option to grub ISO
- help adding more features to calamares
- help with cleaning the code

# FAQ
1. Q: Are you making your own custom Arch-based distro?
   R: No. this project goal isn't becoming an Arch based full fledged distro, but rather remain as close as possible to the vanilla base, but completely offline + minor tweaks inspired by Archboot project (https://archboot.com).
2. Q: Will you add X feature?
R: 
3. *placeholder*
4. *placeholder*  

------------
# Personal Insight:
I started this project for myself, after installing Arch countless times, using both the wiki, manual way, and the official archinstall script. great, you get a vanilla barebones system, but I've faced times when the internet connection became unstable or just disconnected, rendering the install process into a broken mess. after researching, and trying several solutions, including archboot, from which I took inspiration for this project (https://archboot.com/), I was still unsatisfied with the results. so, I began working on this. 

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


