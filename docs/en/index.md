---
layout: toppage
translated: true
---

SML# is an open source functional programming language.
While maintaining compatibility with Standard ML,
it provides practically important features such as
interoperability with C and databases.
See "[About SML#](about/index.md)" for details.

{% highlight sml %}
val puts = _import "puts" : string -> int
val _ = app puts ["Hello", "World"]
{% endhighlight %}

Currently, we are working on migration to GitHub.
[Visit old SML# website in Tohoku University](https://www.pllab.riec.tohoku.ac.jp/smlsharp/)
