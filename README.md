# Fedora Atomic &nbsp; [![build-ublue](https://github.com/lorduskordus/fedora-atomic/actions/workflows/build-all.yml/badge.svg)](https://github.com/lorduskordus/fedora-atomic/actions/workflows/build-all.yml)

> The [Fedora Atomic Desktop](https://fedoraproject.org/atomic-desktops/) is a non-traditional Linux distribution, which provides additional stability and reliability by making parts of the system immutable. That means the base system always stays clean and in a working state. Updates are atomic and applied on reboot. When the system is updated and booted into, the previous state is kept. Should any problems occur, it is possible to rollback to that state.

> The [Universal Blue](https://universal-blue.org/) project takes Fedora Atomic OCI images and adds QoL changes on top, like NVIDIA drivers, codecs, distrobox or services providing automatic updates.

> The [BlueBuild](https://blue-build.org/) project makes image building easy by allowing you to declare your modifications in yaml files using modules with an easy to understand syntax, serving as an abstraction to a classic containerfile. The images are built daily by default using a GitHub Action.

The images built and provided by this repository are further customized with additional changes applied on top.

## Base Images

- Generic (kinda), should not break

##### COSMIC
```
ostree-image-signed:docker://ghcr.io/lorduskordus/fedora-base-cosmic
```
##### COSMIC (NVIDIA)
```
ostree-image-signed:docker://ghcr.io/lorduskordus/fedora-base-cosmic-nvidia
```
##### KDE
```
ostree-image-signed:docker://ghcr.io/lorduskordus/fedora-base-kde
```
##### KDE (NVIDIA)
```
ostree-image-signed:docker://ghcr.io/lorduskordus/fedora-base-kde-nvidia
```

## LK Images

- Personal, possibly breaking changes

##### COSMIC (NVIDIA)
```
ostree-image-signed:docker://ghcr.io/lorduskordus/fedora-lk-cosmic
```
##### KDE (NVIDIA)
```
ostree-image-signed:docker://ghcr.io/lorduskordus/fedora-lk-kde
```
