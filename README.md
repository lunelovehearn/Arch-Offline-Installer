# Arch-Offline-Installer (WIP)
A completely offline, vanilla Arch Linux installer.

# Introduction:

This project aims to simplify the process of installing vanilla Arch Linux on x86-64 systems, by releasing fully fledged, offline isos with everything already prepacked for a daily use.

No extra apps will ever added, but the base arch + barebones to have a functional system. Drivers for AMD, Intel, Nvidia (wip), and wireless cards are already integrated, so you don't need to add it yourself after a minimal, barebones base Arch installation. it should work as intended on most sytems.
Additionally, the ISOs can be used to rescue already installed systems, as those include all the neccesary tools to troubleshoot. you can chroot, clone, partition and more if you ever have the need, while still keeping the Arch KISS philosophy. 

As such, this project goal isn't becoming an Arch based full fledged distro, but rather remain as close as possible to the vanilla base, but completely offline + minor tweaks inspired by Archboot project (https://archboot.com).

The isos boot into a live enviroment from where the user can live test the system, do troubleshooting, or proceed to install, by using the Calamares Installer framework.

# Personal Insight:
I started this project for myself, after installing Arch countless times, using both the wiki, manual way, and the official archinstall script. great, you get a vanilla barebones system, but I've faced times when the internet connection became unstable or just disconnected, rendering the install process into a broken mess. after researching, and trying several solutions, including archboot, from which I took inspiration for this project (https://archboot.com/), I was still unsatisfied with the results. so, I began working on this. 



### Note: This is a work in progress, being done on my free time.

releases will be added once enough testing is done.
automated monthly releases are planned.

### Preview: 

![Captura de pantalla_20240814_125558](https://github.com/user-attachments/assets/5669d358-5283-4b54-a552-45d2698eadbd)


# Help wanted
- to configure WMs/write documentation
- beta testers with real hardware, mostly nvidia users
- need help adding an nvidia boot option to grub ISO
- help adding more features to calamares
- help with cleaning the code

  
## TO-DO list:

- ~~remove root password requirement on live session login~~ thanks to HikariNeee for the fix. (https://github.com/HikariNeee)
- ~~enable autologin~~ fixed thanks to HikariNeee
- add calamares installer icon on live session desktop
- make calamares not ask for sudo password when being launched to install
- set a custom wallpaper for the live session
- make a script that removes calamares icon and itself once the system reboots to the newly installed system
- add nvidia hardware support and boot entry (wip)
- create branding and clean up code
- add custom fonts package
- add encryption support/test it
- make the other DE spins, starting with GNOME
- you tell me :)

# Credits:
1. Main code forked from EZArcher by EZnix on SourceForge, without him and his advice, this project would had never came to be.
Source project: https://sourceforge.net/projects/ezarch/
2. Main idea inspired by Archboot project, thanks to them for giving me advice and the base concepts and ideas to begin this project.
3. Calamares Installer framework team
  Github: https://github.com/calamares/calamares
  Website: https://calamares.io/

