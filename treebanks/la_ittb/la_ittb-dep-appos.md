---
layout: base
title:  'Statistics of appos in UD_Latin-ITTB'
udver: '2'
---

## Treebank Statistics: UD_Latin-ITTB: Relations: `appos`

This relation is universal.

150 nodes (0%) are attached to their parents as `appos`.

150 instances of `appos` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 3.12666666666667.

The following 14 pairs of parts of speech are connected with `appos`: <tt><a href="la_ittb-pos-NOUN.html">NOUN</a></tt>-<tt><a href="la_ittb-pos-NOUN.html">NOUN</a></tt> (98; 65% instances), <tt><a href="la_ittb-pos-DET.html">DET</a></tt>-<tt><a href="la_ittb-pos-NOUN.html">NOUN</a></tt> (11; 7% instances), <tt><a href="la_ittb-pos-PROPN.html">PROPN</a></tt>-<tt><a href="la_ittb-pos-NOUN.html">NOUN</a></tt> (11; 7% instances), <tt><a href="la_ittb-pos-PRON.html">PRON</a></tt>-<tt><a href="la_ittb-pos-NOUN.html">NOUN</a></tt> (8; 5% instances), <tt><a href="la_ittb-pos-NOUN.html">NOUN</a></tt>-<tt><a href="la_ittb-pos-DET.html">DET</a></tt> (6; 4% instances), <tt><a href="la_ittb-pos-NOUN.html">NOUN</a></tt>-<tt><a href="la_ittb-pos-PROPN.html">PROPN</a></tt> (5; 3% instances), <tt><a href="la_ittb-pos-NOUN.html">NOUN</a></tt>-<tt><a href="la_ittb-pos-PRON.html">PRON</a></tt> (3; 2% instances), <tt><a href="la_ittb-pos-PRON.html">PRON</a></tt>-<tt><a href="la_ittb-pos-PROPN.html">PROPN</a></tt> (2; 1% instances), <tt><a href="la_ittb-pos-DET.html">DET</a></tt>-<tt><a href="la_ittb-pos-ADJ.html">ADJ</a></tt> (1; 1% instances), <tt><a href="la_ittb-pos-NOUN.html">NOUN</a></tt>-<tt><a href="la_ittb-pos-ADJ.html">ADJ</a></tt> (1; 1% instances), <tt><a href="la_ittb-pos-PRON.html">PRON</a></tt>-<tt><a href="la_ittb-pos-ADJ.html">ADJ</a></tt> (1; 1% instances), <tt><a href="la_ittb-pos-PROPN.html">PROPN</a></tt>-<tt><a href="la_ittb-pos-ADJ.html">ADJ</a></tt> (1; 1% instances), <tt><a href="la_ittb-pos-PROPN.html">PROPN</a></tt>-<tt><a href="la_ittb-pos-DET.html">DET</a></tt> (1; 1% instances), <tt><a href="la_ittb-pos-PROPN.html">PROPN</a></tt>-<tt><a href="la_ittb-pos-PROPN.html">PROPN</a></tt> (1; 1% instances).


~~~ conllu
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 10 appos	color:blue
1	uirtute	uirtus	NOUN	C1|grn1|casF|gen2|vgr1	Case=Abl|Gender=Fem|InflClass=IndEurX|Number=Sing	5	obl	_	_
2	enim	enim	PART	O4	_	5	discourse	_	_
3	dei	deus	PROPN	F1|grn1|casB|gen1	Case=Gen|Gender=Masc|InflClass=IndEurO|Number=Sing	1	nmod	_	_
4	utrumque	uterque	DET	F1|grn1|casA|gen3|comH|vgr2	Case=Nom|Gender=Neut|InflClass=LatPron|Number=Sing|PronType=Con	5	nsubj	_	_
5	fit	facio	VERB	N3|modJ|tem1|gen6	Aspect=Imp|InflClass=LatI2|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Pass	0	root	_	SpaceAfter=No|TraditionalMood=Indicativus|TraditionalTense=Praesens
6	,	,	PUNCT	Punc	_	8	punct	_	_
7	et	et	CCONJ	O4	_	8	mark	_	_
8	corpus	corpus	NOUN	C1|grn1|casA|gen3	Case=Nom|Gender=Neut|InflClass=IndEurX|Number=Sing	5	dislocated:nsubj	_	_
9	et	et	CCONJ	O4	_	7	fixed	_	_
10	anima	anima	NOUN	F1|grn1|casA|gen2	Case=Nom|Gender=Fem|InflClass=IndEurA|Number=Sing	8	appos	_	SpaceAfter=No
11	:	:	PUNCT	Punc	_	5	punct	_	_

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 7 appos	color:blue
1	utroque	uterque	DET	F1|grn1|casF|gen3|comH	Case=Abl|Gender=Neut|InflClass=LatPron|Number=Sing|PronType=Con	4	obl	_	_
2	enim	enim	PART	O4	_	4	discourse	_	_
3	agens	agens	NOUN	C1|grn1|casA|gen3	Case=Nom|Gender=Neut|InflClass=IndEurI|Number=Sing	4	nsubj	_	_
4	agit	ago	VERB	L3|modA|tem1|gen6	Aspect=Imp|InflClass=LatX|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	SpaceAfter=No|TraditionalMood=Indicativus|TraditionalTense=Praesens
5	,	,	PUNCT	Punc	_	7	punct	_	_
6	et	et	CCONJ	O4	_	7	mark	_	_
7	uirtute	uirtus	NOUN	C1|grn1|casF|gen2|vgr1	Case=Abl|Gender=Fem|InflClass=IndEurX|Number=Sing	1	appos	_	_
8	et	et	CCONJ	O4	_	9	cc	_	_
9	instrumento	instrumentum	NOUN	B1|grn1|casF|gen3	Case=Abl|Gender=Neut|InflClass=IndEurO|Number=Sing	7	conj	_	SpaceAfter=No
10	.	.	PUNCT	Punc	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 4 appos	color:blue
1	de	de	ADP	S4	_	2	case	_	_
2	deo	deus	PROPN	F1|grn1|casF|gen1	Case=Abl|Gender=Masc|InflClass=IndEurO|Number=Sing	10	obl	_	_
3	autem	autem	PART	O4	_	10	discourse	_	_
4	patre	pater	NOUN	C1|grn1|casF|gen1	Case=Abl|Gender=Masc|InflClass=IndEurX|Number=Sing	2	appos	_	_
5	et	et	CCONJ	O4	_	7	cc	_	_
6	de	de	ADP	S4	_	7	case	_	_
7	deo	deus	PROPN	F1|grn1|casF|gen1	Case=Abl|Gender=Masc|InflClass=IndEurO|Number=Sing	2	conj	_	_
8	filio	filius	NOUN	B1|grn1|casF|gen1	Case=Abl|Gender=Masc|InflClass=IndEurO|Number=Sing	7	flat	_	_
9	opposita	oppono	VERB	L2|modM|tem4|grp1|casJ|gen3	Aspect=Perf|Case=Nom|Gender=Neut|InflClass=LatX|InflClass[nominal]=IndEurO|Number=Plur|VerbForm=Part|Voice=Pass	10	csubj:pass	_	TraditionalMood=Participium|TraditionalTense=Perfectum
10	praedicantur	praedico	VERB	J3|modJ|tem1|gen9|vgr1	Aspect=Imp|InflClass=LatA|Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin|Voice=Pass	0	root	_	SpaceAfter=No|TraditionalMood=Indicativus|TraditionalTense=Praesens
11	:	:	PUNCT	Punc	_	10	punct	_	_

~~~


