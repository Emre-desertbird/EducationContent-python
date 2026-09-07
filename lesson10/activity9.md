### @explicitHints true
### @hideIteration true 
# Der Agent im Labyrinth

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
Steuere den Agenten durch das Labyrinth. Schreibe dafür Code, der die farbigen Blöcke als Steuerfelder für **vorwärts**, **links** und **rechts** nutzt. Stelle dich dann auf die passenden Felder, um den Agenten bis zum Ausgang zu führen.

### ~ tutorialhint
Eine `while`-Schleife mit der Bedingung `True` läuft immer weiter. `True` bedeutet „wahr“.
