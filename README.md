# AUR Packages

A collection of **PKGBUILDS** I maintain for the [Arch User Repository](https://aur.archlinux.org), currently including:
 - [odin2-synthesizer](https://aur.archlinux.org/packages/odin2-synthesizer)
    (deprecated - now in the [Community](https://archlinux.org/packages/community/x86_64/odin2-synthesizer/) repository)
 - [odin2-synthesizer-bin](https://aur.archlinux.org/packages/odin2-synthesizer-bin)
    (deprecated - now in the [Community](https://archlinux.org/packages/community/x86_64/odin2-synthesizer/) repository)

## Installation:

**Using Paru (or other AUR-helper):**
 - `paru -S <package_name>`

**Manually, from AUR:**
 - `git clone https://aur.archlinux.org/<package_name>`
 - `cd <package_name>`
 - `makepkg -si`

**Manually, from Github:**
 - `git clone --recurse-submodules https://github.com/ralgar/aur-packages`
 - `cd aur-packages/<package_name>`
 - `makepkg -si`
