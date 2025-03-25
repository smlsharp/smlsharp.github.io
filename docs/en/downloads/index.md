---
title: "Downloads"
translated: true
---

The SML# compiler and its relevant tools are open source software distributed
under the MIT license copyrighted by the SML# development team.
(The [License page](../about/license/) and the [LICENSE](https://github.com/smlsharp/smlsharp/blob/master/LICENSE) file in the distribution.)

The latest version of SML# is 4.2.0.
See the [document](../documents/index.md) page for details on how to set up SML#.
See the [Changes](https://github.com/smlsharp/smlsharp/blob/master/Changes) file for major changes in each release.

### Latest release

#### Source code

* [smlsharp-4.2.0.tar.gz](https://github.com/smlsharp/smlsharp/releases/download/v4.2.0/smlsharp-4.2.0.tar.gz)（Released on 24 Mar 2025)
  ```
  SIZE: 14518864
  SHA256: 931fb54762c30ab018c804e669d696522cfabafe0a6f85cadefecee1eff710b7
  ```

#### Installing SML# from package systems

For popular operating systems equipped with package systems,
we are serving SML# private repositories, each of which offers source and binary packages of SML# for each operating system.
Once you install SML# through the package system, SML# is automatically updated
at the timing of system update.
How to set up SML# for each operating system is given below.
See the [document](../documents/index.md) for details.

* Debian sid
  ```
  wget -P /usr/share/keyrings https://github.com/smlsharp/repos/raw/main/debian/dists/sid/smlsharp-archive-keyring.gpg
  wget -P /etc/apt/sources.list.d https://github.com/smlsharp/repos/raw/main/debian/dists/sid/smlsharp.list
  apt update
  apt install smlsharp
  ```

* Debian 11 (bullseye)
  ```
  wget -P /usr/share/keyrings https://smlsharp.github.io/repos/debian/dists/bullseye/smlsharp-archive-keyring.gpg
  wget -P /etc/apt/sources.list.d https://smlsharp.github.io/repos/debian/dists/bullseye/smlsharp.list
  apt update
  apt install smlsharp
  ```
* Debian 12 (bookworm)
  ```
  wget -P /etc/apt/keyrings https://smlsharp.github.io/repos/debian/dists/bookworm/smlsharp-archive-keyring.gpg
  wget -P /etc/apt/sources.list.d https://smlsharp.github.io/repos/debian/dists/bookworm/smlsharp.sources
  apt update
  apt install smlsharp
  ```

* Ubuntu 22.04 LTS (jammy), 24.04 LTS (noble):
  ```
  apt-add-repository ppa:smlsharp/ppa
  apt update
  apt install smlsharp
  ```

* Fedora Rawhide
  ```
  rpm -i https://smlsharp.github.io/repos/fedora/smlsharp-release-fedora-41-1.noarch.rpm
  dnf install smlsharp smlsharp-smlformat smlsharp-smllex smlsharp-smlyacc
  ```

* AlmaLinux 8, AlmaLinux 9:
  ```
  rpm -i https://smlsharp.github.io/repos/almalinux/smlsharp-release-almalinux-8-1.noarch.rpm
  dnf install smlsharp smlsharp-smlformat smlsharp-smllex smlsharp-smlyacc
  ```

* Nix/NixOS
  ```
  nix run github:smlsharp/nixpkgs
  ```

* macOS (Homebrew)
  ```
  brew tap smlsharp/smlsharp
  brew install smlsharp
  ```

#### Installing SML# on Windows

Please set up Ubuntu by using Windows Subsystem for Linux (WSL) and
install SML# through Ubuntu's package system.

### Past releases

Please use the latest SML#.
Releases except for the latest one are not maintained.

Packages released in the past are still available from
[GitHub release](https://github.com/smlsharp/smlsharp/releases) page.

SML# 3.7.1 and prior are distributed under the 3-clause BSD license
copyrighted by Tohoku University. See LICENSE file in the source package
of each release for the license terms.
