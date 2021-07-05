The [makedeb User Repository](https://MUR.hunterwittenborn.com) (MUR) is a user-maintained repository of build files (PKGBUILDs) that can be built with [makedeb](/makedeb/intro.md) and then installed with APT.

The MUR takes its roots in the [Arch User Repository](https://wiki.archlinux.org/title/Arch_User_Repository), from which most of its features are derived.

The MUR was designed to aid users who use makedeb on Debian systems to more easily find and build their favorite packages that might not be in their distribution's repositories.

The MUR was also made to solve a lingering problem with alternatives such as PPAs: centralization.

With PPAs, you only get a select group of packages with each repository. On top of this, PPAs require adding extra signing keys to your system, can become out of date easily, and can become hard to manage when you want to remove them from your system.

Everything in the MUR is inside of a central repository, meaning you don't have to scour for the packages you want across multiple repositories.

If you want to remove the MUR from your system, there's also no configuration files to remove. Just uninstall the offending packages, and you're done.

The MUR also makes it easier for users to start sharing their own packages through the use of the PKGBUILD package format. Other Debian-based build utilities often require configuring multiple files, and require a more complex setup compared to PKGBUILDs, which, in most circumstances, only consists of a single file.