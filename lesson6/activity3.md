### @explicitHints true
### @hideIteration true 
# Aufgabe 3 – Hindernissen ausweichen

```python
agent.detect(AgentDetection.BLOCK, FORWARD) 
agent.turn(LEFT_TURN)
agent.move(FORWARD, 5)
for i in range(2):
      pass
if True:
      pass
```

## Schritt 1
Lass den Agenten die zufällig verteilten Hindernisse erkennen und ihnen ausweichen. Verwende dafür `if`, `elif` und `else`. Verbinde in der `if`-Bedingung zwei Prüfungen mit `agent.detect()` durch **`and not`**. In der `elif`-Bedingung verbindest du zwei Prüfungen durch **`and`**. Das folgende Muster zeigt `and not`. Ersetze `DIRECTION` jeweils durch die Richtung, die du prüfen möchtest:
```python
agent.detect(AgentDetection.BLOCK, DIRECTION) and not agent.detect(AgentDetection.BLOCK, DIRECTION)
```

### ~ tutorialhint 
Mit `and` müssen **beide** Bedingungen zutreffen. Bei `and not` muss die erste Bedingung zutreffen und die zweite **nicht**.

```template
// Ersetze die folgenden Hinweise durch deinen Code.
// Ergänze eine for-Schleife mit 23 Wiederholungen.
// Ergänze eine if-Bedingung mit zwei agent.detect()-Prüfungen, verbunden durch and not.
agent.move(LEFT, 1)                              
// Ergänze eine elif-Bedingung mit zwei agent.detect()-Prüfungen, verbunden durch and.
agent.move(RIGHT, 2)
// Ergänze den else-Zweig.
agent.move(FORWARD, 1)                                   
// Ende der Schleife.
```
