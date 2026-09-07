### @explicitHints true

# Aufgabe 1 – Anhalten und weitergehen

```python
loops.pause(2000)
agent.move(FORWARD, 5)
for i in range(2):
      pass
if True:
      pass
agent.detect(AgentDetection.BLOCK, FORWARD)
```

## Schritt 1
**Teil 1:** Der Agent soll nur vorwärtsgehen, wenn **links von ihm ein Block liegt**. Prüfe das mit `agent.detect()`. Diese Prüfung ist die Bedingung für deinen `if`-Befehl:
```python
agent.detect(AgentDetection.BLOCK, LEFT)
```

## Schritt 2
**Teil 2:** Ändere den Code so, dass der Agent vorwärtsgeht, wenn links von ihm **kein Block** liegt. Schreibe dafür `not` vor die Bedingung. Das bedeutet „nicht“ und kehrt das Ergebnis der Prüfung um.

## Schritt 3
**Teil 3:** Lass den Agenten nach der Pause mit `loops.pause()` weitergehen, damit er den letzten Goldblock (gold block) erreicht.

### ~ tutorialhint
**1000 Millisekunden (ms)** entsprechen **1 Sekunde**.

```template
// Ersetze die folgenden Hinweise durch deinen Code.
// Ergänze eine for-Schleife mit 7 Wiederholungen. | Teil 1
// Ergänze not vor der folgenden Bedingung. | Teil 2
// Ergänze eine if-Bedingung mit agent.detect(). | Teil 1
// Lass den Agenten vorwärtsgehen. | Teil 1
// Ergänze eine if-Bedingung mit agent.detect(). | Teil 3
loops.pause(2000)
// Lass den Agenten vorwärtsgehen. | Teil 3
// Ende der Schleife.
```
