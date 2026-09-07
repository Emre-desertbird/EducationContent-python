### @explicitHints true

# Aufgabe 2 – Steine aus dem Weg räumen

```python
agent.destroy(FORWARD)
agent.place(RIGHT)
agent.collect_all()
agent.move(FORWARD, 5)
agent.till(BACK)
for i in range(4):
      pass
if agent.inspect(AgentInspection.BLOCK, FORWARD) == GRASS:
    pass
else: 
    pass
```

## Schritt 1
**Teil 1:** Lass den Agenten vorwärtsgehen und dabei jeden **Steinblock** auf seinem Weg abbauen und einsammeln.
### ~ tutorialhint
Mit dieser Bedingung prüfst du den Blocktyp. Ersetze `DIRECTION` durch die gewünschte Richtung und `BLOCK_TYPE` durch den gesuchten Blocktyp:
```python
agent.inspect(AgentInspection.BLOCK, DIRECTION) == BLOCK_TYPE
```

## Schritt 2
**Teil 2:** Ergänze deinen Code so, dass der Agent auch **Grasblöcke** bearbeitet und dort Setzlinge pflanzt.
### ~ tutorialhint
Mit dieser Bedingung prüfst du den Blocktyp. Ersetze `DIRECTION` durch die gewünschte Richtung und `BLOCK_TYPE` durch den gesuchten Blocktyp:
```python
agent.inspect(AgentInspection.BLOCK, DIRECTION) == BLOCK_TYPE
```

```template
// Schreibe hier deine Funktionen.
// Beschreibe hier in einem Kommentar, was die folgende Funktion macht. | Teil 1
// Definiere Funktion 1. | Teil 1
// Lass den Agenten den Block vor sich abbauen. | Teil 1
    agent.move(FORWARD, 1)
// Beschreibe hier in einem Kommentar, was die folgende Funktion macht. | Teil 2
// Definiere Funktion 2. | Teil 2
// Lass den Agenten vorwärtsgehen. | Teil 2
// Lass den Agenten den Boden hinter sich bearbeiten. | Teil 2
// Lass den Agenten hinter sich einen Setzling pflanzen. | Teil 2
// Ersetze die folgenden Hinweise durch deinen Code.
// Ergänze eine for-Schleife mit 12 Wiederholungen. | Teil 1
// Ergänze eine if-else-Abfrage, die mit agent.inspect() auf STONE prüft. | Teil 1
// Rufe die Funktion zum Entfernen von Steinen auf. | Teil 1
// Ergänze eine elif-Bedingung, die mit agent.inspect() auf GRASS prüft. | Teil 2
// Rufe die Funktion zum Pflanzen von Bäumen auf. | Teil 2
// Ergänze den else-Zweig. | Teil 1
// Lass den Agenten vorwärtsgehen. | Teil 1
```
