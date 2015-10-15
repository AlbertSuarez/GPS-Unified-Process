# **SISTEMA ACME - PLA DE DESENVOLUPAMENT DE SOFTWARE** #

## **1. ORGANITZACIÓ I EQUIP** ##

El nostre equip estarà organitzat de la següent manera:

* Cap de projecte*: és l'encarregat de liderar el grup I assegurar-se que cada persona compleixi amb les expectatives. També és el responsable de distribuir els salaris de la resta de treballadors. El cap de projecte és una sola persona.

* *Analista sènior*: és qui ha de tenir un coneixement profund sobre les tècniques I recursos que s'usen, és necessari que domini els llenguatges de programació que se li demanin.

* *Analista programador*: és el treballador a qui li correspon programar les parts més complicades del programa I totes les parts que l'analista li ordeni.

* *Dissenyador*: és l'encarregat de definir l’aplicació en si, quines funcionalitats tindrà i com estarà distribuïda. Hi haurà 3 dissenyadors.

* *Enginyer de Requisits*: és el responsable d’establir els requisits que haurà de complir el projecte per tal de satisfer les necessitats bàsiques del client. Hi haurà 3 enginyers de requisits.

* *Programador Sènior*: són els encarregats de redactar tot el codi per tal que l'aplicació faci tot el que els dissenyadors defineixen en les especificacions. Hi haurà 2 programadors sènior.

* *Programador Junior*: A partir de la documentació, és l'encarregat de traduir a un llenguatge comprensible per la màquina les ordres precises per a l'execució.

* *Tester*: és el treballador que realitza els tests per la qualificació del personal. Corregeix i valora la feina d'acord amb les plantilles i barems continguts en els manuals i redacta el corresponent informe.


## **2. ESTIMACIÓ D'ESFORÇ** ##

L’estimació de l’esforç del nostre sistema l’hem calculat seguint el model UCPA amb el respectius paràmetres a calcular:

* *Actors*: s’ha de tenir en compte qualsevol entitat externa al sistema que interacciona amb ell. Cadascun d’ells se li atorga un pes entre 1 i 3 depenent de si és un altre sistema que ofereix API o requereix un altre tipus de comunicació o bé és una interacció humana (GUI). A partir d’això obtenim el valor *UAW*.

* *Casos d’ús*: també s’ha de valorar el flux d’esdeveniments per assolir un objectiu. Cadascun d’aquests se’ls ha valorat segons la seva complexitat (Simple, Mig o Complex) i atorgant-li un pes (5, 10 o 15 respectivament). S’obtindrà el valor *UUCW*.

* *Complexitats tècniques*: disposa d’un catàleg de 13 factors on cal fixar-ne el pes basat en la complexitat d’aquest i la prioritat, és a dir, la importància en el projecte. El valor obtingut serà el *TCF*.

* *Factors d’entorn*: es té en compte 8 factors on es representen els factors relacionals al projecte, context, etc., que no són governables i que poden influir en el projecte. Cadascun d’aquests té un pes. S’obté el valor *ECF*.

A continuació es disposa de les taules on es fa el càlcul dels 4 paràmetres explicats anteriorment.

