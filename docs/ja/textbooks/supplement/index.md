---
title: "「SML#で始める実践MLプログラミング」補足説明"
---
## 第9章 データベースとの連携

この章は、SML#の特徴的な機能であるSQLとの統合を活用したデータベースプログラミングの解説です。
本教科書で学ぶプログラムの中でも、その構造が最も複雑なものと言えます。プログラミングの疑問点
などがあればお送りください。一般的なものについては、ここにヒントや注意などを掲載予定です。

### 9.10.1 データソースの特定とデータのインポート

* 本教科書執筆時点の covid19の累積感染者データファイルを本書のサポートレポジトリ
にファイル
[covid19japan-all.json](https://github.com/smlsharp/mlpractice-book/blob/master/covid19japan-all.json)
として公開しています。```corona.go.jp```サイトが任務を終えて閉鎖された場合は、
p.168の上部のコードブロックの最後の宣言を以下のように変更して使用してください。
```
val 累積陽性者Url = 
    "https://github.com/smlsharp/mlpractice-book/raw/refs/heads/master/covid19japan-all.json"
```
このファイルのソースと配布条件は、
[covid19japanjson-allNotice.txt](https://github.com/smlsharp/mlpractice-book/blob/master/covid19japanjson-allNotice.txt)
に記されています。
