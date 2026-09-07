### @explicitHints true
### @hideIteration true 
# Diamanten zählen

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
Entferne zuerst die einfachen Anführungszeichen (**'**) am Anfang und Ende jeder Zeile. Ergänze den Code so, dass der Agent auf dem Weg zum Goldblock jeden Diamantblock unter sich zählt. Am Ziel soll er genau so viele Diamantblöcke **einzeln vor sich** setzen, wie er unterwegs gezählt hat. Ein Kolben stapelt die gesetzten Blöcke automatisch.
```template
'diamond = 0'
'for index in range(11):'
'    agent.move(FORWARD, 1)'
'for index2 in range(diamond):'
'    agent.place(FORWARD)'
'    loops.pause(500)'
```