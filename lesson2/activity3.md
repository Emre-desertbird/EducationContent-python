### @explicitHints true
### @hideIteration true
# Aufgabe 3 – Stufe für Stufe

```python
blocks.place(BRICKS, pos(0, 0, 1))
```

## Schritt 1
Baue mit Python eine Treppe aus drei **vollen Ziegelblöcken** (bricks; im Code: `BRICKS`). Verwende dafür drei `blocks.place()`-Befehle. Die Aufgabe prüft, ob die richtigen Blöcke an den vorgesehenen Stellen stehen. Treppenblöcke (`BRICK_STAIRS`) werden hier nicht als Lösung erkannt.

Stelle dich auf den **Goldblock**, bevor du deinen Code ausführst. Bleibe dort stehen, bis alle drei Blöcke gesetzt sind: `pos()` beschreibt die Position eines Blocks relativ zu deinen Füßen.

Setze den ersten Block mit `pos(0, 0, 1)` direkt hinter den Goldblock. Jeder weitere Block soll eine Stelle höher und eine Stelle weiter in dieselbe Richtung stehen. Erhöhe dafür jeweils die **zweite und dritte Zahl**, also `y` und `z`, um `1`. Die erste Zahl (`x`) bleibt `0`.

### ~ tutorialhint
So setzt du die drei Ziegelblöcke, wenn du auf dem Goldblock stehst:

```python
blocks.place(BRICKS, pos(0, 0, 1))
blocks.place(BRICKS, pos(0, 1, 2))
blocks.place(BRICKS, pos(0, 2, 3))
```

Volle Ziegelblöcke müssen nicht ausgerichtet werden. Du brauchst für diese Aufgabe also kein `blocks.block_with_data()`. Springe anschließend von Block zu Block nach oben.
