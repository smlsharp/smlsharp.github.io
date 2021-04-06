---
title: "Downloads"
translated: true
---

The SML# compiler and its relevant tools are open source software distributed
under the MIT license copyrighted by the SML# development team.
(The [License page](../about/license/) and the [LICENSE](https://github.com/smlsharp/smlsharp/blob/master/LICENSE) file in the distribution.)

The latest version of SML# is 4.0.0.
See the [document](../documents/index.md) page for details on how to set up SML#.
See the [Changes](https://github.com/smlsharp/smlsharp/blob/master/Changes) file for major changes in each release.

### Latest release

#### Source code

* [smlsharp-4.0.0.tar.gz](https://github.com/smlsharp/smlsharp/releases/download/v4.0.0/smlsharp-4.0.0.tar.gz)（Released on 6 Apr 2021)
  ```
  SIZE: 7397808
  SHA256: 0b44fb1f369f7cfced197c68f0d3102e940dbe5288adc3bdf618a5a3ec3165db
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

* Debian 10 (buster)
  ```
  wget -P /usr/share/keyrings https://github.com/smlsharp/repos/raw/main/debian/dists/buster/smlsharp-archive-keyring.gpg
  wget -P /etc/apt/sources.list.d https://github.com/smlsharp/repos/raw/main/debian/dists/buster/smlsharp.list
  apt update
  apt install smlsharp
  ```

* Ubuntu
  ```
  apt-add-repository ppa:smlsharp/ppa
  apt update
  apt install smlsharp
  ```

* Fedora Rawhide
  ```
  rpm -i https://github.com/smlsharp/repos/raw/main/fedora/smlsharp-release-rawhide-31-1.noarch.rpm
  dnf install smlsharp smlsharp-smlformat smlsharp-smllex smlsharp-smlyacc
  ```

* Fedora
  ```
  rpm -i https://github.com/smlsharp/repos/raw/main/fedora/smlsharp-release-fedora-31-1.noarch.rpm
  dnf install smlsharp smlsharp-smlformat smlsharp-smllex smlsharp-smlyacc
  ```

* CentOS 8
  ```
  rpm -i https://github.com/smlsharp/repos/raw/main/centos/smlsharp-release-centos-8-1.noarch.rpm
  dnf install smlsharp smlsharp-smlformat smlsharp-smllex smlsharp-smlyacc
  ```

* CentOS 7
  ```
  yum install epel-release
  rpm -i https://github.com/smlsharp/repos/raw/main/centos/smlsharp-release-centos-7-1.noarch.rpm
  yum install smlsharp smlsharp-smlformat smlsharp-smllex smlsharp-smlyacc
  ```

* macOS 11 Big Sur (Homebrew)
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
