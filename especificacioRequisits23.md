# **SISTEMA ACME - ESPECIFICACIÓ DE REQUISITS DEL SOFTWARE** #

## **1. ESPECIFICACIÓ FUNCIONAL** ##

### 1.1. Diagrama de casos d'ús




![Diagrama de casos d’us](https://bytebucket.org/AlbertSuarez/gps-up-23/raw/86006fbc5ee3334957c81dd868848f366191a5dd/Imatges/DiagramaCasosDus.png?token=fc5bcf4cf5b44f79c8752bc2f506fdd939689a0e)

### 1.2. Descripció individual dels casos d'ús

#### Cas d'ús UC001 - *Esborrar Usuari* ####

L'administrador pot esborrar un usuari del sistema si detecta algun error en el compte, activitats il·legals, incompliments de les regles de la comunitat, etc.

#### Cas d'ús UC002 - *Registrar-se* ####

Un usuari pot crear un compte d'usuari per tal de formar part de la comunitat i, llavors registrar-lo en el sistema.

#### Cas d'ús UC003 - *Iniciar Sessió* ####

Un usuari un cop s'ha enregistrat al sistema ja pot utilitzar l'aplicació, però el sistema l’ha de reconèixer iniciant sessió abans.

#### Cas d'ús UC004 - *Publicar Servei* ####

L'usuari pot publicar un servei que ell ofereix a la resta d'usuaris. Ha d'especificar el preu (en hores) i donar una descripció del servei.

#### Cas d'ús UC005 - *Esborrar Servei* ####

Si un usuari decideix que ja no ofereix un servei el pot esborrar, sempre i quan sigui ell el propietari d’aquest.

#### Cas d'ús UC006 - *Veure Servei* ####

Un usuari pot veure la llista de serveis oferts en la qual pot seleccionar-ne un i veure la informació d'aquest en concret.

#### Cas d'ús UC007 - *Modificar Servei* ####

Un usuari en qualsevol moment pot modificar la descripció i/o el preu d'un servei, sempre i quan sigui ell el propietari d’aquest.

#### Cas d'ús UC008 - *Veure Ofertes de Serveis* ####

Un usuari pot llistar tots els serveis oferts per tal de poder navegar en ells i triar el que més necessita.

#### Cas d'ús UC009 - *Buscar Servei* ####

L'usuari disposa d'un buscador per tal de trobar serveis a través paraules claus que identifiquin el servei.

#### Cas d'ús UC010 - *Contactar Altre Usuari* ####

Un cop dins d'un servei en concret, l'usuari pot contactar amb el propietari del servei via chat dins de la mateixa aplicació i això poder parlar directament amb l’altre usuari de la comunitat.

#### Cas d'ús UC011 - *Valorar un Servei* ####

Un cop un usuari ha rebut un servei d'un altre usuari, pot valorar el servei rebut per tal que altres usuaris puguin veure la valoració mitjana de l’usuari.

#### Cas d'ús UC012 - *Pagar Servei* ####

Un cop un usuari ha rebut un servei d'un altre usuari, ha de pagar aquest servei. L'usuari disposarà de l'opció de pagar a l'altre usuari les hores marcades en el preu del servei anunciat.

#### Cas d'ús UC013 - *Buscar Ubicació a Google Maps* ####

L'usuari pot veure a través de l'API Google Maps la ubicació exacta on realitza un servei determinat.

#### Cas d'ús UC014 - *Vincular Servei amb Google Calendar* ####

L'usuari quan contracta un servei o un altre usuari li contracta un servei seu, pot decidir sincronitzar-ho amb Google Calendar i d'aquesta manera obtenir un recordatori en el moment desitjat.




#### Mockups ####

Per tal d’entendre millor el sistema, a continuació es disposa d’un seguit d’imatges on es mostra visualment l’aproximació de com seria l’aplicació Time Barter (en angles: *Intercanvi de Temps*).



![Mockups](https://bytebucket.org/AlbertSuarez/gps-up-23/raw/762d14a0e45cc6cfe65f057f7544a69d03fc6d5c/mockups.png?token=85d9d82dfd09c732c56409ee3efb8afe551bb044)


## **2. ESPECIFICACIÓ NO FUNCIONAL** ##

**Requisits d’aparença**

*Tipus de requisit segons (Volere)*: 10 a

*Descripció*: Disseny atractiu i d’ús senzill que convidarà a l'usuari a fer-ne ús.

*Justificació del requisit*: Com l'aplicació treballa sobre un nombre de persones considerable com és tota Barcelona, cal destacar per l'atractiu de l'aplicació per tal de marcar un abans i un després en l'usuari.

*Condició de satisfacció*: El requisit se satisfarà si s'obté una bona valoració dels usuaris en respecte a l'apariència.


**Requisits d’estil**

*Tipus de requisit segons (Volere)*: 10 b

*Descripció*: Disseny modern i ambiciós, seguint la tendència en disseny però destacant en punts específics.

*Justificació del requisit*: La competència del mercat ens obliga a disposar d’un disseny modern per tal destacar sobre els usuaris.

*Condició de satisfacció*: El requisit se satisfarà si més de tres quartes parts dels usuaris consideren un disseny modern.


**Requisits de facilitat d’ús**

*Tipus de requisit segons (Volere)*: 11 a

*Descripció*: El sistema ha de ser intuïtiu i fàcil d'usar. Complirà els criteris de temes de disseny, de contingut, d'estructura i de presentació fixats pel W3C.

*Justificació del requisit*: Un punt diferenciador important és que l'usuari pugui fer servir el sistema intuïtivament, de manera que no perdi el temps intentant descobrir com funciona i, a més a més, que qualsevol persona sigui capaç de familiaritzar-se amb el sistema.

*Condició de satisfacció*: El requisit se satisfarà si un usuari amb poca experiència en aplicacions aconsegueix usar-lo sense cap problema.


**Requisits de latència i velocitat**

*Tipus de requisit segons (Volere)*: 12 a

*Descripció*: La resposta del sistema ha de ser de menys d'un segon com a mínim en el 95% de les operacions.

*Justificació del requisit*: Un temps de resposta ràpid permet que l’usuari no perdi el flux o atenció del que esta fent amb el sistema.

*Condició de satisfacció*: El requisit se satisfarà si donat un estudi sobre el rendiment de l'aplicació, aquest confirma que el temps d'espera en cada acció és menor al segon en el 95% dels casos.


**Requisits de precisió o exactitud**

*Tipus de requisit segons (Volere)*: 12 c

*Descripció*: Totes les dates que s’incloguin en l’aplicació tindran el format següent: DD/MM/AAAA

*Justificació del requisit*: és convenient especificar el format de la data ja que no a tot arreu té el mateix format i podria provocar malentesos entre els usuaris.

*Condició de satisfacció*: El requisit se satisfarà si el format de la data i l'hora segueix l’estàndard ISO-8601 extens d’estil Europeu (EN 28601).


**Requisit de disponibilitat**

*Tipus de requisit segons (Volere)*: 12 d

*Descripció*: El sistema haurà d'estar disponible les 24 hores del dia durant els 365 dies que conformen l’any.

*Justificació del requisit*: Els usuaris han de poder utilitzar el sistema en qualsevol moment del dia per tal de poder buscar serveis o oferir-ne.

*Condició de satisfacció*: El requisit se satisfarà si el sistema està disponible i completament funcional tot el temps.


**Requisits d’adaptabilitat**

*Tipus de requisit segons (Volere)*: 14 c

*Descripció*: L’aplicació web ha de poder-se veure correctament en els diferents navegadors més utilitzats i en la majoria de smartphones, i tenir les mateixes funcions que ambdós.

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
