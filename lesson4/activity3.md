### @explicitHints true

# Aufgabe 3 – Wie heißt die Katze?

```python
player.say("Hallo")
```

## Schritt 1
Ändere den letzten Namen in der Liste `Cat_Names` zu **"Shadow"**. Passe `player.say()` so an, dass der **letzte** Name der Liste im Chat erscheint. Drücke dann **„Katze auswählen“** (englisch: **select a cat**) und wähle die Katze mit diesem Namen.
### ~ tutorialhint 
Einen Listeneintrag änderst du nach diesem Muster: `liste[index] = "Neuer Name"`. Setze den Listennamen und den passenden Index ein.

## Schritt 2
Sortiere die Katzennamen mit `sort()` alphabetisch. Passe `player.say()` so an, dass der **vierte** Name im Chat erscheint. Achtung: Python zählt ab `0`, deshalb ist `Cat_Names[4]` nicht der vierte Eintrag. Drücke wieder **„Katze auswählen“** (englisch: **select a cat**) und wähle die passende Katze.
### ~ tutorialhint 
Die Zählung in Listen beginnt bei **0**.

## Schritt 3
Kehre die Reihenfolge der Liste mit `reverse()` um. Lass den Index in `player.say()` unverändert. Drücke **„Katze auswählen“** (englisch: **select a cat**) und wähle die Katze, deren Name jetzt im Chat steht.

```template
Cat_Names= ["Smokey", "Oreo", "Sammy", "Patch", "Princess", "Snowy"]
// Ersetze die folgenden Hinweise durch deinen Code.
// Ändere den letzten Namen zu "Shadow". | Schritt 1
// Sortiere die Namen in der Liste alphabetisch. | Schritt 2
// Kehre die Reihenfolge der Namen in der Liste um. | Schritt 3
// Passe den Listenindex im folgenden Befehl an. | Schritt 1,2,3
player.say(Cat_Names[0])  
```
