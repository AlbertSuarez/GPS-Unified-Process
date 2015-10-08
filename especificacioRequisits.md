# **SISTEMA ACME - ESPECIFICACIÓ DE REQUISITS DEL SOFTWARE** #

## **1. ESPECIFICACIÓ FUNCIONAL** ##

### 1.1. Diagrama de casos d'ús

> PER ARA CORRECTE, TOT I S'HA DE MILLORAR BASTANT.

![](https://bytebucket.org/AlbertSuarez/gps-up-23/raw/84c11875067262e2a5101efe8237bc91de268216/DiagramaCasosDus.png?token=3b536e9d5a53602e751c5dabc720f67c40e4073c)


> A més, per cada cas d'ús, una descripció d'una o dues línies (fins i tot si el nom és prou auto-explicatiu, pot no ser necessari)

* Cas d'ús UC001 - *nom*: descripció

* Cas d'ús UC002 - *nom*: descripció

* etc...

### 1.2. Descripció individual dels casos d'ús

> Un per un, es descriuen els casos d'ús introduïts a la subsecció 1.1. Com ja s'ha dit adalt, els casos d'ús s'aniran defining paulatinament

#### Cas d'ús UC001 - *nom* ####

> Descripció del primer cas d'ús. Si bé en una especificació "de veritat", escriuriem el curs rellevant d'esdeveniments, excepcions, etc., aquí ens conformem amb una descripció més "lleugera"

#### Cas d'ús UC002 - *nom* ####

> etc.


![](https://bytebucket.org/AlbertSuarez/gps-up-23/raw/762d14a0e45cc6cfe65f057f7544a69d03fc6d5c/mockups.png?token=85d9d82dfd09c732c56409ee3efb8afe551bb044)


## **2. ESPECIFICACIÓ NO FUNCIONAL** ##

**Requisits d’aparença**

*Tipus de requisit segons (Volere)*: 10 a

*Descripció*: Disseny atractiu i d’ús senzill que convidarà a l'usuari a fer-ne ús.

*Justificació del requisit*: Com l'aplicació treballa sobre un nombre de persones considerable com és tota Barcelona, cal destacar per l'atractiu de l'aplicació per tal de marcar un abans i un després en l'usuari.

*Condició de satisfacció*: El requisit se satisfarà si s'obté una bona valoració dels usuaris en respecte a l'apariencia.


**Requisits d’estil**

*Tipus de requisit segons (Volere)*: 10 b

*Descripció*: Disseny modern i ambiciós, seguint la tenència en disseny però destacant en punts específics.

*Justificació del requisit*: La competència del mercat ens obliga a disposar d’un disseny modern per tal destacar sobre els usuaris.

*Condició de satisfacció*: El requisit se satisfarà si més de tres quartes parts dels usuaris consideren un disseny modern.


**Requisits de facilitat d’ús**

*Tipus de requisit segons (Volere)*: 11 a

*Descripció*: El sistema ha de ser intuïtiu i fàcil d'usar. Complirà els criteris de temes de disseny, de contingut, d'estructura i de presentació fixats pel W3C.

*Justificació del requisit*: Un punt diferenciador important és que l'usuari pugui fer servir el sistema intuitivament, de manera que no perdi el temps intentant descobrir com funciona i, a més a més, que qualsevol persona sigui capaç de familiaritzar-se amb el sistema.

*Condició de satisfacció*: El requisit se satisfarà si un usuari amb poca experiència en aplicacions consegueix usar-lo sense cap problema.


**Requisits de latència i velocitat**

*Tipus de requisit segons (Volere)*: 12 a

*Descripció*: La resposta del sistema ha de ser de menys d'un segon com a mínim en el 95% de les operacions.

*Justificació del requisit*: Un temps de resposta ràpid permet que l’usuari no perdi el flux o atenció del que esta fent amb el sistema.

*Condició de satisfacció*: El requisit se satisfarà si donat un estudi sobre el rendiment de l'aplicació, aquest confirma que el temps d'espera en cada acció és menor al segon en el 95% dels casos.


**Requisits de precisió o exactitud**

*Tipus de requisit segons (Volere)*: 12 c

*Descripció*: Totes les dates que s’incloguin en l’aplicació tindran el format següent: DD/MM/AAAA

*Justificació del requisit*: És convenient especificar el format de la data ja que no a tot arreu té el mateix format i podria provocar malentesos entre els usuaris.

*Condició de satisfacció*: El requisit se satisfarà si el format de la data i l'hora segueix l’estandard ISO-8601 extens d’estil Europeu (EN 28601).


**Requisit de disponibilitat**

*Tipus de requisit segons (Volere)*: 12 d

*Descripció*: El sistema haurà d'estar disponible les 24 hores del dia durant els 365 dies que conformen l’any.

*Justificació del requisit*: Els usuaris han de poder utilitzar el sistema en qualsevol moment del dia per tal de poder buscar serveis o oferir-ne.

*Condició de satisfacció*: El requisit se satisfarà si el sistema està disponible i completament funcional tot el temps.


**Requisits d’adaptabilitat**

*Tipus de requisit segons (Volere)*: 14 c

*Descripció*: L’aplicació web ha de poder-se veure correctament en els diferents navegadors més utilitzats i en la majoria de smartphones, i tenir les mateixes funcions que ambdos.

*Justificació del requisit*: L'existència de diferents navegadors web i sistemes operatius en smartphones obliga a garantir que com a mínim es veurà de forma correcta.

*Condició de satisfacció*: El requisit se satisfarà si el sistema es pot visualitzar correctament en els principals navegadors web i smartphones.


**Requisit d’immunitat**

*Tipus de requisit*: 15 e

*Descripció*: El sistema està protegit d’atacs externs i infeccions per software maliciós.

*Justificació del requisit*: S’ha de garantir la seguretat per evitar posar en risc la disponibilitat del sistema i la privadesa de les dades dels usuaris.

*Condició del requisit*: El requisit se satisfarà si s'implementa la normativa de seguretat internacional ISO-17799 per tal de garantir la seguretat davant d'atacs externs.


**Requisits legals**

*Tipus de requisit segons (Volere)*: 17 a

*Descripció*: S’aconseguiran tots els drets sobre els serveis externs que s’utilitzin a l’aplicació i a la vegada es complirà les lleis sobre el tractament de dades personals.

*Justificació del requisit*: Es pactaran acords amb totes les empreses de les que s’utilitzen els seus serveix, arribant a acords sigui amb la Universitat per poder aprofitar la seva plataforma o amb empreses externes. I també mostrar transparència a l'hora de no compartir dades personals per fins no vinculants al sistema.

*Condició de satisfacció*: El requisit se satisfarà si no es rep cap denuncia per part de cap servei extern, ni de cap usuari per ús indegut de les dades personals.
