### @explicitHints true
# Aufgabe 2 – Im Schleudergang

```python
for i in range(2):
pass
agent.collect_all()
agent.move(FORWARD, 5)
agent.drop_all(FORWARD)
agent.turn(LEFT)

```

## Schritt 1
**Teil 1:** Der Agent soll die schmutzige Wäsche einsammeln und **vorwärts** in die Waschmaschine bringen. Dort soll er sich **20-mal nach links** drehen. Danach soll er die saubere Wäsche einsammeln, aus der Maschine gehen und sie auf der anderen Seite des Bereichs mit der schmutzigen Wäsche ablegen.

## Schritt 2
**Teil 2:** Erweitere deinen Code für **drei Ladungen Wäsche**. Setze dafür eine weitere `for`-Schleife um den gesamten bisherigen Ablauf.

### ~ tutorialhint 
Verwende für die beiden Schleifen unterschiedliche Zählvariablen, zum Beispiel `i` und `j`. Wenn du mehrere Zeilen auf einmal einrücken möchtest, markiere sie und drücke die **Tab-Taste**.

```template
// Ersetze die folgenden Hinweise durch deinen Code.
// Ergänze eine for-Schleife (Schleife 2) mit 3 Wiederholungen. | Teil 2
agent.collect_all()
agent.move(FORWARD, 7)
agent.drop_all(FORWARD)
// Ergänze eine for-Schleife (Schleife 1). | Teil 1
// Lass den Agenten sich mit der Schleife 20-mal nach links drehen. | Teil 1
// Ende der Schleife 1.
// Lass den Agenten alle Gegenstände einsammeln. | Teil 1
// Lass den Agenten rückwärtsgehen. | Teil 1
// Lass den Agenten alle Gegenstände links von sich ablegen. | Teil 1
// Ende der Schleife 2.
```
