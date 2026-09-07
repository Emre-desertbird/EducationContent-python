### @explicitHints true

# Aufgabe 3 – Eine Fläche voller Bäume

```python
agent.turn(RIGHT_TURN)
agent.place(RIGHT)
agent.move(FORWARD, 5)
agent.inspect(AgentInspection.BLOCK, FORWARD) 
agent.till(BACK)
for i in range(4):
      pass
if True: 
    pass
else: 
    pass
elif:
    pass
```

## Schritt 1
**Teil 1:** Schreibe drei Funktionen: eine für den Weg **vorwärts durch eine Reihe**, eine für den Wechsel in die nächste Reihe mit **Linksdrehungen** und eine mit **Rechtsdrehungen**. Rufe sie in einer `for`-Schleife auf. So soll der Agent Reihe für Reihe über jeden Block der Fläche laufen, bis er den Goldblock erreicht.

## Schritt 2
**Teil 2:** Erweitere deinen Code: Der Agent soll die Grasblöcke auf seinem Weg bearbeiten und jeweils einen Setzling pflanzen. Ergänze dazu in der Funktion für das Vorwärtsgehen eine `if`-`else`-Abfrage, die auf Grasblöcke prüft.

```template
// Schreibe hier deine Funktionen.
// Passe den Kommentar an die erweiterte Funktion an. | Teil 2
// Beschreibe hier in einem Kommentar, was die folgende Funktion macht. | Teil 1
// Definiere Funktion 1. | Teil 1
// Ergänze eine for-Schleife (Schleife 1) mit 9 Wiederholungen. | Teil 1
// Ergänze eine if-else-Abfrage mit agent.inspect(). | Teil 2
// Rufe die Funktion zum Pflanzen von Setzlingen auf. | Teil 2
// Setze den folgenden Befehl in den else-Zweig. | Teil 2
// Lass den Agenten vorwärtsgehen. | Teil 1
// Ende der Schleife 1.
// Beschreibe hier in einem Kommentar, was die folgende Funktion macht. | Teil 1
// Definiere Funktion 2. | Teil 1
// Lass den Agenten sich nach rechts drehen. | Teil 1
// Lass den Agenten vorwärtsgehen. | Teil 1
// Lass den Agenten sich nach rechts drehen. | Teil 1
// Beschreibe hier in einem Kommentar, was die folgende Funktion macht. | Teil 1
// Definiere Funktion 3. | Teil 1
// Lass den Agenten sich nach links drehen. | Teil 1
    agent.move(FORWARD, 1)
// Lass den Agenten sich nach links drehen. | Teil 1
// Beschreibe hier in einem Kommentar, was die folgende Funktion macht. | Teil 2
// Definiere Funktion 4. | Teil 2
// Lass den Agenten vorwärtsgehen. | Teil 2
// Lass den Agenten den Boden hinter sich bearbeiten. | Teil 2
// Lass den Agenten hinter sich einen Setzling pflanzen. | Teil 2
// Ersetze die folgenden Hinweise durch deinen Code.
// Ergänze eine for-Schleife (Schleife 2) mit 4 Wiederholungen. | Teil 1
// Rufe die Funktion für das Vorwärtsgehen auf. | Teil 1
// Rufe die Funktion für den Reihenwechsel nach rechts auf. | Teil 1
// Rufe die Funktion für das Vorwärtsgehen auf. | Teil 1
// Rufe die Funktion für den Reihenwechsel nach links auf. | Teil 1
```
