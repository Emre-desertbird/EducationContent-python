### @explicitHints true

# Aufgabe 2 – Das richtige Hundefutter

```python
blocks.place()
```

## Schritt 1
Der **erste Hund** soll alle Zutaten aus der vorgegebenen Liste bekommen. Ändere dafür die Listenindizes in den ersten **vier** `blocks.place()`-Befehlen. So werden die Zutaten der Reihe nach ausgewählt. Gib anschließend das Futter aus der Truhe an Hund 1. Die Namen stehen für Knochen (`Bone`), Rindfleisch (`Beef`), Hähnchen (`Chicken`), Keks (`Biscuit`) und Vitamine (`Vitamins`).

### ~ tutorialhint 
Wähle einen Gegenstand in deiner Schnellzugriffsleiste aus und drücke **Q**, um ihn fallen zu lassen.

## Schritt 2
Der **zweite Hund** bekommt dieselben Zutaten und zusätzlich Vitamine. Mit `append()` kannst du **einen neuen Eintrag am Ende einer Liste hinzufügen**:

```python
Listenname.append(neuer_Eintrag)
```

Hänge `Vitamins` mit `append()` an das Ende der Liste an. Passe dann den letzten `blocks.place()`-Befehl so an, dass die Vitamine in die Maschine gelangen. Gib das Futter anschließend an Hund 2.

## Schritt 3
Der **dritte Hund** bekommt die Zutaten aus der Liste, aber **ohne Rindfleisch**. Mit `pop()` kannst du **einen Eintrag über seinen Index aus einer Liste entfernen**:

```python
Listenname.pop(index)
```

Entferne den Eintrag `Beef` mit `pop()` aus der Liste. Gib das Futter anschließend an Hund 3.

### ~ tutorialhint 
Bei `pop()` gibst du den **Index** des Eintrags an, den du entfernen möchtest. Denke daran: Der erste Eintrag hat den Index `0`.

```template
Bone = world(-21, 45, -31)
Beef = world(-21, 45, -29)
Chicken = world(-21, 45, -27)
Biscuit = world(-21, 45, -25)
Vitamins = world(-21, 45, -23)
// Ersetze die folgenden Hinweise durch deinen Code.
Dog_Food=[Bone, Beef, Chicken, Biscuit]
// Hänge Vitamins mit append() an die Liste an. | Schritt 2
// Entferne den Eintrag für Beef mit pop() aus der Liste. | Schritt 3

blocks.place(REDSTONE_BLOCK, Dog_Food[0]) 
// Passe den Listenindex im folgenden Befehl an. | Schritt 1
blocks.place(REDSTONE_BLOCK, Dog_Food[0])
// Passe den Listenindex im folgenden Befehl an. | Schritt 1
blocks.place(REDSTONE_BLOCK, Dog_Food[0]) 
// Passe den Listenindex im folgenden Befehl an. | Schritt 1
blocks.place(REDSTONE_BLOCK, Dog_Food[0])   
// Passe den Listenindex im folgenden Befehl an. | Schritt 2
blocks.place(REDSTONE_BLOCK, Dog_Food[0]) 
```
