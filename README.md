# LLEGIU-ME
Un repositori per publicar la meva primera pàgina web. Aquesta pàgina web es troba publicada a [GRADOT](https://albertroviraduch.github.io/GRADOT/).

## Tema i motivació
En el marc de l'assignatura de Eines Web, Producció i Disseny cartogràfic s'ha tingut d'elaborar una pàgina web per tal de complir els obejctius de l'assignatura. La meva pàgina web s'anomena GRADOT (Grup de Recerca d'Anàlisis de Dinàmiques D'ordenació Territorial). He fet la pàgina web d'aquest tema perquè durant el transcurs de la carrera una de les temàtiques que mès m'ha agrdat és la dedicada a temes d'ordenació i desenvolupament territorial focalitzant en la zona del la província de Tarragona ja que és la més propera a aquesta Facultat de Turisme i Geografia de la Universitat Rovira Virgili (URV).  

## Dades i continguts
La idea de realitzar GRADOT, bé de prendre de referència el Grup de Recerca GRATET de la URV.

- La inspiració per realitzar ha sigut la pàgina web de GRATET i les dades m'he inspirat en treballs que hem realitzat al llarg del Grau de Geografia, Ànalisi Territorial i Sostenibilitat 
- El text ha sigut inscrit per inspiració própia. 
- Les imatges s'han extret d'internet moltes d'elles a continuació veiem les diferents fonts. 
  1. A l'apartat del header, a cada apartat trobem una imatge diferent
     - A l'apartat de Inici, trobem una imatge de la Facultat de Turisme i Geografia extreta del portal web de l'URV.
     - A l'apartat de Membres, trobem una imatge de la Facultat de Turisme i Geografia extreta del portal web de l'URV.
     - A l'apartat de Projectes, trobem una imatge de la ciutat de Tarragona extreta de l'Ajuntament de Tarragona.
     - A l'apartat del Mapa, trobem una imatge de la Facultat de Turisme i Geografia extreta de la pàgina web de GRATET.
     - A l'apartat de Contacte, trobem una imatge de Falset extreta de l'Ajuntament del propi municipi 
  2. A la pàgina de membres trobem una imatge de cada membre.
     - El primer membre l'imatge (Nacho García) s'ha extret del portal web de l'Ajuntament de Tarragona
     - La imatge del membre Sergi Centelles s'ha extret del pinterest
     - La imatge del membre Aaron, ha estat extreta del seu perfil de la xarxa social X
     - La imatge del membre Joan Vaqué, ha estat extreta del portal web Priorat en persona
     - La imatge del membre Albert Rovira, ha sigut extreta del pinterest. 
- El mapa, ha sigut elaboració própia a partir del QGIS amb una versió 3.28 amb el complement QGis2Web amb una versió 3.20 que a l'apartat de cartografia explico com ho he fet. 


## Estructura de la Web. 
L’estructura de la pàgina web, és molt senzilla compta amb 5 grans pàgines: Inici, Membres, Projectes, Mapa i Formulari de Contacte. S'ha de dir que el layout principal de la pàgina web l'he exret de un w3Css templates. 

Aquests apartats, juntament amb el titol GRADOT i una imatge de l’universitat Rovira i Virgili, concretament de l'entrada principal de la Facultat de Geografia amb un fons de color gris clar conformen el Header. Aquest Header és repeteix pels 5 aparts. La imatge de la facultat de geografia i turisme si fem click sobre ella ens porta a la pàgina d’inici.  

A baix de tot de cada apartat he posat un peu de pàgina o footer amb fotos del logo de les principals xarxes socials i si fem click ens porta a la pàgina d’inici d’aquestes xarxes. També he col·locat un boto que s'anomena Tornar a dalt que si clickem sobre ell ens retorna al capdavant de la pàgina. 

Entre mig del footer i header, hi ha el body o cos, cada apartat te un layout diferent per tal de no fer simple i senzilla el portal web. A continuació explicare el layout d’una manera ràpida com són
  - Inici: Text de color negre amb margin i padding per tal de facilitar millor la lectura i no quedi apretat al final i inici de la pàgina web. També he afegit amb comandament HTML, concretament amb el               comandament ul i li  els punts de color negre per tal de fer una ennumeració i ficar de manera més gràfica la pàgina web.
  - Membres: Títols de cada membre remarcats amb negreta per tal de donar-li més importància i dinamisme. S’articuula amb 3 columnes de 2 files amb les línies  transparents, és a dir amb una opacitat del 100% i       amb imatges per cada membre amb una breu explicació a baix de cada imatge sobre el càrrec o funció dins del grup. Al capdamunt del body he redactat de manera breu i en punts com a l’inici                          l’introducció del equip investigador. Cada membre és troba a dintre de unes w3-card i amb opacitat si passem amb el cursor per damunt.  
  - Projectes: Text de color negre menys els links dels projectes anteriors, que els hi resaltat per tal de donar i captar visibilitat. Aquest apartat s’estrctura amb 3 subapartats (Projectes anteriors, projectes     actuals i projectes futurs). Pel que fa els projectes anteriors primer he posat una línia d’explicació i després una taula per els 3 projectes realitzats amb un link que t’emporta a aquests projectes, época       de realització del projecte i els membres que han realitzat el projecte concret. El  projecte en curs, he  optat per ficar un llistat o enumeració amb punts
  - Mapa:Trobem el títol de mapa de localització dels projectes seguint el model h3 dels altres apartats més al mapa en quüestió de localització dels projectes. 
  - Formulari de Contacte: En aquest apartat trobem el titol (h3) i el formulari centrat al mig de la pàgina. L’he configurat de manera que resulti obligatori els camps menys el missatge. 


## Web responsiva
Per tal d’ajudar i facilitar la comprensió en totes les pantalles s’ha aplicat un mètode responsiu que ja venia donat al w3Css template i no he aplicat ningún més, no obstant hagués estat convenient fer-ne un manual per tal de que s'ajustin millor els apartats. 

## Cartografia
Per l’elaboració de la cartografia s’ha descarregat el complement de Qgis2web de l’aplicació QGIS, que antoriorment ja he dit les versions respectives. 
1. Primer de tot hem creat un geopackage del projecte.
2. Ficar un mapa de fons de Open Street Maps i imatge satel·lit de fons (ESRI)
3. Digitalització dels punts als respectius municipis dels projectes amb una taula d’atributs, que conté: Nom Municipi, Projecte, Estat i els membres realitzadors del projecte
4. Canvi de Simbologia per punts de localització amb marcadors SVG de un llibre que és lo més paregut a un projecte o docuemnt. 
5. Aquesta taula d’atributs s’ha integrat al mapa, mitjançant pop-ups. Per la realització del mapa, s’ha implantat un zoom de +/-; mesurament de distàncies, eines de busca i una activació i/o desactivació de         capes i mapa de fons. 
6. Exportar el mapa amb la biblioteca Leaflet a la carpeta de la pàgina web.
7. Al Visual Studio Code, s'ha carregat i s'ha posat la relació del mapa


## Dificultats/millores
Dificultats: 

1. Anteriorment a l'assignatura mai he treballat amb ninguna cosa relacionada amb programació llavors al començar m'ha costat adpatar-m'hi al Visual Studio Code,Github, CSS, HTML i Java Script.
2. Sòc una persona desdendraçada amb carpetes i fitxers de l'ordenador i m'ha costat manejar el Visual Studio Code amb els diferents apartats.
3. Al ser un novat amb la programació hi havia coses que m'hagues agradat fer i no he pogut perquè els meus coneixemnts de programació són molt bàsics.

Millores: 
1. Principalment, crec que és podria millorar el disseny general de la pàgina web
2. Millorar o crear un mètode responsiu manual per tal de que s'ajustin alguns apartats com el mapa, membres, footer
3. Crear un efecte d'hamburguesa als apartats de la pàgina web del Header
5. En resum, és podria millorar tota la pàgina web en criteris generals. 
