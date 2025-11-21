# Skill-Forge Projekt-Schmiede

Dieses Repository ist das Startpaket fuer alle Skill-Forge-Projekte. Es ist bewusst einfach gehalten: kurze Texte, feste Ordner, klare Tabellen. So koennen auch Kids ab 12 Jahren loslegen, waehrend wir spaeter trotzdem automatisch Anzeigen und Stats bauen koennen.

> **Hinweis:** Klicke auf GitHub auf **Use this template**, gib deinem Projekt einen Namen (z. B. `2025-kamenz-sensorbox`) und fuelle danach nur die vorhandenen Dateien.

## Die ersten 10 Minuten
Wenn du dieses Template neu benutzt und nur kurz Zeit hast:

1. Oeffne `README.md` und trage **Projektname** und **1 Satz Ziel** ein.
2. Oeffne `1-idea-forge/canvas.md` und schreibe in 2–3 Saetzen, **was ihr bauen wollt**.
3. Setze im Ordner `1-idea-forge/checklist.md` die ersten Haken.

Damit hast du schon einen sichtbaren Start und weisst, wo es weitergeht.

## So funktioniert es
1. **Idee festhalten:** In `1-idea-forge/canvas.md` dein Ziel, die Nutzenden und das geplante Ergebnis beschreiben.
2. **Checklisten nutzen:** In jedem Forge-Ordner gibt es eine `checklist.md`. Setze Haken, wenn etwas fertig ist.
3. **Kurze Updates schreiben:** Einmal pro Woche etwas in `docs/checkpoints.md` eintragen.
4. **Bilder & Videos ablegen:** In den Ordnern unter `assets/` speichern.
5. **Am Ende alles sammeln:** In `5-skill-forge/handover.md` steht, was fuer den Abschluss wichtig ist.

## Die fünf Forges in einfach
- **Idea Forge (Ideenschmiede):** Hier entsteht die Idee. Du haeltst fest, **was** ihr baut, **fuer wen** es ist und **welches Material** ihr braucht.
- **Maker Forge (Makerschmiede):** Hier wird das **Aussehen und Gehaeuse** geplant und gebaut (z. B. 3D-Druck, Laser, Holz, Kunststoff).
- **Copper Forge (Kupferschmiede):** Hier geht es um **Elektronik**: Kabel, Sensoren, Lichter, Platinen.
- **Code Forge (Codeschmiede):** Hier schreibst du den **Programmcode**, der dein Projekt steuert.
- **Skill Forge (Skill-Schmiede):** Hier pruefst du alles, machst Fotos/Videos und bereitest die **Praesentation** vor.

## Verzeichnisstruktur
```
project-name/
├── 0-admin/
├── 1-idea-forge/
├── 2-maker-forge/
├── 3-copper-forge/
├── 4-code-forge/
├── 5-skill-forge/
├── assets/
│   ├── data/
│   ├── images/
│   └── videos/
├── docs/
│   ├── checkpoints.md
│   ├── qa-checklist.md
│   └── retro.md
└── README.md (dieser Steckbrief)
```

Loesche keine Ordner. Die Website findet spaeter anhand dieser Namen alle Infos.

## README-Template
Die Datei `README.md` ist der Projekt-Steckbrief. Fuell die Abschnitte mit einfachen Saetzen aus:

```
# Projektname

Kurzer Satz: Was bauen wir? Fuer wen?

## Plan
- Ziel:
- Was brauchen wir?
- Wann wollen wir fertig sein?

## Team
- Namen oder Nicknames
- Ansprechpartner

## Fortschritt
- Idea Forge: ...
- Maker Forge: ...
- Copper Forge: ...
- Code Forge: ...
- Skill Forge: ...

## Dokumentation
- Checkpoints: Link zur Datei docs/checkpoints.md
- Tests: Link zur Datei docs/qa-checklist.md
- Rueckblick: Link zur Datei docs/retro.md

## Medien
- Wichtigste Fotos (Dateiname in assets/images)
- Videos (Datei in assets/videos oder Link)

## Lessons Learned
Was nehmen wir mit?
```

## Automatisierung
Im Ordner `.github/workflows/` liegt ein Beispiel-Workflow. Er ist ausgeschaltet, bis ihr ihn braucht. Wenn ihr spaeter Tests oder Exporte automatisieren wollt, koennt ihr dort weiterarbeiten.

## Hilfe
Wenn etwas unklar ist, fragt ein Team-Mitglied, schreibt ein Issue oder meldet euch unter `info@skill-forge.de`.
