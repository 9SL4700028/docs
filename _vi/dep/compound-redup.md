---
layout: relation
title: 'compound:pron'
shortdef: 'reduplicated compound'
udver: '2'
---

The compound:redup relation is used for reduplicated compounds. 
There is a reduplication when a token is followed by one or several occurences of the same token. 


~~~ sdparse
Cô ấy thích màu đo đỏ 。
obj(thích, màu)
compound:redup(đo, đỏ)
nmod(màu, đo)
compound:pron(Cô, ấy)
nsubj(thích, Cô)
punct(đẹp, 。)
~~~

<!-- Interlanguage links updated Po lis 14 15:35:16 CET 2022 -->
