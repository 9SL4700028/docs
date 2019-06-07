---
layout: base
title:  'Statistics of acl:cleft in UD_Swedish-LinES'
udver: '2'
---

## Treebank Statistics: UD_Swedish-LinES: Relations: `acl:cleft`

This relation is a language-specific subtype of <tt><a href="sv_lines-dep-acl.html">acl</a></tt>.
There are also 1 other language-specific subtypes of `acl`: <tt><a href="sv_lines-dep-acl-relcl.html">acl:relcl</a></tt>.

54 nodes (0%) are attached to their parents as `acl:cleft`.

52 instances of `acl:cleft` (96%) are left-to-right (parent precedes child).
Average distance between parent and child is 4.96296296296296.

The following 11 pairs of parts of speech are connected with `acl:cleft`: <tt><a href="sv_lines-pos-NOUN.html">NOUN</a></tt>-<tt><a href="sv_lines-pos-VERB.html">VERB</a></tt> (17; 31% instances), <tt><a href="sv_lines-pos-PRON.html">PRON</a></tt>-<tt><a href="sv_lines-pos-VERB.html">VERB</a></tt> (14; 26% instances), <tt><a href="sv_lines-pos-VERB.html">VERB</a></tt>-<tt><a href="sv_lines-pos-VERB.html">VERB</a></tt> (9; 17% instances), <tt><a href="sv_lines-pos-PROPN.html">PROPN</a></tt>-<tt><a href="sv_lines-pos-VERB.html">VERB</a></tt> (5; 9% instances), <tt><a href="sv_lines-pos-NOUN.html">NOUN</a></tt>-<tt><a href="sv_lines-pos-ADJ.html">ADJ</a></tt> (2; 4% instances), <tt><a href="sv_lines-pos-PRON.html">PRON</a></tt>-<tt><a href="sv_lines-pos-NOUN.html">NOUN</a></tt> (2; 4% instances), <tt><a href="sv_lines-pos-ADJ.html">ADJ</a></tt>-<tt><a href="sv_lines-pos-VERB.html">VERB</a></tt> (1; 2% instances), <tt><a href="sv_lines-pos-ADV.html">ADV</a></tt>-<tt><a href="sv_lines-pos-NOUN.html">NOUN</a></tt> (1; 2% instances), <tt><a href="sv_lines-pos-ADV.html">ADV</a></tt>-<tt><a href="sv_lines-pos-VERB.html">VERB</a></tt> (1; 2% instances), <tt><a href="sv_lines-pos-NOUN.html">NOUN</a></tt>-<tt><a href="sv_lines-pos-NOUN.html">NOUN</a></tt> (1; 2% instances), <tt><a href="sv_lines-pos-PRON.html">PRON</a></tt>-<tt><a href="sv_lines-pos-PROPN.html">PROPN</a></tt> (1; 2% instances).


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 6 acl:cleft	color:blue
1	Det	det	PRON	EX-P3SG	Definite=Def|Gender=Neut|Number=Sing|PronType=Prs	4	expl	_	_
2	var	vara	AUX	PAST-ACT	Mood=Ind|Tense=Past|VerbForm=Fin|Voice=Act	4	cop	_	_
3	en	en	DET	SG-IND	Definite=Ind|Gender=Com|Number=Sing|PronType=Art	4	det	_	_
4	kvinna	kvinna	NOUN	SG-IND-NOM	Case=Nom|Definite=Ind|Gender=Com|Number=Sing	0	root	_	_
5	som	som	PRON	REL	PronType=Rel	6	nsubj	_	_
6	öppnade	öppna	VERB	PAST-ACT	Mood=Ind|Tense=Past|VerbForm=Fin|Voice=Act	4	acl:cleft	_	_
7	dörren	dörr	NOUN	SG-DEF-NOM	Case=Nom|Definite=Def|Gender=Com|Number=Sing	6	obj	_	_
8	till	till	ADP	_	_	9	case	_	_
9	lägenheten	lägenhet	NOUN	SG-DEF-NOM	Case=Nom|Definite=Def|Gender=Com|Number=Sing	7	nmod	_	SpaceAfter=No
10	.	.	PUNCT	Period	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 6 acl:cleft	color:blue
1	Men	men	CCONJ	_	_	4	cc	_	_
2	det	det	PRON	EX-P3SG	Definite=Def|Gender=Neut|Number=Sing|PronType=Prs	4	expl	_	_
3	är	vara	AUX	PRES-ACT	Mood=Ind|Tense=Pres|VerbForm=Fin|Voice=Act	4	cop	_	_
4	det	det	PRON	PERS-P3SG	Definite=Def|Gender=Neut|Number=Sing|PronType=Prs	0	root	_	_
5	jag	jag	PRON	PERS-P1SG-NOM	Case=Nom|Definite=Def|Gender=Com|Number=Sing|PronType=Prs	6	nsubj	_	_
6	råkar	råka	VERB	PRES-ACT	Mood=Ind|Tense=Pres|VerbForm=Fin|Voice=Act	4	acl:cleft	_	_
7	vara	vara	VERB	INF-ACT	VerbForm=Inf|Voice=Act	6	xcomp	_	SpaceAfter=No
8	.	.	PUNCT	Period	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 6 acl:cleft	color:blue
1	Det	det	PRON	EX-P3SG	Definite=Def|Gender=Neut|Number=Sing|PronType=Prs	2	expl	_	_
2	var	vara	VERB	PAST-ACT	Mood=Ind|Tense=Past|VerbForm=Fin|Voice=Act	0	root	_	_
3	då	då	ADV	_	_	2	advmod	_	_
4	han	han	PRON	PERS-P3SG-NOM	Case=Nom|Definite=Def|Gender=Com|Number=Sing|PronType=Prs	6	nsubj	_	_
5	hade	ha	AUX	PAST-AUX	Mood=Ind|Tense=Past|VerbForm=Fin|Voice=Act	6	aux	_	_
6	tagit	ta	VERB	SUP-ACT	VerbForm=Sup|Voice=Act	2	acl:cleft	_	_
7	namnet	namn	NOUN	SG-DEF-NOM	Case=Nom|Definite=Def|Gender=Neut|Number=Sing	8	nmod	_	_
8	William	William	PROPN	SG-NOM	Case=Nom	6	obj	_	_
9	Wilson	Wilson	PROPN	SG-NOM	Case=Nom	8	flat	_	SpaceAfter=No
10	.	.	PUNCT	Period	_	2	punct	_	_

~~~


