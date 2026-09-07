### @explicitHints true
### @hideIteration true 

# Der Frühling kommt

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
for index in range(10):
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
Im Codefenster steht ein unvollständiger Code. Entferne zuerst die einfachen Anführungszeichen (**'**) am Anfang und Ende jeder Zeile. Der Agent soll Reihe für Reihe durch die Fläche laufen und auf jedem Grasblock eine Blume pflanzen. Ergänze die fehlende Bedingung und korrigiere die äußere Schleife, damit der Ablauf funktioniert.
```template
'for index in range(4):'
'   for index2 in range(8):'
'        if agent.inspect(AgentInspection.BLOCK, DOWN) == GRASS:'
'            agent.place(DOWN)'
'        agent.move(FORWARD, 1)'
'   agent.turn(RIGHT_TURN)'
'   agent.move(FORWARD, 1)'
'   agent.turn(RIGHT_TURN)'
'   for index3 in range(8):'
'       if True:'
'           agent.place(DOWN)'
'       agent.move(FORWARD, 1)'
'   agent.turn(LEFT_TURN)'
'   agent.move(FORWARD, 1)'
'   agent.turn(LEFT_TURN)'
```

