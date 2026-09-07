### @explicitHints true

# Aufgabe 3 – Ein Fundament fürs Haus

```python
agent.turn(LEFT_TURN)
agent.place(RIGHT)
agent.move(FORWARD, 5)
agent.detect(AgentDetection.BLOCK, FORWARD) 
while True:
      pass
```

## Schritt 1
**Teil 1:** Der Agent soll der Spur aus Redstone-Staub (redstone dust) folgen und links von sich Blöcke setzen. So entsteht das Fundament für das kleine Haus. Verwende **zwei `while`-Schleifen**: eine für die geraden Abschnitte und eine für die Außenecken.

## Schritt 2
**Teil 2:** Erweitere den Code für das Fundament des größeren Hauses. Ergänze eine weitere `while`-Schleife mit einem Ablauf für die Innenecken.
### ~ tutorialhint 
An einer Innenecke muss der Agent einen Block über die vorgegebene Umrisslinie hinausgehen. Dort setzt er einen Block und geht anschließend wieder zurück.

```template
// Ersetze die folgenden Hinweise durch deinen Code.
// Ergänze eine while-Schleife (Schleife 1) mit agent.detect(). | Teil 1
// Lass den Agenten links von sich einen Block setzen. | Teil 1
// Lass den Agenten vorwärtsgehen. | Teil 1
// Ergänze eine while-Schleife (Schleife 2) mit agent.detect(). | Teil 1
agent.turn(LEFT_TURN)
// Lass den Agenten vorwärtsgehen. | Teil 1
// Ende der while-Schleife 2.
// Ergänze eine while-Schleife (Schleife 3) mit agent.detect(). | Teil 2
// Lass den Agenten links von sich einen Block setzen. | Teil 2
// Lass den Agenten vorwärtsgehen. | Teil 2
// Lass den Agenten links von sich einen Block setzen. | Teil 2
// Lass den Agenten rückwärtsgehen. | Teil 2
// Lass den Agenten sich nach rechts drehen. | Teil 2
// Ende der while-Schleife 3.
// Ende der while-Schleife 1.
```
