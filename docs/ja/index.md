---
layout: toppage
translated: true
---

SML#はオープンソースの関数型プログラミング言語です。Standard MLと互換性を保ちながら、C言語やデータベースとの連携など実用上重要な機能を備えています。詳しくは「[SML#について](about/index.md)」をご覧ください。

```sml
val puts = _import "puts" : string -> int
fun f x = ignore (puts (#b x))
val _ = f {a = "Hi", b = "Hello"}
val _ = f {b = "World", c = "SML#"}
```

現在GitHubへの移行作業中です。[東北大学の旧SML# Webサイトを見る](https://www.pllab.riec.tohoku.ac.jp/smlsharp/ja/)
