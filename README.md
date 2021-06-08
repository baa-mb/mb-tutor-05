## ![Icon](https://microbit.eeducation.at/images/thumb/c/c8/Icon_story.png/40px-Icon_story.png "Icon") Den Zufall kann man vielleicht auch berechnen ...

![kopf\_zahl.jpg](https://microbit.eeducation.at/images/thumb/1/11/Kopf_zahl.jpg/600px-Kopf_zahl.jpg "Kopf_zahl.jpg")

Maria behauptet: Wenn man eine Münze oft genug wirft, dann kommen immer
gleich viele Kopf- und Zahlergebnisse.

Das würde bedeuten: Wirft man 100-mal, dann kommen in der Gesamtrechnung
immer 50 Kopf- und 50 Zahlergebnisse?

  - Ist das exakt immer so?
  - Ist das meistens so?
  - Könnte es auch 10 zu 90 ausgehen?

Am besten du testest einmal mit einigen Würfen einer Münze – versuche
einmal 10 Würfe: Lege dir eine Tabelle an, in die du die Ergebnisse
einträgst.

![50%](https://microbit.eeducation.at/images/e/ec/Tabelle_zufall1.jpg "50%")

## ![Icon](https://microbit.eeducation.at/images/thumb/7/7e/Icon_gluehbirne.png/40px-Icon_gluehbirne.png "Icon") Aufgabenstellung

Mit dem BBC micro:bit kannst du dies noch bequemer testen – du benützt
den Zufallsgenerator des micro:bit. Entwickle ein Programm, mit dem man
das Werfen der Münzen simulieren kann. Der Vorteil des Computers, sehr
viele Würfe zu produzieren, sollte dabei ebenfalls zum Tragen kommen.

  - Das Schütteln des micro:bit sollte den Zufallsgenerator aufrufen:
    Dieser soll Kopf oder Zahl produzieren.
  - Taste A sollte die Anzahl der "Kopfwürfe" darstellen
  - Taste B sollte die Anzahl der "Zahlwürfe" darstellen
  - Taste A+B sollten die Gesamtanzahl der Versuche darstellen
  - Neustart mit "Reset"-Taste (Erweiterung)

## ![Icon](https://microbit.eeducation.at/images/thumb/c/ce/Icon_material.png/40px-Icon_material.png "Icon") Materialien

  - Münze
  - Blatt Papier
  - micro:bit

## ![Icon](https://microbit.eeducation.at/images/thumb/8/8a/Icon_sanduhr.png/40px-Icon_sanduhr.png "Icon") Zeitaufwand

  - 1 Unterrichtseinheit

## ![Icon](Icon_puzzle3.png "Icon") Schwierigkeitsgrad

[30px|borderless](Datei:SternGelb.png "wikilink")[30px|borderless](Datei:SternLeer.png "wikilink")[30px|borderless](Datei:SternLeer.png "wikilink")

## ![Icon](Icon_brain.png "Icon") Kompetenzen

![IMG\_5764\_(1).png](IMG_5764_\(1\).png "IMG_5764_(1).png") Du solltest
bereits

  - einen Prozentanteil schätzen können
  - eine Wertetabelle anlegen und auswerten können

Beim Programmieren lernst bzw. übst du

  - [Variablen](Variablen "wikilink") zu verwenden
  - [Operatoren](Operatoren "wikilink") zu verwenden
  - den [Zufallsgenerator](Zufallsgenerator "wikilink") zu nutzen
  - [Bedingungen](Bedingungen "wikilink") zu verwenden

Bei dieser Aufgabe lernst du auch

  - ein NEUES Programm zu lesen und es zu interpretieren

## ![Icon](Icon_faecher.png "Icon") Unterrichtsfächer

  - Mathematik
  - Informatik
  - Deutsch

## ![Icon](Icon_hilfe.png "Icon") Tipps und Hilfestellungen

### Erforderliche Programmierblöcke

#### Ziel

  - Der Zufallsgenerator sollte 2 Zustände darstellen: wahr oder falsch
  - Diese Zustände entsprechen den 2 Möglichkeiten beim Münzwurf
  - Es sollte jeweils die Anzahl der Treffer für "wahr" und für "falsch"
    gezählt werden.

#### Vereinbarung

  - "**W**ahr bedeutet Kopf" und "Falsch bedeutet **Z**ahl"

[200px ](Datei:kopf.png "wikilink") ... [200px
](Datei:zahl.png "wikilink")

#### Blöcke

  - Anstelle des Münzwurfs sollte der Zufallsgenerator "wahr" oder
    "falsch" liefern <spoiler text="Block"> ![Zwei mögliche Zustände
    (wahr und falsch)?](Zufall_w_f.png
    "Zwei mögliche Zustände (wahr und falsch)?")</spoiler>
  - Der Zufallsgenerator sollte durch Schütteln des micro:bit aufgerufen
    werden <spoiler text="Block"> ![Zwei mögliche Zustände (wahr und
    falsch)?](Geschuettelt.png
    "Zwei mögliche Zustände (wahr und falsch)?")</spoiler>
  - Je nach Bedingung "wahr" oder "falsch" sollten verschiedene Aktionen
    stattfinden <spoiler text="Block"> ![Wenndann.png](Wenndann.png
    "Wenndann.png")</spoiler>
  - Bestimmte Tastenereignisse für Taste A, B und A+B - müssen Daten
    anzeigen <spoiler text="Block">![Taste\_a.png](Taste_a.png
    "Taste_a.png")
    ![Bild\_20180513\_004039.png](Bild_20180513_004039.png
    "Bild_20180513_004039.png")
    ![Bild\_20180513\_004129.png](Bild_20180513_004129.png
    "Bild_20180513_004129.png")</spoiler>
  - Daten müssen angezeigt werden
    <spoiler text="Block">![Zeige\_nr.png](Zeige_nr.png
    "Zeige_nr.png")</spoiler>
  - Bei Programmstart durchzuführen <spoiler text="Block">
    ![Start\_ereignis.png](Start_ereignis.png
    "Start_ereignis.png")</spoiler>
  - Variablen müssen angelegt und initialisiert werden
    <spoiler text="Block"> ![Beim\_start.png](Beim_start.png
    "Beim_start.png")</spoiler>
  - Variablen müssen hochgezählt werden
    <spoiler text="Block">![Add\_var.png](Add_var.png
    "Add_var.png")</spoiler>
  - Variablen müssen addiert werden
    <spoiler text="Block">![Op\_add.png](Op_add.png
    "Op_add.png")</spoiler>

### Eckpfeiler zur Umsetzung

  - Programmiere den micro:bit-Zufallsgenerator so, dass durch Schütteln
    ein Wert "wahr" oder "falsch" ermittelt wird (= Kopf oder Zahl)
  - Wenn Taster "A" gedrückt wird, soll die Anzahl Kopfwürfe gezeigt
    werden
  - Wenn Taster "B" gedrückt wird, soll die Anzahl Zahlwürfe gezeigt
    werden
  - Wenn Taster "A+B" gedrückt werden, soll die Summe der Würfe
    dargestellt werden
  - Zufallswerte erhält man aus dem Menü Mathematik "Wähle zufälligen
    Wahr- und Falsch-Wert"
  - Wird Wahr ermittelt, so soll der Buchstabe "K" für Kopf erscheinen,
    andernfalls "Z" für Zahl.
  - Hier benötigt man die logische Verzweigung "Wenn ... dann ... sonst"
  - Das System sollte über zwei Variablen protokollieren, wie oft Kopf
    und wie oft Zahl geworfen wurde

### [Schritt für Schritt zur Lösung](Lösung_zufall "wikilink")

  -   
    Hinweise zur Lösungsfindung und auch eine mögliche, komplette Lösung
    findest du auf der [Lösungsseite zu diesem
    Beispiel](Lösung_zufall "wikilink")

## ![Icon](presentation.png "Icon") Präsentation und Reflexion

### Allgemein

  - Stelle dein Ergebnis vor\! Was kann dein Produkt?
  - Was hat dir bei der Entwicklung deines Produkts gefallen?
  - Welche Schwierigkeiten hattest? Wie konntest du diese lösen?
  - Erläutere, wie du dein Produkt programmiert hast\!
  - Was war bei dieser Aufgabe interessant für dich?

### Projektspezifisch

  - Welche Regeln wurden für Kopf und Zahl festgelegt? Welche andere
    Regeln für "Kopf oder Zahl" gäbe es noch?
  - Welche Diskussionspunkte ergaben sich während des Spiels?
  - Wo wird im Alltag der Wirtschaft mit Zufallsgenerator gearbeitet?
  - Wo braucht man bei einem Computerspiel den Zufallsgenerator.
  - Wo war bei diesem Beispiel der Vorteil des Computers zu sehen, wo
    war er eher ein Nachteil?
  - Bei welcher Erweiterungsstufe war es am schwierigsten, einen
    Programmcode zu erstellen.

## ![Icon](icon_plus.png "Icon") Weiterentwicklung

  - Schleife: Du kannst mit einer Schleife nicht nur jeweils einen Wurf
    produzieren, sondern gleich 100 oder gar 1000 Würfe
  - Das bedeutet: Wenn einmal geschüttelt wird, werden gleich 1000 Würfe
    simuliert
  - Nütze dabei den Vorteil des Computers – er kann sehr schnell rechnen

### Noch eine Erweiterungsaufgabe

**Analyse eines fremden Programmcodes:**  

  - Was stellt dieser Programmcode dar?

![Lesen\_prg.png](Lesen_prg.png "Lesen_prg.png")

Dieses Programm ist hier aufrufbar:
[Link](https://makecode.microbit.org/#pub:_XdWYVaPe8WUk)
