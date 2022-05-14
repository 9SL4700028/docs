---
layout: relation
title:  'dep'
shortdef : 'dependent'
udver: '2'
---

A dependency is labeled as `dep` when a system is unable to determine
a more precise dependency relation between two words.  This may be
because of a weird grammatical construction, a limitation in the
Stanford Dependency conversion software, a parser error, or because of
an unresolved long distance dependency.

~~~ sdparse
Then , as if to show that he could , ...
dep(show, if)
~~~
<!-- Interlanguage links updated So kvě 14 19:03:24 CEST 2022 -->
