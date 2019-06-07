---
layout: base
title:  'Statistics of nsubj:pass in UD_German-HDT'
udver: '2'
---

## Treebank Statistics: UD_German-HDT: Relations: `nsubj:pass`

This relation is a language-specific subtype of <tt><a href="de_hdt-dep-nsubj.html">nsubj</a></tt>.

5219 nodes (1%) are attached to their parents as `nsubj:pass`.

5007 instances of `nsubj:pass` (96%) are right-to-left (child precedes parent).
Average distance between parent and child is 6.42402759149262.

The following 6 pairs of parts of speech are connected with `nsubj:pass`: <tt><a href="de_hdt-pos-VERB.html">VERB</a></tt>-<tt><a href="de_hdt-pos-NOUN.html">NOUN</a></tt> (3898; 75% instances), <tt><a href="de_hdt-pos-VERB.html">VERB</a></tt>-<tt><a href="de_hdt-pos-PRON.html">PRON</a></tt> (907; 17% instances), <tt><a href="de_hdt-pos-VERB.html">VERB</a></tt>-<tt><a href="de_hdt-pos-PROPN.html">PROPN</a></tt> (283; 5% instances), <tt><a href="de_hdt-pos-VERB.html">VERB</a></tt>-<tt><a href="de_hdt-pos-X.html">X</a></tt> (98; 2% instances), <tt><a href="de_hdt-pos-VERB.html">VERB</a></tt>-<tt><a href="de_hdt-pos-NUM.html">NUM</a></tt> (25; 0% instances), <tt><a href="de_hdt-pos-VERB.html">VERB</a></tt>-<tt><a href="de_hdt-pos-ADJ.html">ADJ</a></tt> (8; 0% instances).


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 2 nsubj:pass	color:blue
1	Alte	alt	ADJ	ADJA	Degree=Pos|Number=Plur	2	amod	_	_
2	EMails	EMails	NOUN	NN	Case=Nom|Person=3	7	nsubj:pass	_	_
3	wurden	werden	AUX	VAFIN	Mood=Ind|Number=Plur|Person=3|Tense=Past	7	aux:pass	_	_
4	nicht	nicht	PART	PTKNEG	_	7	advmod	_	_
5	vom	vom	ADP	APPRART	Case=Dat	6	case	_	_
6	Server	Server	NOUN	NN	Case=Dat|Gender=Masc|Number=Sing|Person=3	7	obl	_	_
7	gelöscht	löschen	VERB	VVPP	_	0	root	_	_
8	.	.	PUNCT	$.	_	7	punct	_	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 2 nsubj:pass	color:blue
1	Ob	Ob	SCONJ	KOUS	_	5	mark	_	_
2	dieser	dieser	PRON	PDS	Case=Nom|Gender=Masc|Number=Sing|Person=3	5	nsubj:pass	_	_
3	absichtlich	absichtlich	ADJ	ADJD	Degree=Pos	5	advmod	_	_
4	offen	offen	ADJ	ADJD	Degree=Pos	5	xcomp	_	_
5	gelassen	lassen	VERB	VVPP	_	10	csubj	_	_
6	wurde	werden	AUX	VAFIN	Mood=Ind|Number=Sing|Person=3|Tense=Past	5	aux:pass	_	_
7	,	,	PUNCT	$,	_	5	punct	_	_
8	ist	sein	AUX	VAFIN	Mood=Ind|Number=Sing|Person=3|Tense=Pres	10	cop	_	_
9	dabei	dabei	ADV	PROAV	_	10	advmod	_	_
10	egal	egal	ADJ	ADJD	Degree=Pos	0	root	_	_
11	.	.	PUNCT	$.	_	10	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 3 nsubj:pass	color:blue
1	Nun	Nun	ADV	ADV	_	9	advmod	_	_
2	ist	sein	AUX	VAFIN	Mood=Ind|Number=Sing|Person=3|Tense=Pres	9	aux:pass	_	_
3	Felix	Felix	PROPN	NE	Case=Nom|Number=Sing|Person=3	9	nsubj:pass	_	_
4	Somm	Somm	PROPN	NE	Person=3	3	flat:name	_	_
5	in	in	ADP	APPR	Case=Acc	8	case	_	_
6	eine	eine	DET	ART	Case=Acc|Gender=Fem|Number=Sing	8	det	_	_
7	prekäre	prekär	ADJ	ADJA	Degree=Pos|Gender=Fem|Number=Sing	8	amod	_	_
8	Situation	Situation	NOUN	NN	Case=Acc|Gender=Fem|Number=Sing|Person=3	9	obl:arg	_	_
9	geraten	geraten	VERB	VVPP	_	0	root	_	_
10	.	.	PUNCT	$.	_	9	punct	_	_

~~~


