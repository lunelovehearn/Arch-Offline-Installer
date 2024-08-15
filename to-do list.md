## TO-DO list:

- ~~remove root password requirement on live session login~~ thanks to HikariNeee for the fix. (https://github.com/HikariNeee)
- ~~enable autologin~~ fixed thanks to HikariNeee
- add calamares installer icon on live session desktop
- ~~make calamares not ask for sudo password when being launched to install~~ fixed. thanks to carli guide regarding /etc/sudoers.d and figured out by adding code to the users, groups and shadow section of the build.sh and pointing profiledef.sh to include the sudoers.d and polkit.d folders. still needs further testing.

- set a custom wallpaper for the live session (optional)
- make a script that removes calamares icon and itself once the system reboots to the newly installed system
- add nvidia hardware support and boot entry (wip)
- create calamares branding and clean up code
- add custom fonts package (fonts provided from my other font repo, will make an AUR package)
- add LUKS encryption support and test it
- add UKI/secure boot support
- make the other DE spins, starting with GNOME
- automated monthly releases following official Arch release schedule
- ...
- you tell me :)
