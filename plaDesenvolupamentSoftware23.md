# **SISTEMA ACME - PLA DE DESENVOLUPAMENT DE SOFTWARE** #

## **1. ORGANITZACIÓ I EQUIP** ##

El nostre equip estarà organitzat de la següent manera:

* *Cap de projecte*: és l'encarregat de liderar el grup I assegurar-se que cada persona compleixi amb les expectatives[4]. També és el responsable de distribuir els salaris de la resta de treballadors. El cap de projecte és una sola persona.

* *Analista sènior*: és qui ha de tenir un coneixement profund sobre les tècniques I recursos que s'usen, és necessari que domini els llenguatges de programació que se li demanin.

* *Analista programador*: és el treballador a qui li correspon programar les parts més complicades del programa I totes les parts que l'analista li ordeni.

* *Dissenyador*: és l'encarregat de definir l’aplicació en si, quines funcionalitats tindrà i com estarà distribuïda. Hi haurà 3 dissenyadors.

* *Enginyer de Requisits[5]*: és el responsable d’establir els requisits que haurà de complir el projecte per tal de satisfer les necessitats bàsiques del client. Hi haurà 3 enginyers de requisits.

* *Programador Sènior*: són els encarregats de redactar tot el codi per tal que l'aplicació faci tot el que els dissenyadors defineixen en les especificacions. Hi haurà 2 programadors sènior.

* *Programador Junior*: A partir de la documentació, és l'encarregat de traduir a un llenguatge comprensible per la màquina les ordres precises per a l'execució.

* *Tester*: és el treballador que realitza els tests per la qualificació del personal. Corregeix i valora la feina d'acord amb les plantilles i barems continguts en els manuals i redacta el corresponent informe.


## **2. ESTIMACIÓ D'ESFORÇ** ##

L’estimació de l’esforç del nostre sistema l’hem calculat seguint el model UCPA amb el respectius paràmetres a calcular:

* *Actors*[1]: s’ha de tenir en compte qualsevol entitat externa al sistema que interacciona amb ell. Cadascun d’ells se li atorga un pes entre 1 i 3 depenent de si és un altre sistema que ofereix API o requereix un altre tipus de comunicació o bé és una interacció humana (GUI). A partir d’això obtenim el valor *UAW*.

* *Casos d’ús*[3]: també s’ha de valorar el flux d’esdeveniments per assolir un objectiu. Cadascun d’aquests se’ls ha valorat segons la seva complexitat (Simple, Mig o Complex) i atorgant-li un pes (5, 10 o 15 respectivament). S’obtindrà el valor *UUCW*.

* *Complexitats tècniques*: disposa d’un catàleg de 13 factors on cal fixar-ne el pes basat en la complexitat d’aquest i la prioritat, és a dir, la importància en el projecte. El valor obtingut serà el *TCF*.

* *Factors d’entorn*: es té en compte 8 factors on es representen els factors relacionals al projecte, context, etc., que no són governables i que poden influir en el projecte. Cadascun d’aquests té un pes. S’obté el valor *ECF*.

A continuació es disposa de les taules on es fa el càlcul dels 4 paràmetres explicats anteriorment.

