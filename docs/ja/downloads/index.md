---
title: "ダウンロード"
translated: true
---

SML#コンパイラおよびSML#用プログラム開発ツールは、MITライセンスの下で配布されているオープンソースソフトウェアです。
[ライセンスページ](../about/license/)および[LICENSE](https://github.com/smlsharp/smlsharp/blob/master/LICENSE)ファイルをお読みください。

SML#の最新版は4.0.0です。セットアップ方法については[ドキュメント](../documents/index.md)をご覧ください。リリースごとの主な変更点は[Changes](https://github.com/smlsharp/smlsharp/blob/master/Changes)ファイルをご覧ください。


### 最新のリリース

#### ソースコード

* [smlsharp-4.0.0.tar.gz](https://github.com/smlsharp/smlsharp/releases/download/v4.0.0/smlsharp-4.0.0.tar.gz)（2021年4月6日リリース）
  ```
  SIZE: 7397808
  SHA256: 0b44fb1f369f7cfced197c68f0d3102e940dbe5288adc3bdf618a5a3ec3165db
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

#### Windowsへのインストール

Windows Subsystem for Linux (WSL)を使用してUbuntuをセットアップし、Ubuntuのパッケージシステムでインストールしてください。

### 過去のリリース

最新のSML#をお使いください。最新版以外のSML#はメンテナンスされていません。

過去にリリースされたパッケージは[GitHubのリリースページ](https://github.com/smlsharp/smlsharp/releases)で確認・ダウンロードできます。

3.7.1以前のSML#は3条項BSDライセンスで配布されています。各リリースのライセンスについてはソースパッケージに含まれるLICENSEファイルをご覧ください。
