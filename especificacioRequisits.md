> Nota preliminar: tots els comentaris de la plantilla són informatius i han de desaparéixer en la versió entregable

# SISTEMA ACME - ESPECIFICACIÓ DE REQUISITS DEL SOFTWARE #


> El propòsit del document d'especificació de requisits presenta el detall dels requisits del sistema. És un document evolutiu, atès que el nombre i detall dels requisits creix a mida que s'avança en el projecte

> Donat el principi de "dirigit per casos d'ús", l'especificació funcional pendrà la forma d'una especificació per casos d'ús

> Recordem que els documents de visió i cas de negoci tindran força informació sobre el producte, que aquí no repetirem


## 1. ESPECIFICACIÓ FUNCIONAL ##

### 1.1. Diagrama de casos d'ús

![](https://bytebucket.org/AlbertSuarez/gps-up-23/raw/84c11875067262e2a5101efe8237bc91de268216/DiagramaCasosDus.png?token=3b536e9d5a53602e751c5dabc720f67c40e4073c)


> A més, per cada cas d'ús, una descripció d'una o dues línies (fins i tot si el nom és prou auto-explicatiu, pot no ser necessari)

- Cas d'ús UC001 - *nom*: descripció

- Cas d'ús UC002 - *nom*: descripció

- etc...

### 1.2. Descripció individual dels casos d'ús

> Un per un, es descriuen els casos d'ús introduïts a la subsecció 1.1. Com ja s'ha dit adalt, els casos d'ús s'aniran defining paulatinament

#### Cas d'ús UC001 - *nom* ####

> Descripció del primer cas d'ús. Si bé en una especificació "de veritat", escriuriem el curs rellevant d'esdeveniments, excepcions, etc., aquí ens conformem amb una descripció més "lleugera"

#### Cas d'ús UC002 - *nom* ####

> etc.

## 2. ESPECIFICACIÓ NO FUNCIONAL ##

> Descriure en més detall els requisits no funcionals que han sortit al document de visió, intentant fer-los el més quantificables posible


Requisits d’aparença
Número: 1
Tipus de requisit segons (Volere): 10 a
Descripció: Disseny atractiu i d’ús senzill que convidarà a fer-ne ús. 
Justificació del requisit: Atès que serà una aplicació utilitzada per un públic exigent com són els estudiants serà necessari fer un bon disseny que agradi a tothom y ens faci guanyar popularitat.
Condició de satisfacció: Auto-explicatiu

Requisits d’estil
Número: 2
Tipus de requisit segons (Volere): 10 b
Descripció: Disseny modern i ambiciós
Justificació del requisit: La competència del mercat ens obliga a disposar d’un disseny modern.
Condició de satisfacció: +75% dels usuaris afirmen que el disseny es modern

Requisits de facilitat d’ús
Número: 3
Tipus de requisit segons (Volere): 11a
Descripció: El sistema ha de ser intuïtiu i fàcil d'usar. Complirà els criteris de temes de disseny, de contingut, d'estructura i de presentació fixats pel W3C.
Justificació del requisit: Un punt diferenciador important és que l'usuari pugui fer servir el sistema intuitivament, de manera que no perdi el temps intentant descobrir com funciona i, a més a més, que qualsevol persona sigui capaç de familiaritzar-se amb el sistema. 
Condició de satisfacció: Ha de ser fàcil d’usar.

Requisits de latència i velocitat
Número: 5
Tipus de requisit segons (Volere): 12 a
Descripció: La resposta del sistema ha de ser de menys de un segon com a mínim en el 95% de les operacions.
Justificació del requisit: Un temps de resposta ràpid permet que l’usuari no perdi el flux o atenció del que esta fent amb el sistema.
Condició de satisfacció: Es guardarà el temps de resposta del sistema per fer-ne un estudi i demostrar que funciona correctament aquest requisit. 

Requisits de precisió o exactitud
Número: 6
Tipus de requisit segons (Volere): 12 c
Descripció: Totes les dates que s’incloguin en l’aplicació tindran el següent format: 
DD/MM/AAAA
Justificació del requisit: És convenient especificar el format de la data ja que no a tot arreu té el mateix format.
Condició de satisfacció: El format  data i hora  seguirà l’estandard ISO -8601 extens d’estil Europeu (EN 28601).

Requisit de precisió o exactitud
Número: 7
Tipus de requisit segons (Volere): 12d
Descripció: El sistema haurà d'estar disponible les 24 hores del dia durant els 365 dies que conformen l’any.
Justificació del requisit: Els usuaris han de poder utilitzar el sistema en qualsevol moment per poder gestionar les seves tasques del sistema.
Condició de satisfacció: El sistema estarà disponible i completament funcional tot el temps.

Requisits d’adaptabilitat
Número: 8
Tipus de requisit segons (Volere): 14c
Descripció: L’aplicació web ha de poder-se veure correctament en els diferents navegadors més utilitzats.
Justificació del requisit: L'existència de diferents navegadors web obliga a garantir que com a mínim es veurà de forma correcta en els més comuns com Firefox, Safari o  Google Chrome.. 
Condició de satisfacció: El sistema es visualitzarà correctament en les versions especificades i posteriors dels següents navegadors: Firefox 5, Safari i Chrome 11.

Número: 9
Tipus de requisit: 14c
Descripció: L’aplicació web ha de poder-se veure correctament en les diferents plataformes existents.
Justificació del requisit: L’existència de diferents plataformes com poden ser smartphones, tablets o ordinador obliga que a garantir que es vegi de forma correcta en tots ells.
Condició de satisfacció: El sistema es visualitzarà correctament en les diverses plataformes especificades: Smartphones, tablets i ordinador.

Requisit d’immunitat
Número: 10
Tipus de requisit: 15e
Descripció: El sistema està protegit d’atacs externs i infeccions per software maliciós. 
Justificació del requisit: S’ha de garantir la seguretat per evitar posar en risc la disponibilitat del sistema i la privadesa de les dades dels usuaris.
Condició del requisit: Implementació d’una normativa de seguretat internacional com la normativa ISO 17799 per garantir la seguretat davant d'atacs externs. 

Requisits legals
Número: 11
Tipus de requisit segons (Volere): 17a
Descripció: S’aconseguiran tots els drets sobre els serveis externs que s’utilitzin a l’aplicació.
Justificació del requisit: Es pactaran acords amb totes les empreses de les que s’utilitzen els seus serveix, arribant a acords sigui amb la Universitat per poder aprofitar la seva plataforma o amb empreses externes. 
Condició de satisfacció: No rebrà cap denuncia per part de cap servei extern.

Número: 12
Tipus de requisit segons (Volere): 17a
Descripció: Compliment de la lleis sobre el tractament de dades que l’usuari ingressa i guarda en el sistema.
Justificació del requisit: Al registrar-se en el sistema (Cas d’ús: Registrar-se) l’usuari serà informat sobre la utilització de les seves dades per a vendre a tercers, però sense compartir res de dades personals. 
Condició de satisfacció: No rebrà cap incidència per part de cap usuari respecte a l’ús inadequat de les seves dades.
