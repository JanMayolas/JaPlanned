# Resum del canvi del nav

## Què s'ha fet

He deixat el menú lateral fixat a la part superior de la pàgina i l'he fet que ocupi tota l'alçada visible.

- El `nav` queda a la part superior esquerra amb `position: fixed`
- La mida és `width: 300px` i `height: 100vh`
- El contingut principal queda desplaçat cap a la dreta per no solapar-se

## 🧩 Dins del nav

He reubicat la icona i el títol perquè quedin dins del mateix bloc del menú lateral, en lloc d'estar fora.

- La icona i el nom de JaPlanned estan dins de `.nav-header`
- El títol i la icona es mantenen alineats horitzontalment
- Els botons de la dreta queden dins del mateix espai superior

## 🔧 Fitxers implicats

- `index.html`: estructura del nav i la capçalera
- `css/style.css`: estils del posicionament, mida i alineació

## 🎯 Resultat

Ara el nav té aquest aspecte:

- enganxat a dalt
- vertical i ample fix
- amb el logo i el títol dins del lateral
- sense deixar espai brut a la part superior

## 📌 Observació

Aquest canvi està pensat perquè el menú sigui una barra lateral clara i estable, i deixar el contingut principal amb marge a la dreta.
