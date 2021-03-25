---
title: "Downloads"
translated: true
---

The SML# compiler and its relevant tools are open source software distributed
under a BSD-style license, named SML# license.
Please be sure to read the [SML# license](https://github.com/smlsharp/smlsharp/blob/master/LICENSE).

The latest version of SML# is 3.7.1.
See the [document](/en/documents/) page for details on how to set up SML#.
See the [Changes](https://github.com/smlsharp/smlsharp/blob/master/Changes) file for major changes in each release.

### Latest release

#### Source code

* [smlsharp-3.7.1.tar.gz](https://github.com/smlsharp/smlsharp/releases/download/v3.7.1/smlsharp-3.7.1.tar.gz) (Released on 15 May 2021)
  ```
  SHA256: 6dbe0c6c11b6636f9cf5696961782fd43490ea63265d6e19bf387764931f4449
  ```

#### Installing SML# from package systems

For popular operating systems equipped with package systems,
we are serving SML# private repositories, each of which offers source and binary packages of SML# for each operating system.
Once you install SML# through the package system, SML# is automatically updated
at the timing of system update.
How to set up SML# for each operating system is given below.
See the [document](/en/documents/) for details.

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
