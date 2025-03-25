---
title: "ダウンロード"
translated: true
---

SML#コンパイラおよびSML#用プログラム開発ツールは、MITライセンスの下で配布されているオープンソースソフトウェアです。
[ライセンスページ](../about/license/)および[LICENSE](https://github.com/smlsharp/smlsharp/blob/master/LICENSE)ファイルをお読みください。

SML#の最新版は4.2.0です。セットアップ方法については[ドキュメント](../documents/index.md)をご覧ください。リリースごとの主な変更点は[Changes](https://github.com/smlsharp/smlsharp/blob/master/Changes)ファイルをご覧ください。


### 最新のリリース

#### ソースコード

* [smlsharp-4.2.0.tar.gz](https://github.com/smlsharp/smlsharp/releases/download/v4.2.0/smlsharp-4.2.0.tar.gz)（2025年3月24日リリース）
  ```
  SIZE: 14518864
  SHA256: 931fb54762c30ab018c804e669d696522cfabafe0a6f85cadefecee1eff710b7
  ```

#### パッケージシステムからインストール

各種OSのパッケージシステム向けに、バイナリパッケージとソースパッケージを提供するプライベートリポジトリを用意しています。一度インストールすると、パッケージシステムによりシステム更新の時点で自動的に更新されます。OSごとのインストール方法は以下の通りです。操作の詳細は[ドキュメント](../documents/index.md)をご覧ください。

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

* 22.04 LTS (jammy), 24.04 LTS (noble):
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

#### Windowsへのインストール

Windows Subsystem for Linux (WSL)を使用してUbuntuをセットアップし、Ubuntuのパッケージシステムでインストールしてください。

### 過去のリリース

最新のSML#をお使いください。最新版以外のSML#はメンテナンスされていません。

過去にリリースされたパッケージは[GitHubのリリースページ](https://github.com/smlsharp/smlsharp/releases)で確認・ダウンロードできます。

3.7.1以前のSML#は3条項BSDライセンスで配布されています。各リリースのライセンスについてはソースパッケージに含まれるLICENSEファイルをご覧ください。
