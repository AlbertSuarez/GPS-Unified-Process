> Nota preliminar: tots els comentaris de la plantilla són informatius i han de desaparéixer en la versió entregable

# SISTEMA ACME - VISIÓ #


> El propòsit del document de visió és recollir, analitzar i definir necesitats i capacitats d'alt nivell del sistema objecte del projecte


## 1. INTRODUCCIÓ ##

> Breu motivació i presentació del sistema. No hauria d'ocupar més de 250 paraules


## 2. EL PROBLEMA ##

> Descrivim el problema que volem resoldre amb èmfasi en el seu impacte (sobre persones, la societat, l'economia, ...)

Degut a la crisis actual, molta gent no disposa dels recursos necessaris per poder afrontar les tasques del dia a dia. A partir d’aquesta problemàtica esta sorgint una nova tendència on la moneda de canvi és el temps enlloc dels diners.

## 3. PARTS INTERESSADES ##

> Descriviu totes les parts interessades en el sistema

1. *Habitants de Barcelona*. Qualsevol habitant de Barcelona pot estar interessat en rebre serveis sense la necessitat d’haver de pagar per aquest. També existeix el cas contrari en el que la persona vol oferir un servei per tal de guanyar temps d’intercanvi.
2. *Inversors*. Recuperar la seva inversió amb interessos en un temps determinat.

## 4. EL PRODUCTE ##

> Aquesta secció descriu en alt nivell les capacitats del producte, supòsits de funcionament, dependències sobre altres sistemes, ...

### 4.1. Perspectiva del producte ###

El nostre producte serà principalment una app per a smarthphones però tindrà una altra plataforma via web per si l’usuari no disposa d’un smarthphone.
 
> Resumiu la informació en un dibuix:

![](http://www.dittoditto.com/img/screenshots/soft-arch.gif)

### 4.2. Descripció del producte ###
> Enumereu molt breument les funcionalitats més importants (el detall estarà en altre document, el d'especificació):

1. *Registrar-se*. Per poder utilitzar l’aplicació has de formar part del nostre sistema. 
2. *Iniciar Sessió*. Per poder utilitzar l’aplicació has d’iniciar sessió. 
3. *Oferir un servei*. L’usuari pot crear un anunci dient que ofereix.
4. *Veure ofertes de serveis*. L’usuari pot veure un llistat d’ofertes d’altres usuaris per trobar el que necessita.
5. *Contactar amb un altre usuari*. L’usuari quan troba l’anunci que estava buscant pot contactar amb l’altre usuari per tal de quedar amb ell i acordar els termes del “contracte”.
6. *Valorar el servei d’un usuari*. Un cop realitzada la tasca l’usuari pot valorar el servei realitzat i la professionalitat d’aquest.
7. *Intercanviar temps amb un altre usuari*. Els clients un cop s’ha realitzat la tasca acordada han de pagar al treballador el temps acordat.

 
### 4.3. Supòsits de funcionament ###
> Enumereu els supòsits per a que el producte satisfaci la seva funcionalitat:

1. *Pagament Satisfactori*. Un cop realitzada l’activitat demanada el client pagarà al treballador el temps acordat.
2. *Temps suficient*. El client a l’hora de contractar el servei disposa del temps necessari per poder-lo pagar.
3. *Acords Legals*. Un usuari no tindrà més d’una compte d’usuari per tal de poder-se transferir l’hora inicial de manera indefinida.
 
### 4.4. Dependències sobre altres sistemes ###
> Enumereu les dependències del producte sobre altres sistemes existents:

1. *Google Maps*. Per poder filtrar els serveis en funció de la seva localització el sistema interactuarà amb Google Maps.
  
### 4.5. Altres requisits ###
> Aquí ens referim només als requisits no funcionals (usabilitat, eficiència, ...). Poseu els més importants amb una molt breu descripció:

1. *Usable*. El sistema ha de ser intuïtiu i fàcil d’usar.
2. *Eficient*. El sistema ha de respondre a l’usuari en menys de mig segon.
3. *Legal*. El sistema ha de complir totes les lleis necessàries.
4. *Disponible*. El sistema ha d’estar disponible sempre.
5. *Fiable*. El sistema ha de garantir a l’usuari que les seves dades estaran protegides segons les lleis.

## 5. RECURSOS ##

> Si heu usat webs, documents, articles, etc., per basar el vostre document, enumereu aquí les referències tal i com es mostra aball. Des de la resta del document, cal referenciar l'estudi amb el seu ID entre claudàtors, "[*id*]"

[1] http://www.bdtonline.org/

[2] http://www.lavanguardia.com/vida/20100525/53933533287/siete-bancos-de-tiempo-operan-en-barcelona-para-cruzar-favores-entre-socios.html

[3] https://es.wikipedia.org/wiki/Banco_de_tiempo

[4] http://adbdt.org/

