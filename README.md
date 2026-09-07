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
