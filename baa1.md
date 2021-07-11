## <img src="https://microbit.eeducation.at/images/thumb/c/c8/Icon_story.png/30px-Icon_story.png" width="30" alt="Icon" /> Den Zufall kann man vielleicht auch berechnen ...


Maria behauptet: Wenn man eine Münze oft genug wirft, dann kommen immer
gleich viele Kopf- und Zahlergebnisse.

Das würde bedeuten: Wirft man 100-mal, dann kommen in der Gesamtrechnung
immer 50 Kopf- und 50 Zahlergebnisse?

-   Ist das exakt immer so?
-   Ist das meistens so?
-   Könnte es auch 10 zu 90 ausgehen?

Am besten du testest einmal mit einigen Würfen einer Münze – versuche
einmal 10 Würfe: Lege dir eine Tabelle an, in die du die Ergebnisse
einträgst.

<img src="https://microbit.eeducation.at/images/e/ec/Tabelle_zufall1.jpg" width="575"/>

## <img src="https://microbit.eeducation.at/images/thumb/7/7e/Icon_gluehbirne.png/30px-Icon_gluehbirne.png" width="30" alt="Icon" /></a> Aufgabenstellung</span>

Mit dem BBC micro:bit kannst du dies noch bequemer testen – du benützt
den Zufallsgenerator des micro:bit. Entwickle ein Programm, mit dem man
das Werfen der Münzen simulieren kann. Der Vorteil des Computers, sehr
viele Würfe zu produzieren, sollte dabei ebenfalls zum Tragen kommen.

-   Das Schütteln des micro:bit sollte den Zufallsgenerator aufrufen:
    Dieser soll Kopf oder Zahl produzieren.
-   Taste A sollte die Anzahl der "Kopfwürfe" darstellen
-   Taste B sollte die Anzahl der "Zahlwürfe" darstellen
-   Taste A+B sollten die Gesamtanzahl der Versuche darstellen
-   Neustart mit "Reset"-Taste (Erweiterung)


## <span id="Tipps_und_Hilfestellungen" class="mw-headline"><a href="https://microbit.eeducation.at/wiki/Datei:Icon_hilfe.png" class="image" title="Icon"><img src="https://microbit.eeducation.at/images/thumb/3/3d/Icon_hilfe.png/30px-Icon_hilfe.png" srcset="https://microbit.eeducation.at/images/thumb/3/3d/Icon_hilfe.png/30px-Icon_hilfe.png 1.5x, /images/thumb/3/3d/Icon_hilfe.png/40px-Icon_hilfe.png 2x" width="30" alt="Icon" /></a> Tipps und Hilfestellungen</span>

### <span id="Erforderliche_Programmierbl.C3.B6cke" class="mw-headline">Erforderliche Programmierblöcke</span>

#### <span id="Ziel" class="mw-headline">Ziel</span>

-   Der Zufallsgenerator sollte 2 Zustände darstellen: wahr oder falsch
-   Diese Zustände entsprechen den 2 Möglichkeiten beim Münzwurf
-   Es sollte jeweils die Anzahl der Treffer für "wahr" und für "falsch"
    gezählt werden.

#### <span id="Vereinbarung" class="mw-headline">Vereinbarung</span>

-   "**W**ahr bedeutet Kopf" und "Falsch bedeutet **Z**ahl"

<a href="https://microbit.eeducation.at/wiki/Datei:Kopf.png" class="image"><img src="https://microbit.eeducation.at/images/thumb/8/83/Kopf.png/200px-Kopf.png" srcset="https://microbit.eeducation.at/images/thumb/8/83/Kopf.png/300px-Kopf.png 1.5x, /images/8/83/Kopf.png 2x" width="200" height="164" alt="Kopf.png" /></a>
...
<a href="https://microbit.eeducation.at/wiki/Datei:Zahl.png" class="image"><img src="https://microbit.eeducation.at/images/thumb/d/dd/Zahl.png/200px-Zahl.png" srcset="https://microbit.eeducation.at/images/thumb/d/dd/Zahl.png/300px-Zahl.png 1.5x, /images/d/dd/Zahl.png 2x" width="200" height="164" alt="Zahl.png" /></a>

