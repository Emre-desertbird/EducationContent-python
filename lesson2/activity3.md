### @explicitHints true
### @hideIteration true 
# Aufgabe 3 – Stufe für Stufe

```python
blocks.place(blocks.block_with_data(BRICK_STAIRS, 0), pos(0, 0, 0))
```

## Schritt 1
Baue mit Python eine vollständige **Ziegeltreppe** (brick stairs; im Code: `BRICK_STAIRS`). Ändere in deinen drei `blocks.place()`-Befehlen die **zweite und dritte Zahl** der Position, also `y` und `z`.

Für die Ausrichtung setzt du `blocks.block_with_data()` direkt in die Klammern von `blocks.place()`. Du kannst die Zeile selbst eintippen oder kopieren; du brauchst dafür kein Drag-and-drop. So sieht ein Beispiel aus – passe die Position und die Ausrichtung an deine Treppe an:

```python
blocks.place(blocks.block_with_data(BRICK_STAIRS, 3), pos(0, 2, 3))
```

Der innere Befehl liefert eine Ziegeltreppenstufe mit der Ausrichtung `3`. Der äußere Befehl setzt genau diese Stufe an die angegebene Position. Ein einzelner Aufruf von `blocks.block_with_data()` in einer eigenen Zeile dreht keine bereits gesetzte Treppe und verändert auch `BRICK_STAIRS` nicht.

### ~ tutorialhint
Die Werte `0`, `1`, `2` und `3` stehen für die vier waagerechten Ausrichtungen. Wenn eine Stufe falsch herum steht, ändere nur diese Zahl und führe den Befehl für dieselbe Position erneut aus. Bleibe dabei an derselben Stelle stehen: `pos()` gibt die Position relativ zu deinen Füßen an. Achte darauf, dass die Stufen in Laufrichtung ansteigen.
