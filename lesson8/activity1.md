### @explicitHints true

# Aufgabe 1 – Eine Reihe bepflanzen

```python
agent.till(RIGHT)
agent.move(FORWARD, 5)
agent.set_slot(1)
```

## Schritt 1
**Teil 1:** Lass den Agenten vorwärtsgehen, die **Grasblöcke (grass block) links von sich** bearbeiten und dort Setzlinge (sapling) pflanzen. Fasse die Befehle zum Pflanzen in einer **Funktion** zusammen. Das ist ein benannter Ablauf, den du mehrfach aufrufen kannst. So sieht eine Funktion grundsätzlich aus; im Beispiel wird der Boden rechts bearbeitet:
```python
def function_name():
    agent.till(RIGHT)
```

### ~ tutorialhint 
Beschreibe in einem kurzen Kommentar, was deine Funktion macht. Ein Python-Kommentar beginnt mit `#`.

## Schritt 2
**Teil 2:** Ergänze deinen Code so, dass der Agent jeden Setzling **sechsmal** düngt.
### ~ tutorialhint 
Der Dünger liegt im **zweiten Inventarfach** des Agenten. Mit `agent.set_slot()` wechselst du zwischen dem **ersten** und **zweiten** Fach.

```template
// Schreibe hier deine Funktionen.
// Beschreibe hier in einem Kommentar, was die folgende Funktion macht. | Teil 1
// Definiere deine Funktion. | Teil 1
// Wähle Inventarfach 1 des Agenten aus. | Teil 2
// Lass den Agenten den Boden links von sich bearbeiten. | Teil 1
// Lass den Agenten links von sich einen Setzling pflanzen. | Teil 1
// Wähle Inventarfach 2 des Agenten aus. | Teil 2
// Lass den Agenten den Setzling links von sich düngen. | Teil 2
// Lass den Agenten den Setzling links von sich düngen. | Teil 2
// Lass den Agenten den Setzling links von sich düngen. | Teil 2
// Lass den Agenten den Setzling links von sich düngen. | Teil 2
// Lass den Agenten den Setzling links von sich düngen. | Teil 2
// Lass den Agenten den Setzling links von sich düngen. | Teil 2
// Ersetze die folgenden Hinweise durch deinen Code.
agent.move(FORWARD, 1)
// Rufe deine Funktion auf. | Teil 1
// Lass den Agenten vorwärtsgehen. | Teil 1
// Rufe deine Funktion auf. | Teil 1
// Lass den Agenten vorwärtsgehen. | Teil 1
// Rufe deine Funktion auf. | Teil 1
```
