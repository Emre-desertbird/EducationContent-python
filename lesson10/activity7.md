### @explicitHints true
### @hideIteration true 
# Kürbis oder Melone?

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
Lass den Agenten bis zum Goldblock (gold block) vorwärtsgehen. Unterwegs soll er die Melonen (melon block) abbauen und die Kürbisse (pumpkin) stehen lassen.