#### <span id="Bl.C3.B6cke" class="mw-headline">Blöcke</span>

-   Anstelle des Münzwurfs sollte der Zufallsgenerator "wahr" oder
    "falsch" liefern <a href="#" class="spoilerLink">Block</a>


-   Der Zufallsgenerator sollte durch Schütteln des micro:bit aufgerufen
    werden <a href="#" class="spoilerLink">Block</a>

-   Je nach Bedingung "wahr" oder "falsch" sollten verschiedene Aktionen
    stattfinden <a href="#" class="spoilerLink">Block</a>


-   Bestimmte Tastenereignisse für Taste A, B und A+B - müssen Daten
    anzeigen <a href="#" class="spoilerLink">Block</a>

<div id="MCMAAZMUAGMEJVFHKWKZ" class="spoiler" style="display: none;">



<img src="https://microbit.eeducation.at/images/7/7c/Taste_a.png" class="thumbborder" width="600" />
<img src="https://microbit.eeducation.at/images/b/b9/Bild_20180513_004039.png" class="thumbborder" width="632" />
<img src="https://microbit.eeducation.at/images/0/0a/Bild_20180513_004129.png" class="thumbborder" width="670" />



</div>

-   Daten müssen angezeigt werden
    <a href="#" class="spoilerLink">Block</a>

<div id="GPEAYBQVYXQGANWHKBOC" class="spoiler" style="display: none;">

<div class="mw-parser-output">

<a href="https://microbit.eeducation.at/wiki/Datei:Zeige_nr.png" class="image"><img src="https://microbit.eeducation.at/images/0/0b/Zeige_nr.png" class="thumbborder" width="399" height="99" alt="Zeige nr.png" /></a>

</div>

</div>

-   Bei Programmstart durchzuführen
    <a href="#" class="spoilerLink">Block</a>

<div id="UBGJNLERJZNCNIQHLTDC" class="spoiler" style="display: none;">

<div class="mw-parser-output">

</div>

</div>

-   Variablen müssen angelegt und initialisiert werden
    <a href="#" class="spoilerLink">Block</a>

<div id="UYCXCTAEGMFPCVDUWOTG" class="spoiler" style="display: none;">

<div class="mw-parser-output">

</div>

</div>

-   Variablen müssen hochgezählt werden
    <a href="#" class="spoilerLink">Block</a>

<div id="LSNWQQNGBMGPZSSWFGWP" class="spoiler" style="display: none;">

<div class="mw-parser-output">

<a href="https://microbit.eeducation.at/wiki/Datei:Add_var.png" class="image"><img src="https://microbit.eeducation.at/images/f/fe/Add_var.png" class="thumbborder" width="517" height="166" alt="Add var.png" /></a>

</div>

</div>

-   Variablen müssen addiert werden
    <a href="#" class="spoilerLink">Block</a>

<div id="JDJFWLHIUYQTCASRUKTM" class="spoiler" style="display: none;">

<div class="mw-parser-output">

<a href="https://microbit.eeducation.at/wiki/Datei:Op_add.png" class="image"><img src="https://microbit.eeducation.at/images/7/78/Op_add.png" class="thumbborder" width="311" height="87" alt="Op add.png" /></a>

</div>

</div>

  

### <span id="Eckpfeiler_zur_Umsetzung" class="mw-headline">Eckpfeiler zur Umsetzung</span>

-   Programmiere den micro:bit-Zufallsgenerator so, dass durch Schütteln
    ein Wert "wahr" oder "falsch" ermittelt wird (= Kopf oder Zahl)
-   Wenn Taster "A" gedrückt wird, soll die Anzahl Kopfwürfe gezeigt
    werden
-   Wenn Taster "B" gedrückt wird, soll die Anzahl Zahlwürfe gezeigt
    werden
-   Wenn Taster "A+B" gedrückt werden, soll die Summe der Würfe
    dargestellt werden
-   Zufallswerte erhält man aus dem Menü Mathematik "Wähle zufälligen
    Wahr- und Falsch-Wert"
-   Wird Wahr ermittelt, so soll der Buchstabe "K" für Kopf erscheinen,
    andernfalls "Z" für Zahl.