![Actors]( https://bytebucket.org/AlbertSuarez/gps-up-23/raw/b41ce6eeb02b8c2930552b6360782111c9062c19/Imatges/Actors.PNG?token=4fe204e7073829d2f0460e49f922760a16b9d5ad)

![Casos d’Us]( https://bytebucket.org/AlbertSuarez/gps-up-23/raw/b41ce6eeb02b8c2930552b6360782111c9062c19/Imatges/CasosDUs.PNG?token=3702aa8c316c1b4cdc0245661257ee78f7a2bd93)

![Complexitats Tècniques]( https://bytebucket.org/AlbertSuarez/gps-up-23/raw/b41ce6eeb02b8c2930552b6360782111c9062c19/Imatges/ComplexitatsTecniques.PNG?token=480e3ab401902de644544460593bee5275d2479d)

![Factors d’entorn]( https://bytebucket.org/AlbertSuarez/gps-up-23/raw/b41ce6eeb02b8c2930552b6360782111c9062c19/Imatges/EstimacioDEsforc.PNG?token=fa787325725546fda7ca707f09d5d33b4f7873de)



Un cop obtingut tots els valors mencionats anteriorment, hem de decidir el factor PF, contingut entre 15 i 30, donat dacord amb alguns factors com:

* *Entregar la feina en el termini indicat*.

* *Compliment del pressupost*.

* *Experiència en treball en equip*.

Llavors, hem decidit optar per un factor mig i prendre PF com 22,5. Aleshores, els càlculs serien els següents.

**UCP = (UUCW + UAW) x TCF x ECF = 111.9976**

**Estimació d’esforç = UCP * PF = 2519.95 hores**



## **3. ESTIMACIÓ DE COST** ##

L'estimació del cost del nostre sistema ve donat de molts factors com el nombre de treballadors, el repartiment d'hores respecte als membres de l'equip, marge de benefici i així un llarg etcètera.

Per començar, cal tenir en compte el *Schedule* de les 4 fases del nostre sistema (Inception, Elaboration, Construction i Transition). Llavors dividim les hores de treball obtingudes en l'apartat anterior en els percentatges marcats. Aleshores, s'ha de decidir el salari per hora de cada membre de l'equip i la seva respectiva responsabilitat sobre el projecte. Després donat el *Schedule* mencionat i la distribució en percentatges dels rols del nostre sistema, obtenim les hores que hi dedicarà cada membre de l'equip. I llavors, simplement, multipliquem pel salari de cadascun d'ells.

![Distribució típica de les fase](https://bytebucket.org/AlbertSuarez/gps-up-23/raw/af00a6936c31c1c8cd6a89f61aeb3848a73b8ac2/Imatges/DistribucioTipicaDeLesFases.PNG?token=b8aeed46238d1fcf0592e35a03ddfdb605efe843)

![Estimació del Cost 1](https://bytebucket.org/AlbertSuarez/gps-up-23/raw/af00a6936c31c1c8cd6a89f61aeb3848a73b8ac2/Imatges/EstimacioCost1.png?token=f61ad8a8fa5abdb0a13a06af64d7b302018e20a7)

![Estimació del Cost 2](https://bytebucket.org/AlbertSuarez/gps-up-23/raw/af00a6936c31c1c8cd6a89f61aeb3848a73b8ac2/Imatges/EstimacioCost2.png?token=71940610a453918d787ced2ac6e8850a2a2bb5ac)

![Estimació del Cost 3](https://bytebucket.org/AlbertSuarez/gps-up-23/raw/af00a6936c31c1c8cd6a89f61aeb3848a73b8ac2/Imatges/EstimacioCost3.png?token=9a193399dcbe857a4dc681a3fa85ff432d7e69e5)

![Estimació del Cost 4](https://bytebucket.org/AlbertSuarez/gps-up-23/raw/af00a6936c31c1c8cd6a89f61aeb3848a73b8ac2/Imatges/EstimacioCost4.png?token=faed22ea899c963eaa45e20388b7a265afdf44e6)

Per tant, donat 13 treballadors, on tenim un cost fix de 200€ en terme de lloc de treball per treballador, obtenim un cost salarial de 35,967.19€ (tenint en compte el 40% de la cotització a la Seguretat Social). Llavors a aquest cos, hem de tenir en compte els costos estructurals (un 17.5%), que sorgeix el cost final de 42,261.45€. I per últim, s'ha de valorar el marge de benefici (d'un 50%) i el percentatge de contingències (10%). Amb tot això, surt un pressupost final de **69,731.39€**.


## **4. PLA DE PROJECTE** ##

Per tal de garantir una bona organització del desenvolupament del projecte, s'ha decidit dividir en quatre fases (Inception, Elaboration, Construction i Transition),
tal com marca el protocol UP, què és en el que ens basem.


### Inception ###

En aquesta fase, principalment l'objectiu és entendre el problema que se'ns planteja. L'enginyer de requisits i l'analista superior seran els principals protagonistes en aquesta fase.
A més a més, el cap de projecte aportarà un valor important en la presa de decisions. La primera fase durarà 13 dies laborables, és a dir, del 11 de Gener al 27 del mateix mes. Les principals tasques a realitzar en aquesta fase seran les següents:

* Establir l’àmbit del projecte i condicions de frontera.

* Determinar els casos d’ús i els seus escenaris principals.

* Visualitzar una arquitectura candidata basant-se en alguns escenaris primaris.

* Estimar el cost i planificació temporal.

* Identificar possibles riscos.

* Preparar l’entorn de treball del projecte.


### Elaboration ###

En la segona fase, després d'un estudi del context i entendre el problema, cal entendre la solució plantejada. Per això, prenen protagonisme l'analista i programador sènior i el dissenyador. 
A part, també destaca el cap de projecte que ha d'acabar de refinar el projecte. La segona fase del projecte tindrà 20 dies laborables de durada, o sigui, del 28 de Gener al 25 de Febrer. Les principals feines a fer en la segona fase seran les següents:

* Definir, validar i articular l’arquitectura.

* Considerar riscos arquitectònics significatius.

* Delinear la visió del projecte.

* Demostrar que l’arquitectura suportarà la visió en un temps raonable i a un cost raonable.

* Produir un pla detallat per a la fase de Construcció.

* Refinar l’entorn de treball del projecte.


### Construction ###

En aquesta fase el principal objectiu és obtenir la solució plantejada durant la fase anterior. Com és lògic, en aquesta part del projecte els programadors, tant sènior com junior,
 aporten la major part del treball de la fase. A més a més, el tester realitza les primeres proves amb les primeres versions del sistema. La tercera fase durarà 36 dies laborables, és a dir, del 26 de Febrer al 21 d'Abril. En aquesta tercera fase, les tasques a realitzar són les següents:

* Completar el producte software per a la seva transició a producció.

* Minimitzar els costos de desenvolupament gràcies a l’optimització de recursos.

* Arribar a una qualitat adequada tan ràpidament com es considera pràctic.

* Obtenir versions útils (alfa, beta, i altres versions de proves) tan ràpidament com sigui possible.


### Transition ###

Per últim, en aquesta quarta fase l'objectiu primordial i principal és lliurar la solució. Per tant, els membres de l'equip principals són el cap de projecte i el tester.
Eventualment, els programadors i analistes també tenen un paper important per sí sorgeix algun canvi d'última hora. La quarta fase del projecte tindrà 19 dies laborables de durada, o sigui, del 22 d'Abril al 19 de Maig. Les feines a fer són les següents:

* Permetre al client que sigui autosuficient en l’ús del producte

* Obtenir l’aprovació dels interessats

* Arribar a la configuració final de forma ràpida i efectiva


Llavors, finalment en aquesta fase, es decideix si alliberar el producte o no al mercat.



A continuació es mostra una taula representativa dels percentatges de treball per rol subdividit en les 4 fases marcades pel protocol UP.

![Percentatge de rols aproximat]( https://bytebucket.org/AlbertSuarez/gps-up-23/raw/41b8dc3682c9709577d338db2b21b4a99fdae350/Imatges/PercentatgeDeRolsAproximat.PNG?token=036aee3fc0389cac9bf89f00beeb8e44f8b300e5)

Per tant, donat els percentatge de rols aproximat i les hores dedicades totals a les quatre fases del sistema, ja podem distribuir l'execució del projecte donada pel *top-down*.

Partim de la data inicial del 11 de Gener. Llavors, donades les hores requerides per a cada fase i contant una jornada laboral de 40 hores setmanals sorgeix la següent taula:

![TopDown](https://bytebucket.org/AlbertSuarez/gps-up-23/raw/5e633ad7dd8c221cf49e57af9287f09ff58f6b87/Imatges/TopDown.PNG?token=c55fad9830876be3d043cef7f81c151225858c10)

I donats els objectius principals de cada fase mencionats anteriorment i les dates inicials i finals de cada una de les quatre parts del projecte, sorgeix la següent classificació en iteracions del projecte:

![Classificacio per iteracions](https://bytebucket.org/AlbertSuarez/gps-up-23/raw/9a6c4c51ae8e385ffefb86ba40ca3a8adf1639bd/Imatges/ClassificacioIteracions.PNG?token=a676af6f4f608c38b45585bc6f80d2a026eecb68)



I finalment en quant als casos d'ús, la distribució de fases plantejada pel protocol UP, estableix:

 - La identificació s'ha de dur a terme principalment durant les fases d'inception i Elaboration.
 - L'esbossat s'ha de plantejar a la fase d'inception i s'ha d'acabar completament durant la fase Construction.
 - El refinament s'elabora principalment a les fases Elaboration i Construction
 - L'analisi es realitza durant les fases Elaboration i construction
 - A la fase de Transition el cas d'ús ha d'estar complet.
 
 A continuació es mostra una taula que reflecteix l'anàlisi de les fases d'un cas d'ús subdividit segons el seu estat per fase de projecte:
 
 ![Anàlisi en termes de cas d'ús](https://bytebucket.org/AlbertSuarez/gps-up-23/raw/736414a4c9a980ac7a1766de55a26bd50b0b7704/Imatges/AnalisisEnTermeDeCasosDUs.PNG?token=7c8802819606af03765b3c34649f8f7cb7b37c19)
