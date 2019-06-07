---
layout: base
title:  'Statistics of parataxis in UD_Turkish-PUD'
udver: '2'
---

## Treebank Statistics: UD_Turkish-PUD: Relations: `parataxis`

This relation is universal.

74 nodes (0%) are attached to their parents as `parataxis`.

69 instances of `parataxis` (93%) are right-to-left (child precedes parent).
Average distance between parent and child is 11.7972972972973.

The following 19 pairs of parts of speech are connected with `parataxis`: <tt><a href="tr_pud-pos-VERB.html">VERB</a></tt>-<tt><a href="tr_pud-pos-VERB.html">VERB</a></tt> (22; 30% instances), <tt><a href="tr_pud-pos-NOUN.html">NOUN</a></tt>-<tt><a href="tr_pud-pos-VERB.html">VERB</a></tt> (15; 20% instances), <tt><a href="tr_pud-pos-VERB.html">VERB</a></tt>-<tt><a href="tr_pud-pos-NOUN.html">NOUN</a></tt> (7; 9% instances), <tt><a href="tr_pud-pos-NOUN.html">NOUN</a></tt>-<tt><a href="tr_pud-pos-ADJ.html">ADJ</a></tt> (4; 5% instances), <tt><a href="tr_pud-pos-ADJ.html">ADJ</a></tt>-<tt><a href="tr_pud-pos-VERB.html">VERB</a></tt> (3; 4% instances), <tt><a href="tr_pud-pos-NOUN.html">NOUN</a></tt>-<tt><a href="tr_pud-pos-NOUN.html">NOUN</a></tt> (3; 4% instances), <tt><a href="tr_pud-pos-PRON.html">PRON</a></tt>-<tt><a href="tr_pud-pos-VERB.html">VERB</a></tt> (3; 4% instances), <tt><a href="tr_pud-pos-VERB.html">VERB</a></tt>-<tt><a href="tr_pud-pos-ADJ.html">ADJ</a></tt> (3; 4% instances), <tt><a href="tr_pud-pos-AUX.html">AUX</a></tt>-<tt><a href="tr_pud-pos-VERB.html">VERB</a></tt> (2; 3% instances), <tt><a href="tr_pud-pos-NOUN.html">NOUN</a></tt>-<tt><a href="tr_pud-pos-AUX.html">AUX</a></tt> (2; 3% instances), <tt><a href="tr_pud-pos-PROPN.html">PROPN</a></tt>-<tt><a href="tr_pud-pos-VERB.html">VERB</a></tt> (2; 3% instances), <tt><a href="tr_pud-pos-ADJ.html">ADJ</a></tt>-<tt><a href="tr_pud-pos-ADJ.html">ADJ</a></tt> (1; 1% instances), <tt><a href="tr_pud-pos-ADJ.html">ADJ</a></tt>-<tt><a href="tr_pud-pos-NOUN.html">NOUN</a></tt> (1; 1% instances), <tt><a href="tr_pud-pos-ADP.html">ADP</a></tt>-<tt><a href="tr_pud-pos-VERB.html">VERB</a></tt> (1; 1% instances), <tt><a href="tr_pud-pos-AUX.html">AUX</a></tt>-<tt><a href="tr_pud-pos-ADJ.html">ADJ</a></tt> (1; 1% instances), <tt><a href="tr_pud-pos-AUX.html">AUX</a></tt>-<tt><a href="tr_pud-pos-AUX.html">AUX</a></tt> (1; 1% instances), <tt><a href="tr_pud-pos-NOUN.html">NOUN</a></tt>-<tt><a href="tr_pud-pos-PROPN.html">PROPN</a></tt> (1; 1% instances), <tt><a href="tr_pud-pos-PROPN.html">PROPN</a></tt>-<tt><a href="tr_pud-pos-NUM.html">NUM</a></tt> (1; 1% instances), <tt><a href="tr_pud-pos-VERB.html">VERB</a></tt>-<tt><a href="tr_pud-pos-PRON.html">PRON</a></tt> (1; 1% instances).


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 6 parataxis	color:blue
1	Ben	ben	PRON	PRP	Case=Nom|Number=Sing|Person=1|Polarity=Pos	6	nsubj	_	_
2	zaten	zaten	ADV	RB	_	6	advmod	_	_
3	her	her	DET	DT	Definite=Def|Number=Sing|Polarity=Pos	4	det	_	_
4	şekilde	şekil	NOUN	NN	Case=Loc|Number=Sing	6	obl	_	_
5	hapse	haps	NOUN	NN	Case=Dat|Number=Sing	6	obl	_	_
6	gireceğim	gir	VERB	VB	Aspect=Perf|Mood=Ind|Number=Sing|Person=1|Tense=Fut	8	parataxis	_	SpaceAfter=No
7	,	,	PUNCT	,	_	6	punct	_	_
8	umarım	um	VERB	VB	Number=Sing|Person=1|Tense=Aor	0	root	_	_
9	buna	bu	PRON	PRD	Case=Dat|Number=Sing|Polarity=Pos	10	nmod	_	_
10	değmiştir	değmiş	VERB	VB	Aspect=Perf|Evident=Nfh|Mood=Gen|Number=Sing|Person=3|Tense=Past	8	ccomp	_	SpaceAfter=No
11	.	.	PUNCT	.	_	8	punct	_	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 10 5 parataxis	color:blue
1	Birleşik	Birleşik	ADJ	JJ	Number=Sing	2	amod	_	Proper=True
2	Devletler	Devlet	NOUN	NN	Case=Nom|Number=Plur	5	nsubj	_	Proper=True|SpaceAfter=No
3	,	,	PUNCT	,	_	2	punct	_	_
4	Küba'yı	Küba	PROPN	PROPN	Case=Acc|Number=Sing	5	obj	_	Proper=True
5	özgürleştirdi	özgürleşt	VERB	VB	Aspect=Perf|Mood=Ind|Number=Sing|Person=3|Tense=Past|Voice=Cau	10	parataxis	_	_
6	(	(	PUNCT	(	_	10	punct	_	SpaceAfter=No
7	ABD	Abd	PROPN	PROPN	Number=Sing	8	compound	_	Proper=True
8	Ordusu'nun	Ordusu	NOUN	NN	Case=Gen|Number=Sing|Number[psor]=Sing|Person[psor]=3	9	nmod:poss	_	_
9	işgali	işgali	NOUN	NN	Number=Sing|Number[psor]=Sing|Person[psor]=3	10	compound	_	_
10	sonrasında	sonra	NOUN	NN	Case=Loc|Number=Sing|Number[psor]=Sing|Person[psor]=3	0	root	_	SpaceAfter=No
11	)	)	PUNCT	)	_	10	punct	_	SpaceAfter=No
12	.	.	PUNCT	.	_	10	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 13	bgColor:blue
# visual-style 13	fgColor:white
# visual-style 13 3 parataxis	color:blue
1	Zodyak	Zodyak	NOUN	NN	Number=Sing	2	compound	_	_
2	hayvanı	hayvan	NOUN	NN	Case=Nom|Number=Sing|Number[psor]=Sing|Person[psor]=3	3	nsubj	_	_
3	Maymun	_	NOUN	NN	Number=Sing	13	parataxis	_	SpaceAfter=No
4	'dur	_	AUX	AUX	Aspect=Perf|Mood=Gen|Number=Sing|Person=3|Tense=Pres	3	cop	_	_
5	ve	ve	CCONJ	CCONJ	_	13	cc	_	_
6	geleneksel	geleneksel	ADJ	JJ	Number=Sing	8	amod	_	_
7	önem	önem	NOUN	NN	Number=Sing	8	obj	_	_
8	taşıyan	taşı	AUX	VJ	Number=Sing|Polarity=Pos	10	acl	_	_
9	altmışıncı	altmışıncı	NUM	CD	Number=Sing|NumType=Ord	10	amod	_	_
10	yıldönümü	yıldön	NOUN	NN	Case=Nom|Number=Sing|Number[psor]=Sing|Person[psor]=3	13	nsubj	_	_
11	1992'ye	1992	NOUN	NN	Case=Dat|Number=Sing	13	obl	_	_
12	denk	denk	ADJ	JJ	_	13	amod	_	_
13	gelmiştir	gel	VERB	VB	Aspect=Perf|Evident=Nfh|Mood=Gen|Number=Sing|Person=3|Tense=Past	0	root	_	SpaceAfter=No
14	.	.	PUNCT	.	_	13	punct	_	_

~~~


