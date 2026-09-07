### @explicitHints true

# Aufgabe 2 – Steine aus dem Weg räumen


## Schritt 1
**Teil 1:** Lass den Agenten vorwärtsgehen und dabei jeden **Steinblock** (stone) auf seinem Weg abbauen und einsammeln.
### ~ tutorialhint
Mit dieser Bedingung prüfst du den Blocktyp. Ersetze `DIRECTION` durch die gewünschte Richtung und `BLOCK_TYPE` durch den gesuchten Blocktyp:
```python
agent.inspect(AgentInspection.BLOCK, DIRECTION) == BLOCK_TYPE
```

## Schritt 2
**Teil 2:** Ergänze deinen Code so, dass der Agent auch **Grasblöcke** (grass block) bearbeitet und dort Setzlinge (sapling) pflanzt.
### ~ tutorialhint
Mit dieser Bedingung prüfst du den Blocktyp. Ersetze `DIRECTION` durch die gewünschte Richtung und `BLOCK_TYPE` durch den gesuchten Blocktyp:
```python
agent.inspect(AgentInspection.BLOCK, DIRECTION) == BLOCK_TYPE
```

```template        
```
