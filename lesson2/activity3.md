### @explicitHints true
### @hideIteration true 
# Aufgabe 3 – Stufe für Stufe

```python
blocks.place(GRASS_BLOCK, pos(0, 0, 0))
blocks.block_with_data(GRASS_BLOCK, 0)
```

## Schritt 1
Baue mit Python eine vollständige **Ziegeltreppe**. Ändere in allen drei `blocks.place()`-Befehlen die **zweite und dritte Zahl** der Position, also `y` und `z`. Passe auch die Zahlenwerte in `blocks.block_with_data()` an. Diese bestimmen bei Treppen, in welche Richtung die Stufen zeigen.

### ~ tutorialhint 
An den Wänden findest du die Himmelsrichtungen. Für die Ausrichtung der Treppen gelten diese Werte:

- `0` = Westen (W)
- `1` = Osten (E für englisch „East“)
- `2` = Norden (N)
- `3` = Süden (S)
