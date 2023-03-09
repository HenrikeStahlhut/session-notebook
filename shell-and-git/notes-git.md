# Session notes GIT

## 08/03/2023

### Allgemeine Befehle

- pwd - an welcher Stelle/Ordner sind wir
- cd - ordner wechseln
- ls - alle Elemente im Ordner anzeigen
- ls-la - auch versteckte Elemente anzeigen
- cd .. - einen Ordner nach oben
- command + k - alles aus Terminal löschen
- clear - alles clearen
- mkdir + Ordnernamen - neuen Ordner anlegen
- touch + neueDatei.datei - neue Datei erstellen
- rm - löschen _wichtig: endgültiges löschen!!_
- rm-r - Ordner inklusive alle Dateien löschen
- rm-rf - ALLES auf der Festplatte löschen
- mv - move bzw. Datei neu benennen
- cat + Dateinamen.datei - gibt Inhalt der Datei aus

### git Befehle

- git init - erstell ein repository aus Ordner -> Ordner initialisieren
- rm-rf .git - respository löschen -> Ordner wird normaler Ordner
- git status - gibt Status
- git add _Datei_ - Datei wird gestaged, also von untracked zu tracked
- git add . - alles in Ordner stagen
- git log - commits anschauen
- git commit -m'_commit message_' - Dateien die Status tracked haben werden commited
- git checkout _Hash vom Commit_ - zum jeweiligen Commit zurück gehen
- git log--online - kurze Beschreibung von Commits anzeigen lassen
- git restore _Dateiname_ - Datei wird auf Zustand vom letzten Commit zurückgesetzt
