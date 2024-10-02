# StratOS iso
---
This repo contains the files required to build the [StratOS Hyprland spin](https://github.com/StratOS-Linux/hyprland-iso).

The ISO can be built and tested on all Arch-based distributions. 

Ensure that you have `archiso` installed from the [Arch repositories](https://archlinux.org/packages/extra/any/archiso/).
To test the ISO, simply clone this repo and run the build script provided:

```bash
git clone https://github.com/StratOS-Linux/Hyprland-iso
cd Hyprland-iso
./build.sh
```

This would produce an ISO that is suitable for installation in VMs and on bare metal.
