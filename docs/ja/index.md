---
layout: toppage
translated: true
---

SML#はオープンソースの関数型プログラミング言語です。Standard MLと互換性を保ちながら、C言語やデータベースとの連携など実用上重要な機能を備えています。詳しくは「[SML#について](about/index.md)」をご覧ください。

{% highlight sml %}
val puts = _import "puts" : string -> int
val _ = app puts ["Hello", "World"]
{% endhighlight %}

現在GitHubへの移行作業中です。[東北大学の旧SML# Webサイトを見る](https://www.pllab.riec.tohoku.ac.jp/smlsharp/ja/)
