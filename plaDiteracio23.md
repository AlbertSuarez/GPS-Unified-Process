# **SISTEMA ACME - PLA D'ITERACIÓ *Inception*** #

## **1. PRESENTACIÓ DE LA ITERACIÓ** ##

En aquesta iteració, la primera i única de la fase d’Inception, principalment l'objectiu és entendre el problema que se'ns planteja. L'enginyer de requisits i l'analista superior seran els principals protagonistes en aquesta fase.
A més a més, el cap de projecte aportarà un valor important en la presa de decisions. A continuació, es disposa de la taula on es representa el repartiment d’hores de la primera iteració.

La primera iteració durarà 13 dies laborables, és a dir, de l'11 de Gener al 27 del mateix mes. A més a més, a continuació es mostra una taula amb el repartiment de dies per fase.

Les principals tasques a realitzar en aquesta fase seran les següents:

* Establir l’àmbit del projecte i condicions de frontera.

* Determinar els casos d’ús i els seus escenaris principals.

* Visualitzar una arquitectura candidata basant-se en alguns escenaris primaris.

* Estimar el cost i planificació temporal.

* Identificar possibles riscos.

* Preparar l’entorn de treball del projecte.

![hores per treballador i fase](https://bytebucket.org/AlbertSuarez/gps-up-23/raw/3a78e7d6c1fffff81484ca55605513746258908a/Imatges/Hores%20per%20treballador%20i%20fase.PNG?token=81324f8d3d660c7a5ce9d7a008bc5bb7cdfb6fa3)

![percentatge de rols](https://bytebucket.org/AlbertSuarez/gps-up-23/raw/3a78e7d6c1fffff81484ca55605513746258908a/Imatges/PercentatgeDeRolsAproximat.PNG?token=a5dbdbe17e148f693951e8a11ef772c0fd5a83f5)

![topdown](https://bytebucket.org/AlbertSuarez/gps-up-23/raw/3a78e7d6c1fffff81484ca55605513746258908a/Imatges/TopDown.PNG?token=e2a3606ee2613c19c70f51f01b612c80341ac741)


## **2. COBERTURA DE CASOS D'ÚS** ##

Basant-nos en la taula mostrada en el pla de desenvolupament software del nostre sistema que explicava l'estat de cada cas d'ús en cada fase del projecte, ens centrarem només en la primera i única iteració de la fase *Inception*. Així doncs, com podem veure a continuació, 11 dels 14 casos d'ús del nostre sistema estaran ja identificats.

![estat de casos dus en inception](https://bytebucket.org/AlbertSuarez/gps-up-23/raw/39b0bf333f83e2cc97e3fff95592e037b9fd9faa/Imatges/CasosDusInception.png?token=d777670eb86ac90a56dcec5ed77a5766527ccd72)


## **3. ACTIVITATS** ##

Aquesta primera fase, la d'*Inception*, es pot subdividir en 6 activitats de les quals totes tenen dependències amb les anteriors a ella, menys dos en especial: Preparar l'entorn de treball del projecte i Identificar riscos que es poden fer en paral·lel.

1. Establir l’àmbit del projecte i condicions de frontera. (1 dia)
2. Preparar l’entorn de treball del projecte. (1 dia)
3. Identificar possibles riscos. (2 dies)
4. Determinar els casos d’ús i els seus escenaris principals. (3 dies)
5. Visualitzar una arquitectura candidata basant-se en alguns escenaris primaris. (3 dies)
6. Estimar el cost i planificació temporal. (4 dies)

La suma de temps de les sis activitats és equivalent als 13 dies de durada de la primera iteració ja acordats anteriorment.

## **4. DIAGRAMA DE GANTT** ##

Llavors, donades les activitats mencionades d'aquesta iteració, les seves respectives durades i la capacitat de paral·lelització d'aquestes. Sorgeix el següent diagrama de Gantt i de Pert:

![Diagrama Gantt](https://bytebucket.org/AlbertSuarez/gps-up-23/raw/39b0bf333f83e2cc97e3fff95592e037b9fd9faa/Imatges/diagramaGanttInception.png?token=1539ffdbb95f229bc803cbdb8c923b71b281fa32)

![Diagrama Pert](https://bytebucket.org/AlbertSuarez/gps-up-23/raw/39b0bf333f83e2cc97e3fff95592e037b9fd9faa/Imatges/DiagramaPert.png?token=b9f31e14e9e7a1c164690b4ccca7026cfdf8e39b)

Aleshores, donat aquest aquest diagrama, podem veure que el camí crític passa per l'1, 3, 4, 5 i 6. La majoria d'activitats es realitzen seqüencialment perquè considerem que no es poden realitzar sense haver-se finalitzat l'anterior, menys en el cas de l'activitat 2 (Preparar l’entorn de treball del projecte) i l'activitat 3 (Identificar possibles riscos). En aquest cas, entenem que preparar l'entorn en el qual es desenvoluparà el projecte es pot fer paral·lelament amb identificar els possibles riscos d'aquest.