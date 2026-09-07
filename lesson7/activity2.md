### @explicitHints true
### @hideIteration true 
# Aufgabe 2 – Eine Mauer gegen das Feuer

```python
agent.turn(LEFT_TURN)
agent.place(RIGHT)
agent.move(FORWARD, 5)
agent.detect(AgentDetection.BLOCK, FORWARD) 
while True:
      pass
```

## Schritt 1
Lass den Agenten vorwärtsgehen, solange Redstone-Staub vor ihm liegt. Dabei soll er **links von sich eine einen Block hohe Mauer** bauen. Wenn das Gelände ansteigt, soll er nach oben gehen und die Mauer auf der neuen Höhe fortsetzen.

```template
// Ersetze die folgenden Hinweise durch deinen Code.
// Ergänze eine while-Schleife (Schleife 1) mit agent.detect() zur Prüfung auf Redstone-Staub.
// Ergänze eine while-Schleife (Schleife 2) mit agent.detect() zur Prüfung auf einen Block.
agent.place(LEFT)
// Lass den Agenten nach oben gehen.
// Lass den Agenten links von sich einen Block setzen.
// Lass den Agenten vorwärtsgehen.
// Ende der while-Schleife 2.
// Lass den Agenten links von sich einen Block setzen.
// Lass den Agenten vorwärtsgehen.
// Ende der while-Schleife 1.
```