![Actors]( https://bytebucket.org/AlbertSuarez/gps-up-23/raw/b41ce6eeb02b8c2930552b6360782111c9062c19/Imatges/Actors.PNG?token=4fe204e7073829d2f0460e49f922760a16b9d5ad)

![Casos d’Us]( https://bytebucket.org/AlbertSuarez/gps-up-23/raw/b41ce6eeb02b8c2930552b6360782111c9062c19/Imatges/CasosDUs.PNG?token=3702aa8c316c1b4cdc0245661257ee78f7a2bd93)

![Complexitats Tecniques]( https://bytebucket.org/AlbertSuarez/gps-up-23/raw/b41ce6eeb02b8c2930552b6360782111c9062c19/Imatges/ComplexitatsTecniques.PNG?token=480e3ab401902de644544460593bee5275d2479d)

![Factors d’entorn]( https://bytebucket.org/AlbertSuarez/gps-up-23/raw/b41ce6eeb02b8c2930552b6360782111c9062c19/Imatges/EstimacioDEsforc.PNG?token=fa787325725546fda7ca707f09d5d33b4f7873de)



Un cop obtingut tots els valors mencionats anteriorment, hem de decidir el factor PF, contingut entre 15 i 30, donat en base a alguns factors com:

* *Entregar la feina en el termini indicat*.

* *Compliment del pressupost*.

* *Experiència en treball en equip*.

Llavors, hem decidit optar per un factor mig, és dir, prendre PF com 22,5. Aleshores, el càlculs serien els següents.

**UCP = (UUCW + UAW) x TCF x ECF = 111.9976**

**Estimació d’esforç = UCP * PF = 2519.95 hores**



## **3. ESTIMACIÓ DE COST** ##

> Calculeu el cost de personal i la resta de coses. Useu un excel o altra eina per fer els càlculs. Copieu aquí les taules (però entregueu també l'excel!). 
> FEINA ALBERT I VICTOR


## **4. PLA DE PROJECTE** ##

> Per cada fase, dir: objectius, entregables més importants, quantes iteracions a cada fase, dates d'inici i finalització, esforç de cada rol a cada fase, etc.

Per tal de garantir una bona organització del desenvolupament del projecte,s'ha decidit dividir en quatre fase (Inception, Elaboration, Construction i Transition),
tal i com marca el protocol UP, què és en el que ens basem.


### Inception ###

En aquesta fase, principalment l'objectiu és entendre el problema que se'ns planteja. L'enginyer de requisits i l'analista superior seran els principals protagonistes en aquesta fase.
A més a més, el cap de projecte aportarà un valor important en la presa de decisions.Les principals tasques a realitzar en aquesta fase seran les següents:

* Establir l’àmbit del projecte i condicions de frontera.

* Determinar els casos d’ús i els seus escenaris principals.

* Visualitzar una arquitectura candidata en base a alguns escenaris primaris.

* Estimar el cost i planificació temporal.

* Identificar possibles riscos.

* Preparar l’entorn de treball del projecte.


### Elaboration ###

En la segona fase, després d'un estudi del context i entendre el problema, cal entendre la solució plantejada. Per això, prenen protagonisme l'analista i programador senior i el dissenyador. 
A part, també destaca el cap de projecte que ha d'acabar de refinar el projecte. Les principals feines a fer en la segona fase seran les següents:

* Definir, validar i articular l’arquitectura.

* Considerar riscos arquitectònics significatius.

* Delinear la visió del projecte.

* Demostrar que l’arquitectura suportarà la visió en un temps raonable i a un cost raonable.

* Produir un pla detallat per a la fase de Construcció.

* Refinar l’entorn de treball del projecte.


### Construction ###

En aquesta fase el principal objectiu és obtenir la solució plantejada durant la fase anterior. Com és lògic, en aquesta part del projecte els programadors, tant senior com junior,
 aportan la major part del treball de la fase. A més a més, el tester realitza les primeres proves amb les primeres versions del sistema. En aquesta tercera fase, les tasques a realitzar són les següents:

* Completar el producte software per a la seva transició a producció.

* Minimitzar els costos de desenvolupament gràcies a l’optimització de recursos.

* Arribar a una qualitat adequada tan ràpidament com es considera pràctic.

* Obtenir versions útils (alfa, beta, i altres versions de proves) tan ràpidament com sigui possible.


### Transition ###

Per últim, en aquesta quarta fase l'objectiu primordial i principal és lliurar la solució. Per tant, els membres de l'equip principals són el cap de projecte i el tester.
Eventualment, els programadors i analistes també tenen un paper important per sí sorgeix algun canvi d'última hora. Les feines a fer són les següents:

* Permetre al client que sigui auto‐suficient en l’ús del producte
* Obtenir l’aprovació dels interessats
* Arribar a la configuració final de forma ràpida i efectiva

Llavors, finalment en aquesta fase, es decideix si alliberar el producte o no al mercat.



A continuació es mostra una taula representativa dels percentatges de treball per rol subdividit en les 4 fases marcades pel protocol UP.

![Percentatge de rols aproximat]( https://bytebucket.org/AlbertSuarez/gps-up-23/raw/41b8dc3682c9709577d338db2b21b4a99fdae350/Imatges/PercentatgeDeRolsAproximat.PNG?token=036aee3fc0389cac9bf89f00beeb8e44f8b300e5)

Quant als casos d'ús, la distribució de fases plantejada pel protocol UP, estableix:

 - La identificació s'ha de dur a terme principalment durant les faces d'inception i Elaboration.
 - L'esboçat s'ha de plantejar a la fase d'inception i s'ha d'acabar completament durant la fase Construction.
 - El refinat s'elabora principalment a les fases Elaboration i Construction
 - L'analisi es realitza durant les fases Elaboration i construction
 - A la fase de Transition el cas d'us ha destar complert.
 
 ![Analisi en termes de cas d'ús](https://bitbucket.org/AlbertSuarez/gps-up-23/src/2d6e71a2a5d31dc9f26d58d0185052978c0bcc4a/Imatges/AnalisisEnTermeDeCasosDUs.PNG?at=master&fileviewer=file-view-default)
