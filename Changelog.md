# Project history log:
08-12-2024
begin forking the code from ezarcher, starting testing on VMs
created his repo. 1st commit and began working on the repo file structure.


08-13-2024
changed branding to project name. changed kernel from LTS back to vanilla linux, added kernel-headers. 
added missing plasma welcome center, removed redundant apps, added missing packages, improved plasma desktop. 
tweaks to the booting process, reducing boot times for the ISO and the installed system.

08-14-2024
began to write the readme.md
added proper credits to the sources.
changed liveuser name, root liveuser name and password to distro defaults
more fixes to the packagelist, removing pulseaudio in favor of pipewire
added partitioning and disk management tools that weren't present on the source code but are on base archiso.
began to write the todo list, as I detected issues on the base code.

08-15-2024
fixed issues with calamares not automatically loging into the live session, fix provided by HikariNeee
added more GPU drivers for AMD and Intel. Added experimental support for Nvidia GPUs, created testing and testing-release branches
began to work on calamares branding, added missing code to the modules.
fixed live session asking for sudo password to do sudo actions, allowing the execution of calamares without a sudo password.
created more spins folders, set goals to create a gnome spin and more.
added more formatting to readme.md, fixing sources and credits.
