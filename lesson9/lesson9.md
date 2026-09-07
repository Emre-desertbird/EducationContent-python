### @explicitHints true
# Goldblöcke im Visier

```python
pos(0, 0, 0)
mobs.spawn(FIREWORKS_ROCKET, agent.get_position())
blocks.place()
blocks.test_for_block(GRASS, pos(0, 0, 0))
positions.add(pos(0, 0, 0), pos(0, 0, 0))
pos(0, 0, 0)
loops.pause(100)
agent.move(FORWARD, 5)
agent.get_position()
gameplay.title(mobs.target(NEAREST_PLAYER), "Glückwunsch!", "Du hast gewonnen!")
mobs.target(NEAREST_PLAYER)
player.say("Hallo")
if True: 
    pass
else: 
    pass
elif:
    pass
while True:
    pass
```

## Schritt 1
**Aufgabe 1 – Die Spielsteuerung:**
Die Steuerung hat zwei farbige Felder aus hellblauem Beton (light blue concrete) und rotem Beton (red concrete): **Blau** bewegt den Agenten nach **links**, **Rot** nach **rechts**. Schreibe den Code so, dass der Agent in die passende Richtung geht, wenn du auf einem der Felder stehst. Mit diesem Befehl prüfst du, ob an einer bestimmten Position ein bestimmter Block liegt. Ersetze `BLOCK_NAME` durch den gesuchten Blocktyp:
```python
blocks.test_for_block(BLOCK_NAME, pos(0, 0, 0))
```

### ~ tutorialhint
Eine `while`-Schleife mit der Bedingung `True` läuft immer weiter. `True` bedeutet „wahr“. Lass den bereits vorgegebenen Code im Codefenster stehen.

## Schritt 2
**Aufgabe 2 – Goldblöcke (gold block) treffen, Teil 1:**
Schreibe eine weitere Funktion, mit der der Agent die Goldblöcke über sich abschießt. Lass dafür mit `mobs.spawn()` eine Feuerwerksrakete (`FIREWORKS_ROCKET`) erscheinen. Ersetze jeden getroffenen Goldblock durch Luft (`AIR`), damit er verschwindet. Mit `agent.get_position()` erhältst du die Position des Agenten. Mit `positions.add()` kannst du davon ausgehend die Position des Goldblocks berechnen. Zusammen sehen die Befehle so aus; passe die Höhe in `pos()` an:
```python 
positions.add(agent.get_position(), pos(0, 0, 0))
```
## Schritt 3
**Teil 2:** Ergänze eine `elif`-Bedingung, damit der Agent auch die zweite Reihe von Goldblöcken abschießen kann.

## Schritt 4
**Aufgabe 3 – Punkte zählen:**
Die vorgegebene Variable `punktestand` speichert den Punktestand. Erhöhe sie für jeden getroffenen Goldblock um **1**. Ändere die Bedingung der `while`-Schleife so, dass sie nur läuft, solange `punktestand` **kleiner oder gleich 15** ist. Zeige mit `gameplay.title()` am Anfang und am Ende des Spiels einen passenden Text an. Damit du `punktestand` innerhalb deiner Funktion verändern kannst, füge dort diese Zeile ein:
```
global punktestand
```

### ~ tutorialhint
**`<=`** bedeutet **„kleiner oder gleich“**. Mit `global punktestand` bezieht sich die Funktion auf die Variable `punktestand`, die außerhalb der Funktion angelegt wurde.


```template
// Schreibe hier deine Funktionen.
// Definiere Funktion 2. | Aufgabe 2 Teil 1
// Kennzeichne punktestand mit global als globale Variable. | Aufgabe 3
// Ergänze eine if-Bedingung: Prüfe den Block 2 Blöcke über dem Agenten. | Aufgabe 2 Teil 1
// Lass an der Position des Agenten eine Feuerwerksrakete erscheinen. | Aufgabe 2 Teil 1
// Warte 100 Millisekunden. | Aufgabe 2 Teil 1
// Ersetze den Block 2 Blöcke über dem Agenten durch AIR (Luft). | Aufgabe 2 Teil 1
// Erhöhe punktestand um 1. | Aufgabe 3
// Ergänze eine elif-Bedingung: Prüfe den Block 3 Blöcke über dem Agenten. | Aufgabe 2 Teil 2
// Lass an der Position des Agenten eine Feuerwerksrakete erscheinen. | Aufgabe 2 Teil 2
// Warte 100 Millisekunden. | Aufgabe 2 Teil 2
// Ersetze den Block 3 Blöcke über dem Agenten durch AIR (Luft). | Aufgabe 2 Teil 2
// Erhöhe punktestand um 1. | Aufgabe 3
// Beschreibe hier in einem Kommentar, was die folgende Funktion macht. | Aufgabe 1
// Definiere Funktion. | Aufgabe 1
// Ergänze eine if-Bedingung, die mit blocks.test_for_block() auf LIGHT_BLUE_CONCRETE prüft. | Aufgabe 1
// Lass den Agenten nach links gehen. | Aufgabe 1
// Ergänze eine elif-Bedingung, die mit blocks.test_for_block() auf RED_CONCRETE prüft. | Aufgabe 1
// Lass den Agenten nach rechts gehen. | Aufgabe 1
// Ersetze die folgenden Hinweise durch deinen Code.
punktestand = 0
// Zeige mit gameplay.title() einen Text zum Spielstart an. | Aufgabe 3
// Lass die while-Schleife nur laufen, solange punktestand <= 15 gilt. | Aufgabe 3
// Ergänze eine while-Schleife mit der Bedingung True. | Aufgabe 1
// Rufe Funktion auf. | Aufgabe 1
// Rufe Funktion 2 auf. | Aufgabe 2 Teil 1
// Zeige mit gameplay.title() einen Text zum Spielende an. | Aufgabe 3
// Lass an der Position des Agenten einen Blitz einschlagen. | Aufgabe 3
if punktestand > 15
player.execute("scoreboard players set @p score 15")
```
