# linux-distros-ultimate-guide

## about
This project of mine has one goal: to list and describe as many distros that I possibly can. While it is mostly for my hobby, you can search fore some distros here :3

## faq
- *What is considered to be an "anti-feature"?* \
***anti-features are, but not limited to:***
    - **anti-consumer practices**
    - **support of non-free software**
    - **paid**
    - **not-transparent**
- *What is the review scale for categories?* \
***depending on category, these are those:***
    - **open-source**:
        - *yes*
        - *no*
        - *partially*
    - **user-experience required**:
        - *beginner*
        - *amateur*
        - *intermediate*
        - *advanced*
        - *passionate / expert*

## to-the-list

- [Arch Linux](https://archlinux.org/):

    ```
    name: arch linux
    package manager: pacman
    release system: rolling-release
    default environment: none, diy
    user-experience required: advanced
    open-source: yes
    anti-features?: none
    ```

    - [Manjaro](https://manjaro.org)
        
        ```
        name: manjaro
        package manager: pacman
        release system: special rolling-release
        default environment: gnome / kde plasma / xfce
        user-experience required: amateur
        open-source: yes
        anti-features?: no
        pre-installed software: pamac
        ```
        > :information_source: **INFO**: While Manjaro uses Arch rolling-release system, it is often delayed by another 2 weeks, for "stability purposes". For a true rolling-release experience, please disable it or use another distro.

    - [EndeavourOS](https://endeavouros.com/)
        
        ```
        name: endeavouros
        package manager: pacman
        release system: rolling-release
        default enviroment: many
        user-experience required: intermediate
        open-source: yes
        anti-features?: no
        pre-installed software: pamac
        ```

        > :information_source: **INFO**: Possible default enviroments include: xfce, kde plasma, gnome, mate, cinnamon, budgie, lxqt, lxde, i3
    
    - [SteamOS 3.0+](https://store.steampowered.com/steamos/download?ver=steamdeck)

        ```
        name: steamos
        package manager: pacman
        release system: rolling-release
        default enviroment: kde plasma
        user-experience required: beginner
        open-source: partly
        anti-features?: support of non-free software
        pre-installed software: steam, kde discover
        ```

        > :information_source: **INFO**: While SteamOS version 3.0 and later are based on Arch, the previous versions are based on Debian
        
        > :information_source: **INFO**: While possible for instaling it on your daily drive machine, it is not advised due to system focus on gaming on Steam Deck, as well as limited out-of-the-box features

        > :warning: **WARNING**: While system, and steam client are open-source, the architecture of Steam network is not. While this should not cause any endangerment (due to obvious reasons it needs to be closed-source for valve), users who focus on FOSS compatibility should use this system with caution and reconsider using it.

    - [Arch Linux ARM](https://archlinuxarm.org/)

        ```
        name: archlinuxarm
        package manager: custom
        release system: rolling-release
        default enviroment: none, diy
        user-experience required: advanced
        open-source: yes
        anti-features?: no
        ```

        > :information_source: **INFO**: Arch Linux ARM is, as expected, an ARM adaptation of Arch Linux. It cannot thus be used on machines not using ARM CPUs, and the list of supported devices is [very small](https://archlinuxarm.org/platforms)

    - [GarudaLinux](https://garudalinux.org/)

        ```
        name: garudalinux
        package manager: pacman
        release system: rolling-release
        default enviroment: many
        user-experience required: intermediate
        open-source: yes
        anti-features?: no
        pre-installed software: garuda assistant, firedragon, chaotic-aur, garuda gamer
        ```
        
        > :information_source: **INFO**: Garuda Linux is meant to be an Arch distribution specified for gaming purposes, for other special purposes, it is not advised to use it
        
        > :information_source: **INFO**: Default enviroments include: kde plasma, xfce, gnome, cinnamon, qtile, i3, sway and hyprland

    - [Artix Linux](https://artixlinux.org/)

        ```
        name: artixlinux
        package manager: pacman
        release system: rolling-release
        default enviroment: none, diy
        user-experience required: advanced
        open-source: yes
        anti-features?: no
        ```

        > ℹ️ **INFO**: Artix Linux is meant to be a fork of Arch, but without systemd

    - [Parabola](https://www.parabola.nu/)

        ```
        name: parabola
        package manager: modified pacman
        release system: rolling-release
        default enviroment: none / lxde
        user-experience required: passionate / expert
        open-source: yes
        anti-features?: no
        ```

        > ℹ️ **INFO**: Some packages which are considered non-FOSS may be not possible to install out-of-the-box, due to Libre and Free character of distribution. Due to this, some people may find Parabola lacking

        > ℹ️ **INFO**: Parabola uses special list of packages named [Parabola GNU/Linux-libre package database](https://www.parabola.nu/packages/)