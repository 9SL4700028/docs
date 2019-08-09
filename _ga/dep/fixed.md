---
layout: relation
title: 'fixed'
shortdef: 'multi-word expression'
udver: '2'
---

The `fixed` multi-word expression relation is one of the relations for compounding and it is intended mostly for function words.
The first token is the head of a fixed unit - with right branching attachments from the head to each element of the MWE.

Note that in Irish, `flat` and `flat-name` are used for nominal compounds - organisations, people etc. Regular noun compounds are labelled `compound`.
`compound:prt` is used for particle verbs e.g. 'éirí as'

The other multiword units in Irish that are labelled as fixed are as follows:

### Compound Prepositions
The first element of the compound preposition (POS tag usually ADP) is the head.

_Is <b>de bharr</b> a chontúirt don neodracht_ '<b>As a result of</b> the danger it poses to neutrality'

~~~ sdparse
Is de bharr a chontúirt don neodracht \n is as a result of its risk to nature
fixed(de,bharr)
~~~

_Ná bíodh cumha <b>ar bith</b> ort_ 'Don't be upset <b>at all</b>'

~~~ sdparse
Ná bíodh cumha ar bith ort \n Not be regret on world on_you
fixed(ar, bith)
~~~

_Tá dhá phort eile a bhailíodar seasca bliain <b>ó shin</b>_ 'There are two other tunes that were collected sixty years <b>ago</b>'

~~~ sdparse
Tá dhá phort eile a bhailíodar seasca bliain ó shin \n Is two tune other that they collected sixty year from then
fixed(ó, shin)
~~~

_Níor chorraigh <b>a thuilleadh</b> linn an tosta_ 'He didn't stir <b>any more</b> for the rest of the silence'

~~~ sdparse
Níor chorraigh a thuilleadh linn an tosta \n Did not move its more with_us of_the silence
fixed(a, thuilleadh)
~~~
