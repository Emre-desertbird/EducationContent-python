### @explicitHints true
 
# Aufgabe 2 – Links oder rechts?

```python
agent.inspect(AgentInspection.BLOCK, FORWARD)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 5)
for i in range(2):
      pass
if True:
      pass
```

## Schritt 1
**Teil 1:** Verwende eine `if`-`else`-Abfrage: Wenn der Agent den Richtungsblock erreicht, soll er sich nach links drehen. Sonst soll er vorwärtsgehen, bis er auf dem Goldblock (gold block) steht. Prüfe den Block vor dem Agenten mit `agent.inspect()` und vergleiche das Ergebnis mit der Variablen `left`. So sieht der Prüf-Befehl aus:
```python
agent.inspect(AgentInspection.BLOCK, FORWARD)
```
Die Richtungsblöcke bestehen aus blau glasierter Keramik (blue glazed terracotta) und rosa glasierter Keramik (pink glazed terracotta). Nutze die vorgegebenen Variablen: `left = BLUE_GLAZED_TERRACOTTA` steht für die Linksmarkierung, `right = PINK_GLAZED_TERRACOTTA` für die Rechtsmarkierung.
### ~ tutorialhint 
Mit **`==`** prüfst du, ob zwei Werte gleich sind.

## Schritt 2
**Teil 2:** Erweitere den Code so, dass der Agent je nach Richtungsblock links oder rechts abbiegt und den Goldblock erreicht. Füge dafür zwischen `if` und `else` eine weitere Bedingung mit `elif` ein.
### ~ tutorialhint 
Prüfe bei `elif` den Block wieder mit `agent.inspect()`. Vergleiche das Ergebnis diesmal mit `right`.

```template
left = BLUE_GLAZED_TERRACOTTA
right = PINK_GLAZED_TERRACOTTA
// Ersetze die folgenden Hinweise durch deinen Code.
// Ändere die Anzahl der Wiederholungen von 9 auf 21. | Teil 2
// Ergänze eine for-Schleife mit 9 Wiederholungen. | Teil 1
// Ergänze eine if-else-Abfrage mit agent.inspect(). | Teil 1
agent.turn(LEFT_TURN)
// Ergänze eine elif-Bedingung mit agent.inspect(). | Teil 2
// Lass den Agenten sich nach rechts drehen. | Teil 2
// Ergänze den else-Zweig. | Teil 1
// Lass den Agenten vorwärtsgehen. | Teil 1
// Ende der Schleife. | Teil 1
```
