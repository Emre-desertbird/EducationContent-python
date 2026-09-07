### @explicitHints true
### @hideIteration true 
# Reihe für Reihe

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
Lass den Agenten Reihe für Reihe über jeden Block der Fläche laufen. Er soll sich dabei seitwärts bewegen, ohne sich zu drehen.