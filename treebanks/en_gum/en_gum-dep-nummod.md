---
layout: base
title:  'Statistics of nummod in UD_English-GUM'
udver: '2'
---

## Treebank Statistics: UD_English-GUM: Relations: `nummod`

This relation is universal.

780 nodes (1%) are attached to their parents as `nummod`.

670 instances of `nummod` (86%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.29102564102564.

The following 9 pairs of parts of speech are connected with `nummod`: <tt><a href="en_gum-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_gum-pos-NUM.html">NUM</a></tt> (678; 87% instances), <tt><a href="en_gum-pos-PROPN.html">PROPN</a></tt>-<tt><a href="en_gum-pos-NUM.html">NUM</a></tt> (52; 7% instances), <tt><a href="en_gum-pos-SYM.html">SYM</a></tt>-<tt><a href="en_gum-pos-NUM.html">NUM</a></tt> (30; 4% instances), <tt><a href="en_gum-pos-NUM.html">NUM</a></tt>-<tt><a href="en_gum-pos-NUM.html">NUM</a></tt> (9; 1% instances), <tt><a href="en_gum-pos-ADJ.html">ADJ</a></tt>-<tt><a href="en_gum-pos-NUM.html">NUM</a></tt> (5; 1% instances), <tt><a href="en_gum-pos-ADP.html">ADP</a></tt>-<tt><a href="en_gum-pos-NUM.html">NUM</a></tt> (2; 0% instances), <tt><a href="en_gum-pos-X.html">X</a></tt>-<tt><a href="en_gum-pos-NUM.html">NUM</a></tt> (2; 0% instances), <tt><a href="en_gum-pos-PART.html">PART</a></tt>-<tt><a href="en_gum-pos-NUM.html">NUM</a></tt> (1; 0% instances), <tt><a href="en_gum-pos-PRON.html">PRON</a></tt>-<tt><a href="en_gum-pos-NUM.html">NUM</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 2 nummod	color:blue
1	In	in	ADP	IN	_	3	case	_	_
2	fifteen	fifteen	NUM	CD	NumType=Card	3	nummod	_	_
3	minutes	minute	NOUN	NNS	Number=Plur	7	nmod	_	_
4	we	we	PRON	PRP	Case=Nom|Number=Plur|Person=1|PronType=Prs	7	nsubj	_	_
5	would	would	AUX	MD	VerbForm=Fin	7	aux	_	_
6	be	be	AUX	VB	VerbForm=Inf	7	cop	_	_
7	home	home	NOUN	NN	Number=Sing	0	root	_	_
8	and	and	CCONJ	CC	_	12	cc	_	_
9	my	my	PRON	PRP$	Number=Sing|Person=1|Poss=Yes|PronType=Prs	10	nmod:poss	_	_
10	mother	mother	NOUN	NN	Number=Sing	12	nsubj	_	_
11	would	would	AUX	MD	VerbForm=Fin	12	aux	_	_
12	fry	fry	VERB	VB	VerbForm=Inf	7	conj	_	_
13	eggs	egg	NOUN	NNS	Number=Plur	12	obj	_	SpaceAfter=No
14	.	.	PUNCT	.	_	7	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 3 nummod	color:blue
1	—	—	PUNCT	:	_	2	punct	_	_
2	NORTON	Norton	PROPN	NNP	Number=Sing	0	root	_	_
3	I	I	NUM	NNP	Number=Sing	2	nummod	_	SpaceAfter=No
4	,	,	PUNCT	,	_	5	punct	_	_
5	Emperor	Emperor	PROPN	NNP	Number=Sing	2	appos	_	_
6	of	of	ADP	IN	_	9	case	_	_
7	the	the	DET	DT	Definite=Def|PronType=Art	9	det	_	_
8	United	United	PROPN	NNP	Number=Sing	9	amod	_	_
9	States	States	PROPN	NNPS	Number=Plur	5	nmod	_	SpaceAfter=No
10	.	.	PUNCT	.	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 7 nummod	color:blue
1	Through	through	ADP	IN	_	2	case	_	_
2	them	them	PRON	PRP	Case=Acc|Number=Plur|Person=3|PronType=Prs	5	obl	_	_
3	it	it	PRON	PRP	Case=Nom|Gender=Neut|Number=Sing|Person=3|PronType=Prs	5	nsubj	_	_
4	may	may	AUX	MD	VerbForm=Fin	5	aux	_	_
5	cost	cost	VERB	VB	VerbForm=Inf	0	root	_	_
6	£	£	SYM	SYM	_	5	obj	_	_
7	20	@card@	NUM	CD	NumType=Card	6	nummod	_	_
8	in	in	ADP	IN	_	9	case	_	_
9	total	total	NOUN	NN	Number=Sing	5	obl	_	_
10	per	per	ADP	IN	_	11	case	_	_
11	person	person	NOUN	NN	Number=Sing	9	nmod	_	SpaceAfter=No
12	.	.	PUNCT	.	_	5	punct	_	_

~~~


