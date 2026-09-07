### @explicitHints true
# Aufgabe 3 – Zeit zum Saubermachen

```python
for i in range(2):
pass
agent.collect_all()
agent.move(FORWARD, 5)
agent.drop_all(FORWARD)
```

## Schritt 1
**Teil 1:** Lass den Agenten über jeden Block des kleinen Teppichs laufen und dabei den Schmutz einsammeln.
### ~ tutorialhint 
Verwende für die beiden Schleifen unterschiedliche Zählvariablen, zum Beispiel `i` und `j`.

## Schritt 2
**Teil 2:** Passe den Code für den größeren Teppich an. Wiederhole den bisherigen Ablauf mit einer `for`-Schleife **dreimal**. Zum Schluss soll der Agent den gesamten Schmutz in den Mülleimer **rechts von sich** werfen.
### ~ tutorialhint 
Bei einer Schleife innerhalb einer anderen Schleife rückst du die Befehle der inneren Schleife **zweimal** ein.

```template
// Ersetze die folgenden Hinweise durch deinen Code.
// Ergänze eine for-Schleife (Schleife 3). | Teil 2
// Ergänze eine for-Schleife (Schleife 1). | Teil 1
agent.collect_all()
agent.move(FORWARD, 1)
// Ende der Schleife 1.
agent.move(RIGHT, 1)
// Ergänze eine for-Schleife (Schleife 2). | Teil 1
// Lass den Agenten alle Gegenstände einsammeln. | Teil 1
// Lass den Agenten rückwärtsgehen. | Teil 1
// Ende der Schleife 2.
// Lass den Agenten nach rechts gehen. | Teil 2
// Ende der Schleife 3.
// Lass den Agenten alle Gegenstände rechts von sich ablegen. | Teil 2
```
