### @explicitHints true
### @hideIteration true 
# Aufgabe 1 – Tiere zuordnen

```python
blocks.place()
mobs.spawn()
world(0, 0, 0)
```

## Schritt 1
Erstelle eine Liste namens `Tierliste`. Trage die Tiere in der Reihenfolge ein, in der du sie in der Spielwelt **von links nach rechts** siehst. Ergänze nach dem vorgegebenen `mobs.spawn()`-Befehl **vier weitere** solche Befehle. Mit ihnen lässt du Tiere an den angegebenen Positionen erscheinen. Die Schilder an den Gehegen helfen dir bei der Zuordnung.

Für die fünf Tiere brauchst du diese englischen Namen im Code:

- Kuh (cow): `COW`
- Schwein (pig): `PIG`
- Schaf (sheep): `SHEEP`
- Pferd (horse): `HORSE`
- Kaninchen (rabbit): `RABBIT`

Schreibe die Namen in deiner Liste **groß und ohne Anführungszeichen**. Sie stehen für die Tierarten, die Minecraft erscheinen lassen soll. Die Reihenfolge liest du in der Spielwelt ab.

### ~ tutorialhint 
Die Positionen in einer Liste heißen **Indizes**. Python zählt sie ab **0**: Das erste Tier hat den Index `0`, das zweite den Index `1` und so weiter.

```template 
position1 = world(-2, 40, -11)
position2 = world(-2, 40, -5)
position3 = world(-8, 40, -0)
position4 = world(-13, 40, -5)
position5 = world(-13, 40, -11)
// Ersetze die folgenden Hinweise durch deinen Code.

// Erstelle die Liste der Tiere.

mobs.spawn(Tierliste[0], position1)
// Lass das dritte Tier aus der Liste an der Position position2 erscheinen.
// Lass das fünfte Tier aus der Liste an der Position position3 erscheinen.
// Lass das zweite Tier aus der Liste an der Position position4 erscheinen.
// Lass das vierte Tier aus der Liste an der Position position5 erscheinen.
```
