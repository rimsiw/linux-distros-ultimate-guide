# linux-distros-ultimate-guide

## about
This project of mine has one goal: to list and describe as many distros that I possibly can. While it is mostly for my hobby, you can search fore some distros here :3

## faq
- *What is considered to be an "anti-feature"?* \
***anti-features are, but not limited to:***
    - **anti-consumer practices**
    - **support of non-free software**
    - **paid**
    - **paid features**
    - **not-transparent**
    - **data collection**
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
    - **category**:
        - *desktop*
        - *live*
        - *server*
        - *education*
        - *gaming*
        - *mobile*
        - *security*
        - *light*
        - *other*

## to-the-list

### arch-based

- [Arch Linux](https://archlinux.org/):

```
name: arch linux
base: independent
category: desktop
package manager: pacman
release system: rolling-release
default environment: none, diy
user-experience required: advanced
open-source: yes
anti-features?: none
```

> ⭐ **RECOMMENDED**

- [Manjaro](https://manjaro.org)
        
    ```
    name: manjaro
    base: arch
    category: desktop
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
    base: arch
    category: desktop
    package manager: pacman
    release system: rolling-release
    default enviroment: many
    user-experience required: intermediate
    open-source: yes
    anti-features?: no
    pre-installed software: pamac
    ```

    > ⭐ **RECOMMENDED**

    > :information_source: **INFO**: Possible default enviroments include: xfce, kde plasma, gnome, mate, cinnamon, budgie, lxqt, lxde, i3

- [SteamOS 3.0+](https://store.steampowered.com/steamos/download?ver=steamdeck)

    ```
    name: steamos
    base: arch
    category: gaming
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
    base: arch
    category: desktop, mobile
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
    base: arch
    category: gaming
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
    base: arch
    category: desktop, light
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
    base: arch
    category: desktop, education, light
    package manager: modified pacman
    release system: rolling-release
    default enviroment: none / lxde
    user-experience required: passionate / expert
    open-source: yes
    anti-features?: no
    ```

    > ⭐ **RECOMMENDED**

    > ℹ️ **INFO**: Some packages which are considered non-FOSS may be not possible to install out-of-the-box, due to Libre and Free character of distribution. Due to this, some people may find Parabola lacking

    > ℹ️ **INFO**: Parabola uses special list of packages named [Parabola GNU/Linux-libre package database](https://www.parabola.nu/packages/)

    > 👍 **SPECIAL**: Parabola is listed by Free Software Foundation as free software distribution

- [CachyOS](https://cachyos.org/)

    ```
    name: cachyos
    base: arch
    category: desktop, light
    package manager: pacman
    release system: rolling-release
    default enviroment: many
    user-experience required: amateur
    open-source: yes
    anti-features?: no
    pre-installed packages: cachy-browser
    ```

    > ℹ️ **INFO**: Default desktop enviroments include: kde plasma, gnome, xfce, cutefish, i3, wayfire, lxqt, lxde, openbox, cinnamon, ukui, mate, budgie, qtile, hyprland and sway

- [AthenaOS](https://github.com/Athena-OS)

    ```
    name: athenaos
    base: arch
    category: desktop, security, light, live, other
    package manager: pacman
    release system: rolling-release
    default enviroment: gnome
    user-experience required: intermediate
    open-source: yes
    anti-features?: no
    pre-installed software: athena-cyberhub, hackthebox-tools, pwnage-menu, blueteam-menu, readteam-menu, payload-to-dock, nist-feed
    ```

    > ℹ️ **INFO**: AthenaOS main target are mostly hackers and testers. If you are not an aspiring or experienced person who might benefit from this system, there is probably no need to install it

### debian-based

- [Debian](https://www.debian.org/)

    ```
    name: debian
    base: independent
    category: desktop, server
    package manager: apt
    release system: stable
    default enviroment: many
    user-experience required: intermediate
    open-source: yes
    anti-features?: no
    ```

    > ℹ️ **INFO**: Default enviroments include: kde plasma, gnome, xfce, lxqt, lxde, mate, openbox, i3, fluxbox, cinnamon

- [MX Linux](https://mxlinux.org/)

    ```
    name: mxlinux
    base: debian, antiX
    category: desktop, light
    package manager: apt
    release system: stable
    default enviroment: xfce / kde plasma / fluxbox
    user-experience required: amateur
    open-source: yes
    anti-features?: no
    ```

#### ubuntu-based

- [Ubuntu](https://ubuntu.com/)

    ```
    name: ubuntu
    base: debian
    category: desktop
    package manager: apt, snap
    release system: stable
    default enviroment: gnome
    user-experience required: beginner
    open-source: partly
    anti-features?: not-transparent, support of non-free software, anti-consumer practices, data collection
    ```

    > ⚠️ **WARNING**: Ubuntu is own by Canonical, a british company known for their anti-consumer practices. Please, if you value your privacy and security, DO NOT use plain Ubuntu

    > ℹ️ **INFO**: Ubuntu comes in many flavours, including, for example, [Kubuntu](https://kubuntu.org/). While they technically are their own distributions, I won't be including them there

- [Linux Mint](https://linuxmint.com/)

    ```
    name: linuxmint
    base: ubuntu
    category: desktop
    package manager: apt
    release system: stable
    default enviroment: cinnamon / xfce / mate
    user-experience required: beginner
    open-source: yes
    anti-features?: no
    ```

    > :star: **RECOMMENDED**

- [Pop!_OS](https://pop.system76.com/)

    ```
    name: pop_os
    base: ubuntu
    category: desktop
    package manager: apt
    release system: stable
    default enviroment: gnome
    user-experience required: beginner
    open-source: yes
    anti-features?: no
    ```

- [ZorinOS](https://zorin.com/os/)

    ```
    name: zorin
    base: ubuntu
    category: desktop
    package manager: apt
    release system: stable
    default enviroment: gnome, xfce
    user-experience required: beginner
    open-source: no
    anti-features?: paid features, data collection, not-transparent
    ```

    > :warning: **WARNING**: If you value your privacy, PLEASE DO NOT use Zorin. Zorin shows signs of data collection, and their business model is about selling expensive paid plans with otherwise free features

    > :warning: **WARNING**: ZorinOS is NOT open-source. I advise you to not use it