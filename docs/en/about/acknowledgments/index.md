---
title: "Acknowledments"
translated: true
---

From its start in 2003, we have benefited from many peoples and organizations.

### Project funding

SML# development was started as a part of the 5 year
project *e-Society leading project*: highly productive reliable software
development technologies (Project Director: Professor Takuya Katayama) 
under the title
``
reliable software development technology based on automatic program analysis
(chief investigator: Atsushi Ohori)
''
sponsored by the Japan ministry of science, education and technologies.

###  Third-party code and software tool used in SML# development

Since the version 1.0 had completed, SML# has been
developed by the SML# compiler itself.
Before that, we had used Standard ML of New Jersey for
development and MLTon compiler for building distributions.  

The SML# compiler is a software developed by the
SML# development team.
We have wrote most of the code of SML# compiler from
scratch, except for the following codes:

||
| contents | location in SML# distribution | source code |
| :--- | :--- | :--- |
| ML-Yacc | src/ml-yacc | Standard ML of New Jersey 110.73 |
| ML-Lex | src/ml-lex | Standard ML of New Jersey 110.73 |
| ML-Lpt | src/ml-lpt |	Standard ML of New Jersey 110.99 |
| SML/NJ Library | src/smlnj-lib | Standard ML of New Jersey 110.99 |
| TextIO, BinIO, OS, Date, Timer   | src/smlnj | Standard ML of New Jersey 110.73 |
| floating point-string conversion | src/runtime/netlib | the Netlib |

All of the above are open-source software that are compatible
with SML# license.
The SML# source distribution includes the license of each
of them at the ``location in SML# distribution'' show above.

### Collaborators

Many people have contributed to research and development of SML#.
The following people directly contributed to  SML# research.

* **Kiyoshi Yamatodani** for early stage of SML# compiler development and SML# programming tools: SMLFormat、SMLDoc、SMLUnit、and LMLML.

* **Satoshi Osaka** for development of [a new pattern maching algorithm based on a denotational semantics](https://www.jstage.jst.go.jp/article/jssst/24/2/24_2_2_113/_article/-char/ja/) and implementation.

* **Huu-Duc Nguyen** for [a compilation method of ML with tag-free natural data representation](https://dl.acm.org/doi/abs/10.1145/1140335.1140364) and implementation of the initial SML# backend.

* **Liu Bochao** for [module compilation](https://www.jstage.jst.go.jp/article/imt/5/1/5_1_58/_article/-char/ja)

* **Isao Sasano** for [lightweight fusion](https://dl.acm.org/doi/10.1145/1190215.1190241)

* **Toshiaki Otomo** for [non-moging GC](https://dl.acm.org/doi/abs/10.1145/2034773.2034802)

* **NEC Solutions Innovators Co. Ltd (NEC Software Tohoku）** for [a joint project of an ERP system development](https://dl.acm.org/doi/10.1145/2692915.2628164)

* **Tomohiro Sasaki** for natural join in SML# (reored in ([ML Family Workshop](https://sites.google.com/site/mlworkshoppe/workshops/ml2016))
and [partial dynamic records](https://drops.dagstuhl.de/opus/volltexte/2016/6112/)

* **Hisayuki Mima** for [finitary polymorphism and its appication to compiler optimization](https://dl.acm.org/doi/10.1145/3236776)

We have also benefited from many other researchers from 1989; compiling a comprehensive list is difficult and omitted.
