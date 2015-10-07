
# SISTEMA ACME - PLA DE DESENVOLUPAMENT DE SOFTWARE #

> El propòsit del document de pla de desenvolupament de software és determinar l'esforç, cost i calendari a nivell de projecte (distingint només les 4 fases)


## 1. ORGANITZACIÓ I EQUIP ##

> Descriure breument l'organització i l'equip de treball (quins rols, quants treballadors de cada rol)
El nostre equip estarà organitzat de la següent manera:
- Cap de projecte
- Analista
- 2 Desenvolupadors/Administradors del sistema

## 2. ESTIMACIÓ D'ESFORÇ ##

> Calcular el nombre d'hores del projecte. Useu un excel o altra eina per calcular UCPs i convertir a hores. Copieu aquí les taules (però entregueu també l'excel!)

## 3. ESTIMACIÓ DE COST ##

> Calculeu el cost de personal i la resta de coses. Useu un excel o altra eina per fer els càlculs. Copieu aquí les taules (però entregueu també l'excel!). 

## 4. PLA DE PROJECTE ##

> Cal organitzar aquesta secció amb la informació més rellevant de les fases. Per cada fase, dir: objectius, entregables més importants, quantes iteracions a cada fase, dates d'inici i finalització, esforç de cada rol a cada fase, etc.

-->distribució típica de les fases 

	Inception Elaboration Construction Transition
Effort 	5%	 20% 	 65% 	 10%
Schedule 	10%	 30%	 50%	 10%


--->Anàlisi en termes de casos d’ús
Estat cas d’ús	Inception		Elaboration		Construction	 Transition
Identificat 	60% 		>80% 		100% 		100% 
Esboçat 		50% 		60‐70% 		100% 		100%
Refinat 		10% 		40‐80% 		100% 		100%
Analitzat 		<10% 		20‐40% 		100% 		100%
Complet 		<5% 		<10% 		<100% 		100%


-->Percentatge de Rols aproximat
		Inception		Elaboration	 	Construction	Transition
Analista s. 	65%		 30%		 5% 		10%
Arquitecte 		10%		 20%		 15%		 10%
Analista p. 	5%		 15%		 10%		 10%
Program. 		0%		 15%		 40%		 10%
Tester 		0%		 5%		 15%		 0%
Gestor p. 		20%		 15%		 15%		 60%

-->iteracions --> cal parlar


### INCEPTION ###

>punts sobre els q cal parlar
--->Entendre el problema

-Establir l’àmbit del project i condicions de frontera
-Determinar els casos d’ús i els seus escenaris principals
-Visualitzar una arquitectura candidata en base a alguns escenaris primaris
-Estimar el cost i planificació temporal
-Identificar possibles riscos
-Preparar l’entorn de treball del projecte


### ELABORATION ###

-->entendre la solució
• Definir, validar i articular l’arquitectura
• Considerar riscos arquitectònics significatius
• Delinear la visió del projecte
• Demostrar que l’arquitectura suportarà la visió en un temps raonable i a un cost raonable
• Produir un pla detallat per a la fase de Construcció
• Refinar l’entorn de treball del projecte


### CONSTRUCTION ###

-->Obtenir la solució
• Completar el producte software per a la seva transició a producció
• Minimitzar els costos de desenvolupament gràcies a l’optimització de recursos
• Arribar a una qualitat adequada tan ràpidament com es considera pràctic
• Obtenir versions útils (alfa, beta, i altres versions de proves) tan ràpidament com possible

### TRANSITION ###
-->lliurar la solució
• Permetre al client que sigui auto‐suficient en l’ús del producte
• Obtenir l’aprovació dels interessats
• Arribar a la configuració final de forma ràpida i efectiva
En aquesta fase, es decideix si alliberar el producte o no
