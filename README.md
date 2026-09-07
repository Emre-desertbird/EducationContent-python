# EducationContent – Python

Die Python-Tutorials aus [Mojang/EducationContent](https://github.com/Mojang/EducationContent),
herausgelöst aus dem Unterordner [`python/`](https://github.com/Mojang/EducationContent/tree/master/python).

## Inhalt

| Ordner / Datei | Beschreibung |
| --- | --- |
| `lesson1` … `lesson10` | Die zehn Python-Lektionen (MakeCode-Tutorials im Markdown-Format) |
| `TutorialFinish.md` | Abschlussseite der Tutorials |
| `noCodingRequired.md` | Variante ohne Programmieranteil |
| `test123.md`, `test2.md` | Testtutorials aus dem Original-Repo |
| `pxt.json` | MakeCode-Projektdatei mit den benötigten Paketen und allen Tutorial-Dateien |

## Tutorials in Minecraft laden

MakeCode benötigt neben den Markdown-Dateien die Datei `pxt.json` im
Hauptverzeichnis. Neue Tutorials müssen dort in der Liste `files` ergänzt werden.
Fehlt diese Projektdatei, meldet der MakeCode-Dienst
`failed to fetch pxt.json; 404`, auch wenn die Markdown-Dateien auf GitHub erreichbar sind.

Beispiel für die erste Aufgabe:

```text
https://minecraft.makecode.com/#tutorial:https://github.com/emre-desertbird/educationcontent-python/lesson1/activity1
```

Die Pfade enthalten keinen zusätzlichen Unterordner `python/`. Beim Anpassen einer
Weltdatei müssen sowohl die Links in den `.mcfunction`-Dateien als auch der
gespeicherte Startlink `EDU_CurrentCodingURL_…` in der Weltdatenbank auf dieses
Repository zeigen.

Für die Fehlersuche kann der tatsächliche MakeCode-Abruf geprüft werden:

```text
https://minecraft.makecode.com/api/ghtutorial/emre-desertbird/educationcontent-python/lesson1/activity1
```

Eine erfolgreiche Antwort enthält den Tutorialtext unter
`markdown.repo.files[markdown.filename]`.

Die Links verwenden einheitlich kleingeschriebene GitHub-Namen. Diese Schreibweise
wurde nach dem Ergänzen der Projektdatei auch über den MakeCode-CDN geprüft;
die zuvor verwendeten Links lieferten zeitweise noch einen gespeicherten 404-Fehler.

## Herkunft

* **Quelle:** `Mojang/EducationContent`, Branch `master`
* **Stand:** Commit [`d6f2043`](https://github.com/Mojang/EducationContent/commit/d6f2043b27dfd6bf4abdcc01e1c58cd280f3cf41)
* **Übernommen:** 2026-09-07

Dies ist kein GitHub-Fork, sondern eine eigenständige Kopie – GitHub kann nur ganze
Repositories forken, nicht einzelne Unterordner. Es besteht daher keine
Upstream-Verbindung: Änderungen von Mojang landen nicht automatisch hier.

Aktualisieren lässt sich der Inhalt so:

```bash
git clone --filter=blob:none --sparse --depth 1 --branch master \
  https://github.com/Mojang/EducationContent.git tmp
git -C tmp sparse-checkout set python
# tmp/python/ über den Inhalt dieses Repos kopieren
```

## Lizenz

Das Quell-Repository `Mojang/EducationContent` gibt **keine Lizenz** an. Damit gelten
die Inhalte als „all rights reserved“ von Mojang. Diese Kopie dient der eigenen
Nutzung; für eine Weiterverwendung oder Veröffentlichung müsstest du die Rechtelage
mit Mojang klären.
