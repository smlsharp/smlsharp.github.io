---
layout: toppage
translated: true
---

SML# is an open source functional programming language.
While maintaining compatibility with Standard ML,
it provides practically important features such as
interoperability with C and databases.
See "[About SML#](about/index.md)" for details.

```sml
val puts = _import "puts" : string -> int
fun f x = ignore (puts (#b x))
val _ = f {a = "Hi", b = "Hello"}
val _ = f {b = "World", c = "SML#"}
```
