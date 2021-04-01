---
title: "開発・コミュニティ"
translated: true
---

### SML#開発チーム

SML#の開発はSML#開発チームを中心として進められています。現在のSML#開発チームのメンバーは五十音順で以下の通りです。

* 上野 雄大（東北大学電気通信研究所）
* 大堀 淳（東北大学電気通信研究所）

### コミュニティ

SML#について情報交換や議論ができるフォーラムがあります。お気軽にどうぞ。参加にはGitHubアカウントが必要です。

* [smlsharp/forum/discussions](https://github.com/smlsharp/forum/discussions)（英語）
* [smlsharp/forum_ja/discussions](https://github.com/smlsharp/forum_ja/discussions)（日本語）

SML#の公式Twitterアカウントは[@smlsharp](https://twitter.com/smlsharp)です。このアカウントではSML#に関すること（主に新しいリリースなど）をツイートします。SML#ユーザーはぜひフォローしてください。SML#開発チームに直接コンタクトを取りたい場合はこちらにメンションやDMを送ってください。

### リポジトリガイド

SML#のソースコードはバージョン管理システム[git](https://git-scm.org)で管理されています。開発中のソースコードは[GitHub](https://github.com)上のリポジトリにあります。開発中のソースコードを取得するには以下のコマンドを実行してください。

```
git clone https://github.com/smlsharp/smlsharp.git
```

ソースコードだけでなくドキュメントやWebサイトなどの各種リソースもGitHubで管理されています。SML#開発チームが管理・運営しているリポジトリは以下の通りです。

* [smlsharp/smlsharp](https://github.com/smlsharp/smlsharp): SML#コンパイラおよび周辺ツール本体
* [smlsharp/smlsharp-document](https://github.com/smlsharp/smlsharp-document): SML#ドキュメント
* [smlsharp/smlsharp-package](https://github.com/smlsharp/smlsharp-package): 各種OS向けパッケージを作るためのスクリプト集
* [smlsharp/homebrew-smlsharp](https://github.com/smlsharp/homebrew-smlsharp): SML#のHomebrew formula
* [smlsharp/repos](https://github.com/smlsharp/repos): バイナリパッケージを集積するリポジトリ
* [smlsharp/smlsharp.github.io](https://github.com/smlsharp/smlsharp.github.io): このWebサイトのソース
* [smlsharp/forum](https://github.com/smlsharp/forum), [smlsharp/forum_ja](https://github.com/smlsharp/forum): フォーラムを運用するためのリポジトリ

[smlsharp/smlsharp](https://github.com/smlsharp/smlsharp)が、SML#プロジェクトが開発するコンパイラ、ツール、ライブラリの開発最前線であり、一次配布元です。

### 問題点のレポート

SML#コンパイラや周辺ツールのバグ、ドキュメントの誤りなどの問題点を見つけたら、GitHubのIssues機能を使ってお知らせください。報告の際は適切なリポジトリを選んでください（例えば、SML#コンパイラの問題点は[smlsharp/smlsharp](https://github.com/smlsharp/smlsharp/issues)に、マニュアルの問題点は[smlsharp/smlsharp-document](https://github.com/smlsharp/smlsharp-document/issues)に投稿してください）。

修正すべき事項かどうか判断できない場合は、一旦フォーラムで質問してください。

### コードの提供

SML#プロジェクトへのコードの提供はいつでも歓迎しています。コードの提供はGitHubのPull request機能を使ってお知らせください。SML#開発チームでレビューした上で採否を決定します。プルリクエストを送る際は以下の点にご同意ください。

* プルリクエストがマージされると、あなたが送った内容には[SML#と同じライセンス](https://github.com/smlsharp/smlsharp/blob/master/LICENSE)が適用されます。これは、あなたの貢献がSML#プロジェクトへの努力的な寄付になることを意味します。

誤字の修正など明らかな修正・改善は、プルリクエストを直接送っていただいて構いません。疑問がある場合や、大きな機能改善や機能追加の場合は、事前にフォーラムやIssuesで相談してください。

### 関連リポジトリ

以下のリポジトリは、コンポーネントごとにSML#プロジェクトからフォークし、コミュニティによってメンテナンスされています。SML#以外のStandard ML処理系（SML/NJ、MLton、Poly/MLなど）への対応などが行われています。

* [smlsharp/SMLUnit](https://github.com/smlsharp/SMLUnit)
* [smlsharp/SMLFormat](https://github.com/smlsharp/SMLFormat)
* [smlsharp/LMLML](https://github.com/smlsharp/LMLML)

これらの3つのリポジトリについては、SML#開発チームと協力関係にありますが、SML#開発チームの管理下にありません。問題追跡や貢献の方法は各リポジトリをご参照ください。
