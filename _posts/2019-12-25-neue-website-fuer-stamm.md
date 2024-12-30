---
title: Eine neue Website für den Stamm
feature_image:
feature_text: Eine Demo der Darstellungselemente für Artikel
excerpt: Zu Beginn des neuen Jahrzehnts bekommt der Stamm einen neuen Webauftritt denn Pfadfinder finden sich auch digital bestens zurecht.
tags:
---

Im Nachfolgenden werde ich die zentralen Elemente zur Gestaltung eines Blogartikels vorstellen.  
Die Gestaltung ist zur Wahrung eines einheitlichen Gesamtbildes und zur einfacheren Auslieferung an Browser eingeschränkt. Es sollte jedoch reichen, um eure Gedanken mit der Welt zu teilen.

Los geht's!

# Ein paar Beispiele für Überschriften

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

<small>Ein besonders kleines Element</small>

[Ein Link auf eine externe Seite mit Titel](https://www.neuried.de "Neuried Homepage")  
[Ein Link zu einer internen Seite ohne Titel]({% link stamm.md %})  
[Ein Link zu einem unserer Blogartikel]({% post_url 2019-12-25-neue-website-fuer-stamm %})

Duis aute irure dolor in [ein link](https://www.stamm-baeren.com) reprehenderit in ~~durchstreichen~~ esse cillum **bold text** dolore eu fugiat nulla pariatur. Excepteur span element sint occaecat cupidatat non proident, sunt _italicised text_ in culpa qui officia deserunt mollit anim id `Block text, für Code z.B.` est laborum.

Manche Kontrollzeichen wie \* müssen nach einem Backslash \\ stehen um dargestellt zu werden.

Für einen normalen Zeilen-  
umbruch sind mindestens zwei Leerzeichen und ein Absatz notwendig.

>Texte können auch eingeschoben
>bzw. besonders hervorgehoben werden.

Horizontale Trenner gibts auch:

***

### Listen

* An item
* An item
  - An item
  - An item
    1. Und so weiter ...
    2. ... und weiter
* An item

Tasklisten gehen auch:

- [x] 5x Bananen
- [ ] 2x Äpfel
  - [ ] 1x Boskop
  - [x] 1x Pink Lady
- [x] 1x Mango

### Tabellen

Das \|-Symbol trennt Spalten, \--Symbole (Dashes) die Zeilen.

| Tabellen        | sind          | cool  |
| --------------- |:-------------:| -----:|
| Spalte 3 ist    | rechts-orientiert | $1600 |
| Spalte 2 ist     | zentriert      |   $12 |
| **Text formatieren** | *geht auch*   |    $1 |

### Videos

Videos sind zu groß um direkt hochgeladen werden zu können und können daher nur verlinkt werden, vorzugsweise auf Youtube.

{% include video.html id="b4rTx6SnifQ" title="WSJ 2020" caption="Ein Video zum WSJ 2020" %}

### Bilder

Bilder können mit einer Beschreibung, einer Größenangabe und einer Positionierung (links, rechts, zentral) versehen werden:

{% include figure.html image="assets/images/Lilie.png" caption="relativ referenziertes Bild einer Lilie mit fixer Größe" width="300" height="500" %}

{% include figure.html image="assets/images/Kuscheltier-liegend.png" caption="Rechts ausgerichtetes Bild mit relativer Größe" position="right" width="50%" %}

{% include figure.html image="https://picsum.photos/1600/800?image=894" caption="extern referenziertes Bild" position="center"%}

### Noch Fragen?

Falls du noch Fragen hast oder weiter experimentieren möchtest, findest du hier eine [kurze](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) oder auch eine [ausführliche](https://kramdown.gettalong.org/quickref.html) Dokumentation.  
Ansonsten wende dich einfach an Pholen.
