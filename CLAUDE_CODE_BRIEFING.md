# Briefing: JGA Wendl — Tabletop-Kampf ausarbeiten

> **Zweck dieser Datei:** Kontext-Übergabe für eine Claude-Code-Sitzung in VS Code. Aktive Aufgabe = den Tabletop-Kampf vom Skizzen- in den spielfertigen Zustand bringen. Vollständige Projektdetails stehen in `JGA_Wendl_Masterdokument.md` (mit in den Ordner legen).

---

## Kontext in 60 Sekunden

Ganztägiger TTRPG-/Immersions-Event für ~20 Leute zum Junggesellenabschied von **Wendl** (Bräutigam, steht im Fokus). Setting: Mittelalter-Taverne „Im Jahre Schnee". **Iris** (Braut) wurde vom **Erpresser** entführt.

Spine: Wendl besteht Quests → sammelt **Würfel** → ab **6 Würfeln** offen ist der **Tabletop-Kampf gegen den Erpresser** → Sieg, aber der **Komplize (Höschenhändler)** lebt noch → **Werwolf-Finale** enttarnt ihn → er kommt als „gerettete Iris" zurück.

Vier Ressourcen, je eine Funktion: **Würfel** (schaltet Kampf frei), **Hinweis-Karten** (fürs Werwolf-Finale), **Kleidungsstücke** (roter Faden zum Reveal), **Gold** (reine Spaßwährung, gatet nichts).

---

## Projektstand

- **Fertig:** Masterdokument (Ablaufplan + Ökonomie, NPC-Karten, Quest-Karten, Grundregeln).
- **Offener Nebenstrang:** Pub-Quiz-Fragen — Vorgabe: **sehr insiderlastig**, Lösungssatz zeigt auf den Höschenhändler.
- **AKTIVE AUFGABE (diese Sitzung):** Tabletop-Kampf ausarbeiten.

---

## Aktive Aufgabe: Tabletop-Kampf

### Designziele & Constraints
- **Länge:** punchiger Kern ~30–45 Min, **optional verlängerbar** auf ~1,5 h.
- **Kontext:** ~20 Leute, abends nach dem Grillen, angeheitert → laut, theatralisch, keine zähen Brocken.
- **Fokus:** Wendl ist der Held; die Freunde tragen über **ihre Rollen** bei (nicht bloß Statisten).
- **Regeln minimal:** 1 W6, **4+ = Erfolg** als Basis.
- **Riggbar:** Wendl gewinnt am Ende immer — aber mit echter Spannung (er darf „fallen" und gerettet werden).
- **Integration:** Freischaltung bei 6 Würfeln rein; Sieg endet mit sterbendem Hinweis des Erpressers auf den Höschenhändler → Übergang ins Werwolf-Finale.

### Aktueller Entwurf (Ausgangspunkt)
- Erpresser hat **20 LP**.
- Runde: Wendl + bis zu 3 Helfer würfeln je 1 W6, jede **4+ = 1 Schaden**.
- Wendls **6 gesammelte Würfel** = Sonderangriffe (extra Würfe, über den Kampf verteilbar).
- Optionaler Zwischenfall: **Saboteur** stürmt mit Tortilla-Angriff herein (Chaos-Runde).
- Sieg: Erpresser fällt, Bestatter „entsorgt" ihn, letzter Atem nennt den Höschenhändler.

### Zu entwickeln (Checkliste für die Sitzung)
1. **Boss-Statblock + Fähigkeiten** — der Erpresser soll *agieren*, nicht nur LP haben. Seeds: „Erpresserschreiben" (ein Spieler muss aussetzen oder trinken/Aufgabe), „Geiseldrohung" (zeigt Iris-Kleidung → Wendl muss würfeln, sonst Runde verloren).
2. **Phasen / Eskalation** — z. B. 2 Phasen, in der zweiten neue Boss-Fähigkeit.
3. **Helfer-Aktionen je Rolle** (an den Cast koppeln). Seeds:
   - Jaron/Ritter: schwerer Hieb (2 Würfe).
   - Heindl/Magier: Zauber — erzwingt eine 6 oder kontert eine Boss-Fähigkeit.
   - Dom/Heiler: bringt einen „Gefallenen" zurück / heilt Wendl.
   - Markus/Barde: Buff — in dieser Runde trifft die Gruppe schon ab 3+.
   - Christoph/Bestatter: Einschüchterung / Sonderschaden.
   - Stammtisch: gemeinsamer Gruppenangriff (ein gebündelter Wurf).
4. **Wendls Sonderangriffe** — die 6 Würfel als benannte, coole Moves (Insider erlaubt).
5. **„Wendl geht zu Boden"-Mechanik** — Spannungsmoment + Rettung durch Heiler/Freunde.
6. **Saboteur-/Tortilla-Zwischenfall ausregeln** — Trigger, Effekt, Auflösung.
7. **Sieg-/Niederlage-Bedingungen + Rigging-Hinweise** — wie der GM dafür sorgt, dass es knapp, aber siegreich endet.
8. **Verlängerungs-Optionen** — Minions (Tavernengäste), zweite Boss-Phase.
9. **Requisiten** — Riesen-W6, sichtbare LP-Leiste, Schaumstoff-Waffen, Erpresserschreiben-Vorlagen.
10. **Übergänge** — Freischaltungs-Moment rein; sterbender Hinweis → Werwolf raus.

### Tonalität
Insider-Gags ausdrücklich erwünscht (Tortilla, Erpresserschreiben-Stil, Charakter-Macken der echten Leute).

---

## So nutzt du das in Claude Code
1. Beide `.md`-Dateien (dieses Briefing + Masterdokument) in einen Projektordner legen, in VS Code öffnen.
2. Claude-Code-Sitzung starten und auf den Ordner zeigen.
3. Einstieg z. B.: *„Lies CLAUDE_CODE_BRIEFING.md und arbeite die aktive Aufgabe (Tabletop-Kampf) Punkt für Punkt aus."*
