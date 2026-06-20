# Storyline: Von Copilot zur Dark Factory
## AI Hackathon – 30-Minuten-Impuls für Entwickler

---

## Kernthese

> Am Anfang war AI ein Werkzeug. Dann wurde sie ein Mitarbeiter. Jetzt baut sie alleine. Die Frage ist nicht mehr „Kann AI coden?" – sondern: **„Was ist meine Rolle darin?"**

---

## Timing-Übersicht (30 Min)

| Block | Inhalt | Min |
|---|---|---|
| 0 | Opener / Hook | 2 |
| 1 | Woher kommen wir? – Die drei Ären | 5 |
| 2 | Was ist eine Coding Factory? | 6 |
| 3 | Die Dark Factory – Fiktion oder Gegenwart? | 6 |
| 4 | Der Change-Aspekt: Was ändert sich wirklich? | 7 |
| 5 | Takeaways & Call to Action | 4 |

---

## Block 0 – Opener / Hook (2 Min)

**Slide: „Schreibt gerade jemand von euch Code?"**

- Handzeichen-Frage ans Publikum
- Follow-up: „Schreibt die AI gerade Code für euch?"
- Pointe: „Bald wissen wir nicht mehr, wer von beiden die Frage stellt."

**Einstieg mit einem konkreten Bild:**
> Ich hab letzten Dienstag ein Feature ausgeliefert. Ich hab keinen einzigen Character Code geschrieben. Trotzdem war ich der ganze Tag busy.

→ Das ist keine Magie. Das ist eine Coding Factory.

---

## Block 1 – Woher kommen wir? Die drei Ären (5 Min)

**Slide: Die Drei Ären der AI-Assisted Development**

### Ära 1: AI als Werkzeug (2022–2023)
- GitHub Copilot, ChatGPT im Browser
- Autocomplete on steroids
- Dev ist Pilot, AI ist GPS
- Metapher: „Rechtschreibkorrektur, die auch ganzen Sätze kennt"

### Ära 2: AI als Mitarbeiter (2024–2025)
- Cursor, Kiro, Devin erscheinen
- AI liest Kontext, plant, führt aus
- Dev reviewt, AI implementiert
- Metapher: „Werksstudent der nie schläft, nie meckert, und nie Kaffee will"

### Ära 3: AI als Factory (2025–heute)
- Agentic Pipelines, Multi-Agent, Async Coding
- Dev schreibt Spec – Factory liefert Code
- Metapher: „Dark Factory: Licht aus, Robots bauen"

**Key Visual:** Die 3-Ären-Karte aus „Building a Coding Factory" – ggf. direkt übernehmen/adaptieren

---

## Block 2 – Was ist eine Coding Factory? (6 Min)

**Slide: Gleiche Bausteine, andere Hände**

Ausgangspunkt aus „Building a Coding Factory":
- Classic Dev Loop: PO → Dev → CI → Review → Deploy
- Coding Factory: Spec → Agent(s) → CI → Review → Deploy
- Was ändert sich: **Wer** die Arbeit macht, nicht **wie** die Arbeit aussieht

**Slide: Die Factory – Schematisch**
- Control Plane: Du gibst den Kurs vor
- Execution Plane: Agents bauen, testen, commiten
- Der Mensch bleibt im Loop – aber am Ende, nicht in der Mitte

**Slide: Warum ist das möglich?**
- LLMs können planen, strukturieren, Code generieren
- Agents können Tools bedienen (git, bash, APIs)
- Feedback Loops schließen sich automatisch (CI fail → Agent fixt → CI pass)
- Async: Die Factory arbeitet, während du schläfst

**Live-Referenz (optional):** Eigenes Setup zeigen (Happier / Multica)

---

## Block 3 – Die Dark Factory: Fiktion oder Gegenwart? (6 Min)

**Slide: Was ist eine „Dark Factory"?**

> In der Fertigung: Vollautomatisierte Fabrik – kein Mensch im Gebäude.  
> In der Software: Vollautomatisierte Coding Pipeline – kein Dev im Loop.

**Slide: Ist das heute schon Realität?**

Ja – für bestimmte Szenarien:
- Dependency Updates (Renovate Bot, Dependabot + Auto-Merge)
- Bugfixes auf Basis von Test-Output
- Scaffolding / Boilerplate-Generation
- Infrastruktur-Drift-Korrekturen

Noch nicht – für andere:
- Architekturentscheidungen
- Produktverständnis / Business-Kontext
- Security-kritische Änderungen
- Review durch jemanden der weiß was falsch sein könnte

**Slide: Das Spektrum**

```
Vollständig manuell  →  AI-Assisted  →  AI-Driven  →  Dark Factory
    "klassisch"          "Copilot"     "Coding Factory"   "vollautomatisch"
```

