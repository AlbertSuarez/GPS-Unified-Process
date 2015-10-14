# **SISTEMA ACME - ESPECIFICACI� DE REQUISITS DEL SOFTWARE** #

## **1. ESPECIFICACI� FUNCIONAL** ##

### 1.1. Diagrama de casos d'�s




![Diagrama de casos d�us](https://bytebucket.org/AlbertSuarez/gps-up-23/raw/86006fbc5ee3334957c81dd868848f366191a5dd/Imatges/DiagramaCasosDus.png?token=fc5bcf4cf5b44f79c8752bc2f506fdd939689a0e)

### 1.2. Descripci� individual dels casos d'�s

#### Cas d'�s UC001 - *Esborrar Usuari* ####

L'administrador pot esborrar un usuari del sistema si detecta algun error en el compte, activitats il�legals, incompliments de les regles de la comunitat, etc.

#### Cas d'�s UC002 - *Registrar-se* ####

Un usuari pot crear un compte d'usuari per tal de formar part de la comunitat i, llavors registrar-lo en el sistema.

#### Cas d'�s UC003 - *Iniciar Sessi�* ####

Un usuari un cop s'ha enregistrat al sistema ja pot utilitzar l'aplicaci�, per� perqu� el sistema el reconegui ha d'iniciar sessi� pr�viament.

#### Cas d'�s UC004 - *Publicar Servei* ####

L'usuari pot publicar un servei que ell ofereix a la resta d'usuaris. Ha d'especificar el preu (en hores) i donar una descripci� del servei.

#### Cas d'�s UC005 - *Esborrar Servei* ####

Si un usuari decideix que ja no ofereix un servei el pot esborrar, sempre i quan sigui ell el propietari d�aquest.

#### Cas d'�s UC006 - *Veure Servei* ####

Un usuari pot veure la llista de serveis oferts en la qual pot seleccionar-ne un i veure la informaci� d'aquest en concret.

#### Cas d'�s UC007 - *Modificar Servei* ####

Un usuari en qualsevol moment pot modificar la descripci� i/o el preu d'un servei, sempre i quan sigui ell el propietari d�aquest.

#### Cas d'�s UC008 - *Veure Ofertes de Serveis* ####

Un usuari pot llistar tots els serveis oferts per tal de poder navegar en ells i triar el que m�s necessita.

#### Cas d'�s UC009 - *Buscar Servei* ####

L'usuari disposa d'un buscador per tal de trobar serveis a trav�s paraules claus que identifiquin el servei.

#### Cas d'�s UC010 - *Contactar Altre Usuari* ####

Un cop dins d'un servei en concret, l'usuari pot contactar amb el propietari del servei via chat dins de la mateixa aplicaci� i aix� poder parlar directament amb l�altre usuari de la comunitat.

#### Cas d'�s UC011 - *Valorar un Servei* ####

Un cop un usuari ha rebut un servei d'un altre usuari, pot valorar el servei rebut per tal que altres usuaris puguin veure la valoraci� mitjana de l�usuari.

#### Cas d'�s UC012 - *Pagar Servei* ####

Un cop un usuari ha rebut un servei d'un altre usuari, ha de pagar aquest servei. L'usuari tindr� l'opci� de pagar a l'altre usuari les hores marcades en el preu del servei anunciat.

#### Cas d'�s UC013 - *Buscar Ubicaci� a Google Maps* ####

L'usuari pot veure a trav�s de l'API Google Maps la ubicaci� exacta on realitza un servei determinat.

#### Cas d'�s UC014 - *Vincular Servei amb Google Calendar* ####

L'usuari quan contracta un servei o un altre usuari li contracta un servei seu, pot decidir sincronitzar-ho amb Google Calendar i d'aquesta manera obtenir un recordatori en el moment desitjat.




#### Mockups ####

Per tal d�entendre millor el sistema, a continuaci� es disposa d�un seguit d�imatges on es mostra visualment l�aproximaci� de com seria l�aplicaci� Time Barter (en angles: *Trueque de Tiempo*).



![Mockups](https://bytebucket.org/AlbertSuarez/gps-up-23/raw/762d14a0e45cc6cfe65f057f7544a69d03fc6d5c/mockups.png?token=85d9d82dfd09c732c56409ee3efb8afe551bb044)


## **2. ESPECIFICACI� NO FUNCIONAL** ##

**Requisits d�aparen�a**

*Tipus de requisit segons (Volere)*: 10 a

*Descripci�*: Disseny atractiu i d��s senzill que convidar� a l'usuari a fer-ne �s.

*Justificaci� del requisit*: Com l'aplicaci� treballa sobre un nombre de persones considerable com �s tota Barcelona, cal destacar per l'atractiu de l'aplicaci� per tal de marcar un abans i un despr�s en l'usuari.

*Condici� de satisfacci�*: El requisit se satisfar� si s'obt� una bona valoraci� dels usuaris en respecte a l'apari�ncia.


**Requisits d�estil**

*Tipus de requisit segons (Volere)*: 10 b

*Descripci�*: Disseny modern i ambici�s, seguint la tend�ncia en disseny per� destacant en punts espec�fics.

*Justificaci� del requisit*: La compet�ncia del mercat ens obliga a disposar d�un disseny modern per tal destacar sobre els usuaris.

*Condici� de satisfacci�*: El requisit se satisfar� si m�s de tres quartes parts dels usuaris consideren un disseny modern.


**Requisits de facilitat d��s**

*Tipus de requisit segons (Volere)*: 11 a

*Descripci�*: El sistema ha de ser intu�tiu i f�cil d'usar. Complir� els criteris de temes de disseny, de contingut, d'estructura i de presentaci� fixats pel W3C.

*Justificaci� del requisit*: Un punt diferenciador important �s que l'usuari pugui fer servir el sistema intu�tivament, de manera que no perdi el temps intentant descobrir com funciona i, a m�s a m�s, que qualsevol persona sigui capa� de familiaritzar-se amb el sistema.

*Condici� de satisfacci�*: El requisit se satisfar� si un usuari amb poca experi�ncia en aplicacions aconsegueix usar-lo sense cap problema.


**Requisits de lat�ncia i velocitat**

*Tipus de requisit segons (Volere)*: 12 a

*Descripci�*: La resposta del sistema ha de ser de menys d'un segon com a m�nim en el 95% de les operacions.

*Justificaci� del requisit*: Un temps de resposta r�pid permet que l�usuari no perdi el flux o atenci� del que esta fent amb el sistema.

*Condici� de satisfacci�*: El requisit se satisfar� si donat un estudi sobre el rendiment de l'aplicaci�, aquest confirma que el temps d'espera en cada acci� �s menor al segon en el 95% dels casos.


**Requisits de precisi� o exactitud**

*Tipus de requisit segons (Volere)*: 12 c

*Descripci�*: Totes les dates que s�incloguin en l�aplicaci� tindran el format seg�ent: DD/MM/AAAA

*Justificaci� del requisit*: �s convenient especificar el format de la data ja que no a tot arreu t� el mateix format i podria provocar malentesos entre els usuaris.

*Condici� de satisfacci�*: El requisit se satisfar� si el format de la data i l'hora segueix l�est�ndard ISO-8601 extens d�estil Europeu (EN 28601).


**Requisit de disponibilitat**

*Tipus de requisit segons (Volere)*: 12 d

*Descripci�*: El sistema haur� d'estar disponible les 24 hores del dia durant els 365 dies que conformen l�any.

*Justificaci� del requisit*: Els usuaris han de poder utilitzar el sistema en qualsevol moment del dia per tal de poder buscar serveis o oferir-ne.

*Condici� de satisfacci�*: El requisit se satisfar� si el sistema est� disponible i completament funcional tot el temps.


**Requisits d�adaptabilitat**

*Tipus de requisit segons (Volere)*: 14 c

*Descripci�*: L�aplicaci� web ha de poder-se veure correctament en els diferents navegadors m�s utilitzats i en la majoria de smartphones, i tenir les mateixes funcions que ambd�s.

*Justificaci� del requisit*: L'exist�ncia de diferents navegadors web i sistemes operatius en smartphones obliga a garantir que com a m�nim es veur� de forma correcta.

*Condici� de satisfacci�*: El requisit se satisfar� si el sistema es pot visualitzar correctament en els principals navegadors web i smartphones.


**Requisit d�immunitat**

*Tipus de requisit*: 15 e

*Descripci�*: El sistema est� protegit d�atacs externs i infeccions per software malici�s.

*Justificaci� del requisit*: S�ha de garantir la seguretat per evitar posar en risc la disponibilitat del sistema i la privadesa de les dades dels usuaris.

*Condici� del requisit*: El requisit se satisfar� si s'implementa la normativa de seguretat internacional ISO-17799 per tal de garantir la seguretat davant d'atacs externs.


**Requisits legals**

*Tipus de requisit segons (Volere)*: 17 a

*Descripci�*: S�aconseguiran tots els drets sobre els serveis externs que s�utilitzin a l�aplicaci� i a la vegada es complir� les lleis sobre el tractament de dades personals.

*Justificaci� del requisit*: Es pactaran acords amb totes les empreses de les que s�utilitzen els seus serveix, arribant a acords sigui amb la Universitat per poder aprofitar la seva plataforma o amb empreses externes. I tamb� mostrar transpar�ncia a l'hora de no compartir dades personals per fins no vinculants al sistema.

*Condici� de satisfacci�*: El requisit se satisfar� si no es rep cap denuncia per part de cap servei extern, ni de cap usuari per �s indegut de les dades personals.
