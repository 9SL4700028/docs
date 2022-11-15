---
layout: relation
title: 'cop'
shortdef: 'cop'
udver: '2'
---

A `cop` (copula) is the relation of a function word used to link a subject to a nonverbal predicate. Although some languages also classify other function words as copulas, the Slovene treebanks use the `cop` relation only for the linking verb _biti_ '_to be_' in combination with a nominal or adjectival subject complement. The head of the relation is the complement, and the dependent is the linking verb _biti_.

~~~ sdparse
Začetek izvajanja programa je/AUX odvisen od podpisa sporazuma
cop(odvisen,je)
nsubj(odvisen,Začetek)
~~~
~~~ sdparse
Rečna jezera mrtvice so/AUX stalni spremljevalci Mure 
cop(spremljevalci,so)
nsubj(spremljevalci,jezera)
~~~
~~~ sdparse
Da , jaz sem/AUX tisti , ki bi moral biti tukaj
cop(tisti,sem)
nsubj(tisti,jaz)
~~~

If the sentence also contains other forms of the verb _biti_, the copula (`cop`) relation is applied to the non-finite verb form (the -l participle), whereas the finite verb form is analyzed as an auxiliary ([aux]()). Both relations attach to the head of the subject complement.

~~~ sdparse
Niti prijatelja nista/AUX več bila/AUX
cop(prijatelja,bila)
aux(prijatelja,nista)
~~~

Slovenian treebanks do not make any distinction between participial adjectives (always labelled as [ADJ]()) in different syntactic roles. Thus, there is no distinction between participles acting as subject complements (e.g., _kajenje je prepovedano_ 'smoking is prohibited') and participles used in passive constructions (e.g., _kajenje ji je bilo prepovedano_ 'smoking was prohibited to her'). 

~~~ sdparse
kajenje je/AUX prepovedano
cop(prepovedano,je)
nsubj(prepovedano,kajenje)
~~~
~~~ sdparse
kajenje ji je/AUX bilo/AUX prepovedano
cop(prepovedano,bilo)
aux(prepovedano,je)
nsubj(prepovedano,kajenje)
~~~

As a legacy of the JOS annotation system, predicative constructions with prepositional phrases (e.g. _biti v formi_ 'to be in shape') or adverbs (e.g. _to ni prav_ 'this is not correct') are currently not analyzed as copula constructions, as priority is given to form over [semantics](https://universaldependencies.org/v2/copula.html#guidelines-for-udv2) of _biti_. Therefore, both _biti v formi_ 'to be in shape' and _biti v sobi_ 'to be in a room' are analyzed in the same way, with _biti_ 'to be' tagged as [VERB]() and treated as the head of the dependent prepositional phrase ([obl]()). 
<!-- Interlanguage links updated Po lis 14 15:35:18 CET 2022 -->
