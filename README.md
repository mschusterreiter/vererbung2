
# Übung 24 - Vererbung


## 1. Aufgabe

Setzen Sie folgendes Klassendiagramm um:

<p align="center">
  <img src="/assets/images/UML1.png" alt="Bildbeschreibung" />
</p>

**Beschreibung der `GeometrischeForm`-Klasse:**

- Eigenschaften: 
	- Im Konstruktor müssen die `set`-Methoden aufgerufen werden. 
	- Prüfen Sie alle Eigenschaften auf sinnvolle Werte. 

- Methoden: 
	- `anzeigen()`: Gib alle Eigenschaften schön formatiert aus. 
	- `berechneFlaeche()`: Ist eine abstrakte Methode.
	- `drehen()`: Gibt folgenden Satz aus: "Die Form wird gedreht."


**Beschreibung der `FormMitSeiten`-Klasse:**

- Methoden: 
	- `getAnzahlSeiten()`: Ist eine abstrakte Methode.


**Beschreibung der `Rechteck`-Klasse:**

- Eigenschaften: 
	- Im Konstruktor müssen die `set`-Methoden aufgerufen werden. 
	- Prüfen Sie alle Eigenschaften auf sinnvolle Werte. 

- Methoden: 
	- `istQuadrat()`: Prüft, ob das Rechteck ein Quadrat ist. 
	- Programmieren Sie auch alle Methode, welche vererbt oder implementiert werden. Was die Methoden machen sollen, ist selbsterklärend. Wenn nicht, fragen Sie nach.

**Beschreibung der `Kreis`-Klasse:**

- Eigenschaften: 
	- Im Konstruktor müssen die `set`-Methoden aufgerufen werden. 
	- Prüfen Sie alle Eigenschaften auf sinnvolle Werte. 

- Methoden: 
	- `berechneDurchmesser()`: Berechnet den Durchmesser des Kreises.
	- Programmieren Sie auch alle Methode, welche vererbt oder implementiert werden. Was die Methoden machen sollen, ist selbsterklärend. Wenn nicht, fragen Sie nach. (`getSpezielleEigenschaft()` soll den Satz „Dieses Dreieck hat eine Höhe von … .“ ausgeben)

**Beschreibung der `Dreieck`-Klasse:**

- Eigenschaften: 
	- Im Konstruktor müssen die `set`-Methoden aufgerufen werden. 
	- Prüfen Sie alle Eigenschaften auf sinnvolle Werte. 

- Methoden: 
	- Programmieren Sie auch alle Methode, welche vererbt oder implementiert werden. Was die Methoden machen sollen, ist selbsterklärend. Wenn nicht, fragen Sie nach.

**Achtung:** Die Interfaces wurden nicht näher beschrieben. Vergessen Sie nicht, diese lt. UML zu implementieren. 


Schreiben Sie außerdem eine Main-Klasse mit einer `main`-Methode und einer `zeigeFormInformation(GeometrischeForm form)`-Methode. Diese Methode soll zuerst die Methode `form.anzeigen()` aufrufen. Danach soll, je nachdem ob form eine Instanz von `FormMitUmfang` oder `SpezielleFormEigenschaften` ist, der Umfang bzw. die spezielle Eigenschaft ausgegeben werden. Schreiben Sie außerdem einige Testfälle und testen Sie alle Methoden aus.
