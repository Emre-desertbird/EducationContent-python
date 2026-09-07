### @explicitHints true
### @hideIteration true 

# Der richtige Block aus der Liste

```python
agent.move(FORWARD, 5)
pos(0, 0, 0)
player.say("Fertig")
agent.place(LEFT)
agent.inspect(AgentInspection.BLOCK, DOWN) 
agent.turn(RIGHT_TURN)
agent.destroy(BACK)
agent.drop_all(FORWARD)
agent.collect_all()
loops.pause(500)
for i in range(10):
    pass
if True: 
    pass
else: 
    pass
elif:
    pass
while True:
    pass
```

## Schritt 1
Entferne die einfachen Anführungszeichen (**'**) am Anfang und Ende der vorgegebenen Zeile. Finde dann heraus, auf welchem Block der Agent stehen soll: Sortiere die Liste mit `sort()` alphabetisch und lies den **zweiten Eintrag** aus. Stelle dich auf den passenden Block und drücke den Knopf, um den Agenten dorthin zu teleportieren.

Finde nun deinen eigenen Zielblock: Kehre dieselbe Liste mit `reverse()` um und entferne mit `pop()` den **vierten Eintrag**. Lies danach den **sechsten Eintrag** aus und stelle dich auf diesen Block. Denke daran, dass Python die Indizes ab **0** zählt.

Lass die englischen Blocknamen in der Liste stehen, damit die alphabetische Reihenfolge zum Rätsel passt: `DIAMOND` = Diamant, `ICE` = Eis, `EMERALD` = Smaragd, `STONE` = Stein, `WOOD` = Holz, `GOLD` = Gold, `QUARTZ` = Quarz.

```template
'block_list = ["DIAMOND", "ICE", "EMERALD", "STONE", "WOOD", "GOLD", "QUARTZ"]'
```