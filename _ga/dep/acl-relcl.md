---
layout: relation
title:  'acl:relcl'
shortdef : 'relative clause modifier'
udver: '2'
---

A relative clause modifier marks the relation between a relative clause and a noun phrase in a preceding clause.  The head of the relative clause is usually a verb. 

### Example

_Chaill sé pé rud a <b>bhí</b> aige_ `He lost everything that he <b>had</b>'

~~~ sdparse
Chaill sé pé rud a bhí aige \n Lost he whatever thing that had he
acl:relcl(pé,bhí)
nmod(pé, rud)
~~~ 

_Cheannaigh sé leabhar áit a <b>bhí</b> sé ar fáil_ 'He bought a book wherever it <b>was</b> available' 

~~~ sdparse
Cheannaigh sé leabhar áit a bhí sé ar fáil \n Bought he book place was available
acl:relcl(áit, bhí)
~~~

_Faigh tuilleadh eolais faoin taisteal a <b>rinne</b> Naomh Pádraig in Éirinn_ 'Find out more information about the journies <b>made</b> by Saint Patrick in Ireland'
  
~~~ sdparse
Faigh tuilleadh eolais faoin taisteal a rinne Naomh Pádraig in Éirin \n Find more information about journies made St. Patrick in Ireland
acl:relcl(taisteal, rinne)
~~~

_Usáideadh dílseacht don Eaglais Bhunaithe mar ghléas le leatrom a dhéanamh ar Chaitlicigh agus le daoine áirithe a iompú in aghaidh na hEaglaise inar <b>rugadh</b> iad_  'Loyalty to the Established Church was definitely used as a way of discriminating against Catholics and turning some people against the Church they were <b>born</b> into' 

~~~ sdparse
Usáideadh dílseacht don Eaglais Bhunaithe mar ghléas le leatrom a dhéanamh ar Chaitlicigh agus le daoine áirithe a iompú in aghaidh na hEaglaise inar rugadh iad \n Used loyalty for the Church Established as instrument with discriminating to do on Catholics agus with people certain turn against the Church in which born they
acl:relcl(hEaglaise, rugadh)
~~~