**Pointe:** Wir sind schon weiter links als viele denken – und weiter rechts als wir zugeben wollen.

---

## Block 4 – Der Change-Aspekt: Was ändert sich wirklich? (7 Min)

*(Das ist der wichtigste Block – hier nicht nur Tech reden!)*

**Slide: Die technische Verschiebung**
- Von: Code schreiben → Zu: Specs schreiben, Reviews machen
- Von: Einzelner Dev mit Laptop → Zu: Orchestrator mit Fleet
- Von: Synchron → Zu: Async (Agents arbeiten parallel, nachts, am WE)

**Slide: Die organisatorische Verschiebung**
- Team-Struktur: Brauchen wir noch 5 Devs wenn einer 5 Agents steuern kann?
- Rollen: Der "Senior" ist nicht mehr der der am meisten tippt
- Metriken: Lines of Code und Commits sagen nichts mehr

**Slide: Die Skills-Verschiebung – Was noch zählt**
- Systems Thinking (AI baut was du beschreibst – nicht was du meinst)
- Architektur & Clean Code (AI reviewed niemand den schlechten Code weg)
- Review-Kompetenz (du kannst nur reviewen was du verstehst)
- Prompt/Spec Engineering (Garbage in, Garbage out)
- **Zitat aus eigenem Talk:** „The agent is only as good as the senior who reviews"

**Slide: Die menschliche Verschiebung (Change!)**
- Identität: Viele Devs definieren sich über das Coden selbst
- Angst ist real und berechtigt – nicht wegdiskutieren
- But: Elektriker haben die Elektrizität auch überlebt
- Die Frage ist: Wer lernt, Factories zu bauen – und wer bleibt Zuschauer?

**Quote-Slide (aus eigenem Talk adaptieren):**
> „10× faster code means 10× faster problems — in socio-technical systems, speed alone isn't the answer."

---

## Block 5 – Takeaways & Call to Action (4 Min)

**Slide: Die drei Take-Home Messages**

1. **AI hat die Zündung gezündet – der Zug fährt**  
   Copilot war Akt 1. Coding Factories sind Akt 2. Was kommt danach, weiß noch niemand.

2. **Deine Rolle verschiebt sich – und das ist okay**  
   Vom Coder zum Architekten, vom Tipper zum Reviewer, vom Solo-Dev zum Factory-Owner.

3. **Bau Erfahrung auf, jetzt**  
   Nicht warten bis es alle können. Jetzt ist die Zeit zum Lernen – die Playground-Phase.

**Slide: Call to Action – Konkret**
- Heute: Probier einen AI-Agent auf einem echten Task
- Diese Woche: Schreib eine Spec statt direkt zu coden
- Diesen Monat: Baue einen kleinen automatisierten Loop (CI + Agent + PR)

**Slide: Q&A / Diskussion**
- Opener-Frage zurückwerfen: „Was würde sich in eurem Team ändern, wenn ihr morgen 5 Agents hättet?"

---

## Ton & Stil

- **Persona:** Lead Platform Architect, der AI nicht verkauft sondern lebt
- **Ton:** Direkt, witzig, ehrlich über Risiken und Grenzen
- **Keine Buzzword-Bingo-Slides** – konkrete Beispiele, eigene Erfahrungen
- **Change-Aspekt nicht als Drohung** sondern als Einladung rahmend
- Marvins Stimme: pragmatisch, ein bisschen nerdig, Humor eingebaut

---

## Slide-Kandidaten aus „Building a Coding Factory" (direkt nutzbar / adaptierbar)

| Original-Slide | Verwendung im neuen Talk |
|---|---|
| „Three Eras of Coding" | Block 1 – zentrale Ankerkarte |
| „What Changed?" | Block 1 – Überleitung |
| „What if Coding Was a Factory?" (SVG-Diagram) | Block 2 – Factory erklärt |
| „Factory Schematic" (Control/Execution Plane) | Block 2 – Wie's technisch funktioniert |
| „The Skills That (Still) Matter" | Block 4 – Skills-Verschiebung |
| „10× faster code means..." (Quote-Slide) | Block 4 – Change-Pointe |

---

## Offen / Noch zu klären

- [ ] Demo live oder nur Referenz/Screenshot? (Hack-Kontext → Demo empfohlen)
- [ ] Deutsch oder Englisch? (Anfrage war deutsch, aber Slides könnten en sein)
- [ ] Gibt es bereits vorhandene PPTX-Assets (OTTO Branding) oder komplett freies Reveal.js-Format?
- [ ] Soll Marvin seinen OTTO-Kontext explizit einbringen oder neutraler vortragen?
