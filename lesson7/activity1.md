### @explicitHints true

# Aufgabe 1 – Eine Mauer gegen das Wasser

```python
agent.turn(LEFT_TURN)
agent.place(RIGHT)
agent.move(FORWARD, 5)
agent.detect(AgentDetection.BLOCK, FORWARD) 
while True:
      pass
```

## Schritt 1
**Teil 1:** Lass den Agenten vorwärtsgehen, **solange** Redstone-Staub vor ihm liegt. Verwende dafür eine `while`-Schleife. Sie wiederholt ihre Befehle, solange die Bedingung zutrifft.

## Schritt 2
**Teil 2:** Ergänze den Ablauf so, dass der Agent beim Vorwärtsgehen **rechts von sich eine zwei Blöcke hohe Mauer** baut.
### ~ tutorialhint
Der Agent hat die benötigten Blöcke bereits in seinem Inventar.
```template
// Ersetze die folgenden Hinweise durch deinen Code.
// Ergänze eine while-Schleife mit agent.detect(). | Teil 1
// Lass den Agenten rechts von sich einen Block setzen. | Teil 2
// Lass den Agenten nach oben gehen. | Teil 2
// Lass den Agenten rechts von sich einen Block setzen. | Teil 2
// Lass den Agenten wieder nach unten gehen. | Teil 2
    agent.move(FORWARD, 1)
// Ende der while-Schleife.
```
