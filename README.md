### Aufgabe: Bewegter Smiley aus geometrischen Formen

In dieser Aufgabe bauen wir einen Smiley aus verschiedenen geometrische Objekten und bewegen ihn anschließend.
Blockly2Java stellt uns dafür schon einige Klasse mit Formen bereit. Schau dafür einfach links in den Grafik-Kategorien nach.

Die Main-Methode enthält bereits etwas Code, damit du deine Änderungen direkt siehst, wenn du startest.

---

[task][Strukturtests]()
Hier siehst du, ob du schon alle Methodenköpfe und Attribute richtig deklariert hast. Manches ist bereits in der Vorlage fertig, anderes machst du erst später.

(Das Klassendiagramm gibt es nur auf Artemis.)


---


### Smiley Konstruktor erstellen
[task][Konstruktor]()

- Speichere im Konstruktor zunächst die Startwerte für die beiden Geschwindigkeiten: jeweils 10
- Erstelle einen Smiley aus einem Kreis als Kopf, zwei kleinen Kreisen als Augen (`augeL`, `augeR`) und einer Ellipse als Mund.
- Die Positionsangaben beziehen sich immer auf den Mittelpunkt der jeweiligen Form. Die Gesamtposition wird als Parameter übergeben.
- Damit es auch wie ein Gesicht aussieht ist wichtig, dass der Mund mittig und unterhalb der Kopfmitte positioniert ist; die Augen sollen überhalb der Mitte sein und insgeamt symmetrisch am Kopf sein. *Tipp:* Die Mathe-Blöcke helfen dir dabei.
- Optional darfst natürlich noch weitere Objekte, wie Hut, Ohren etc. hinzufügen; Farben anpassen usw.


### Alles Bewegen
[task][Bewegen]()
Zum Bewegen wird die Methode `bewegen()` aufgerufen (was eine Überraschung) und Werte für die Veränderung von x- und y-Koordinate übergeben.
- Programmiere die Methode so, dass alle in Referenz-Attributen gespeicherten Formen, anhand dieser Werte bewegt werden. *Tipp:* Es gibt extra einen bewegen Block für geometrische Objekte.

---


### Rausgeflogen
[task][RandErreicht]()
Um herauszufinden, ob der Smiley die Welt verlässt, schreiben wir die Methode `randErreicht()`. Sie gibt einen Wahrheitswert zurück, ob die Mitte des Smileys den Rand der Welt erreicht hat.
- *Tipp*: Die Blöcke aus der Kategorie 'Getter' helfen dir hier.



### Rumfliegen
[task][Rumfliegen]()
Die Methode rumfliegen soll dafür sorgen, dass ein Smiley, der aus der Welt fliegt, umdreht und wieder zurückkommt.
- Programmiere die Methode dafür so, dass überprüft wird, ob der Smiley den Rand erreicht hat (*Tipp:* dafür hast du eben eine Methode geschrieben) und anschließend entschieden wird, ob die Geschwindigkeit verändert werden muss, bevor `bewegen()` aufgerufen wird.

*Noch ein Tipp:* Der einfachste Weg, die Richtung so zu ändern ist, das Vorzeichen der beiden Geschwindigkeiten zu ändern und den Betrag gleich zu lassen.