-   Hier benötigt man die logische Verzweigung "Wenn ... dann ... sonst"
-   Das System sollte über zwei Variablen protokollieren, wie oft Kopf
    und wie oft Zahl geworfen wurde

### <span id="Schritt_f.C3.BCr_Schritt_zur_L.C3.B6sung" class="mw-headline">[Schritt für Schritt zur Lösung](/wiki/L%C3%B6sung_zufall "Lösung zufall")</span>

Hinweise zur Lösungsfindung und auch eine mögliche, komplette Lösung
findest du auf der [Lösungsseite zu diesem
Beispiel](/wiki/L%C3%B6sung_zufall "Lösung zufall")

## <span id="Pr.C3.A4sentation_und_Reflexion" class="mw-headline"><a href="https://microbit.eeducation.at/wiki/Datei:Presentation.png" class="image" title="Icon"><img src="https://microbit.eeducation.at/images/thumb/6/62/Presentation.png/20px-Presentation.png" srcset="https://microbit.eeducation.at/images/thumb/6/62/Presentation.png/30px-Presentation.png 1.5x, /images/thumb/6/62/Presentation.png/40px-Presentation.png 2x" width="30" alt="Icon" /></a> Präsentation und Reflexion</span>

### <span id="Allgemein" class="mw-headline">Allgemein</span>

-   Stelle dein Ergebnis vor! Was kann dein Produkt?
-   Was hat dir bei der Entwicklung deines Produkts gefallen?
-   Welche Schwierigkeiten hattest? Wie konntest du diese lösen?
-   Erläutere, wie du dein Produkt programmiert hast!
-   Was war bei dieser Aufgabe interessant für dich?

### <span id="Projektspezifisch" class="mw-headline">Projektspezifisch</span>

-   Welche Regeln wurden für Kopf und Zahl festgelegt? Welche andere
    Regeln für "Kopf oder Zahl" gäbe es noch?
-   Welche Diskussionspunkte ergaben sich während des Spiels?
-   Wo wird im Alltag der Wirtschaft mit Zufallsgenerator gearbeitet?
-   Wo braucht man bei einem Computerspiel den Zufallsgenerator.
-   Wo war bei diesem Beispiel der Vorteil des Computers zu sehen, wo
    war er eher ein Nachteil?
-   Bei welcher Erweiterungsstufe war es am schwierigsten, einen
    Programmcode zu erstellen.

## <span id="Weiterentwicklung" class="mw-headline"><a href="https://microbit.eeducation.at/wiki/Datei:Icon_plus.png" class="image" title="Icon"><img src="https://microbit.eeducation.at/images/thumb/0/0c/Icon_plus.png/30px-Icon_plus.png" srcset="https://microbit.eeducation.at/images/thumb/0/0c/Icon_plus.png/30px-Icon_plus.png 1.5x, /images/thumb/0/0c/Icon_plus.png/40px-Icon_plus.png 2x" width="30" alt="Icon" /></a> Weiterentwicklung</span>

-   Schleife: Du kannst mit einer Schleife nicht nur jeweils einen Wurf
    produzieren, sondern gleich 100 oder gar 1000 Würfe
-   Das bedeutet: Wenn einmal geschüttelt wird, werden gleich 1000 Würfe
    simuliert
-   Nütze dabei den Vorteil des Computers – er kann sehr schnell rechnen

### <span id="Noch_eine_Erweiterungsaufgabe" class="mw-headline">Noch eine Erweiterungsaufgabe</span>

**Analyse eines fremden Programmcodes:**  

-   Was stellt dieser Programmcode dar?

<a href="https://microbit.eeducation.at/wiki/Datei:Lesen_prg.png" class="image"><img src="https://microbit.eeducation.at/images/thumb/e/e4/Lesen_prg.png/800px-Lesen_prg.png" srcset="https://microbit.eeducation.at/images/e/e4/Lesen_prg.png 1.5x" width="800" height="831" alt="Lesen prg.png" /></a>

Dieses Programm ist hier aufrufbar:
<a href="https://makecode.microbit.org/#pub:_XdWYVaPe8WUk" class="external text">Link</a>

</div>

