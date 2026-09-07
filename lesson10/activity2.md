### @explicitHints true
### @hideIteration true 

# Licht an!

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
Lass den Agenten auf dem Weg bis zum Goldblock vorwärtsgehen. Dabei soll er die Redstone-Lampen aus seinem Inventar auf die Redstone-Blöcke setzen.

### ~ tutorialhint
Überlege, welche Befehle sich wiederholen. Dafür kannst du eine Schleife verwenden.

