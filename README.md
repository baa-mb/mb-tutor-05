
> Diese Seite bei [https://baa-mb.github.io/mb-tutor-05/](https://baa-mb.github.io/mb-tutor-05/) öffnen

Inhaltsverzeichnis
## Den Zufall kann man vielleicht auch berechnen ...
Maria behauptet: Wenn man eine Münze oft genug wirft, dann kommen immer gleich viele Kopf- und Zahlergebnisse.

Das würde bedeuten: Wirft man 100-mal, dann kommen in der Gesamtrechnung immer 50 Kopf- und 50 Zahlergebnisse?

Ist das exakt immer so?
Ist das meistens so?
Könnte es auch 10 zu 90 ausgehen?
Am besten du testest einmal mit einigen Würfen einer Münze – versuche einmal 10 Würfe: Lege dir eine Tabelle an, in die du die Ergebnisse einträgst.
![Münzen](https://microbit.eeducation.at/images/thumb/1/11/Kopf_zahl.jpg/600px-Kopf_zahl.jpg)
##	Aufgabenstellung
![SkizzeTabelle_zufall1](https://microbit.eeducation.at/images/e/ec/Tabelle_zufall1.jpg)
##	Materialien
##	Zeitaufwand
##	Schwierigkeitsgrad
##	Kompetenzen
##	Unterrichtsfächer
##	Tipps und Hilfestellungen
###	Erforderliche Programmierblöcke
####	Ziel
####	Vereinbarung
####	Blöcke
###	Eckpfeiler zur Umsetzung
###	Schritt für Schritt zur Lösung
##	Präsentation und Reflexion
###	Allgemein
###	Projektspezifisch
##	Weiterentwicklung
###	Noch eine Erweiterungsaufgabe

```
<h1>
dsasdfasdfa
</h1>
```

## Als Erweiterung verwenden Version 555
Dieses Repository kann als **Erweiterung** in MakeCode hinzugefügt werden. NEU
```block
basic.forever(function() {
        basic.showNumber(input.temperature())
        basic.pause(1000)
        basic.showString("alois bachinger")
    })

```

* öffne [https://makecode.microbit.org/](https://makecode.microbit.org/)
* klicke auf **Neues Projekt**
* klicke auf **Erweiterungen** unter dem Zahnrad-Menü
* nach **https://github.com/baa-mb/mb-tutor-04** suchen und importieren

## Dieses Projekt bearbeiten ![Build Status Abzeichen](https://github.com/baa-mb/mb-tutor-04/workflows/MakeCode/badge.svg)

Um dieses Repository in MakeCode zu bearbeiten.

* öffne [https://makecode.microbit.org/](https://makecode.microbit.org/)
* klicke auf **Importieren** und dann auf **Importiere URL**
* füge **https://github.com/baa-mb/mb-tutor-04** ein und klicke auf Importieren

## Blockvorschau

Dieses Bild zeigt den Blockcode vom letzten Commit im Master an.
Die Aktualisierung dieses Bildes kann einige Minuten dauern.

![Eine gerenderte Ansicht der Blöcke](https://github.com/baa-mb/mb-tutor-04/raw/master/.github/makecode/blocks.png)

#### Metadaten (verwendet für Suche, Rendering)

# Lernprogramm

## It's time to code! @showHint

Let's get real bright. We're going to make all the lights flash on your board!
During an interaction, the step description (all text before the first code block or image) is shown in the caption. If the paragraph length goes beyond the display length of caption, a "More" button appears in order to view the rest of the paragraph. It's best to keep the paragraph short enough to so all of it appears in the caption without requiring the user to click to see it all. If your instructions need more text, you can just create an additional step to split up the activity.
```block
    export function baa() {
        basic.showString("Alois")
        console.log("alois")
    }
``` 

```block
    basic.forever(function() {
        basic.showNumber(input.temperature())
        basic.pause(1000)
        basic.showString("alois")
    })

```
- one
- two
***
---
___

+++
===

--
**
__

xxxx

***
 ***
   ***

# foo
## foo
### foo
#### foo
##### foo
###### foo

#5 bolt

#hashtag


# foo *bar* \*baz\*

## Make a new variable @showdialog

Let's get real bright. We're going to make all the lights flash on your board!
During an interaction, the step description (all text before the first code block or image) is shown in the caption. If the paragraph length goes beyond the display 

```block
length of caption
```
, a "More" button appears in order to view the rest of the paragraph. It's best to keep the paragraph short enough to so all of it appears in the caption without requiring the user to click to see it all. If your instructions need more text, you can just create an additional s**te**p 



# Zweite Hauptüberschrift 


Mit diesem Kurs lernst du, wie du Microbit entdecken kannst!
During an interaction, the step description (all text before the first code block or image) is shown in the caption. If the paragraph length goes beyond the display length of caption, a "More" button appears in order to view the rest of the paragraph. It's best to keep the paragraph short enough to so all of it appears in the caption without requiring the user to click to see it all. If your instructions need more text, you can just create an additional step to split up the activity.
```block
    export function baa() {
        basic.showString("Alois")
        console.log("alois")
    }
``` 

![Hier muss ein Bild stehen](https://github.com/baa-mb/mb-tutor-04/raw/master/bilder/bild.png)

## Step 2
# Anleitung 

Sehr gut!xxxx

![Bild](https://github.com/baa-mb/mb-tutor-04/raw/master/bilder/b.png)

![Bildreferenzen richtig](https://github.com/baa-mb/mb-tutor-04/raw/master/bilder/w.png)

## Introduction @unplugged

Have the agent build a tower! Make a command to tell it how many levels to build.
![Agent building a tower](https://github.com/baa-mb/mb-tutor-04/raw/master/bilder/mb.png)



## Schritt Show the temperature

Get a ``||input:temperature||`` block and place it in the value slot of ``||basic:show number||``.

```block
    basic.forever(function() { 
        basic.showNumber(input.temperature())
        basic.pause(1000)
    })


    basic.forever(function() {
        basic.showNumber(input.temperature())
        basic.pause(1000)
        basic.showString("alois")
    })
```

* for PXT/microbit
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>

