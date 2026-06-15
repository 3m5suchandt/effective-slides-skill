![Banner](assets/banner.png)

# Effective Presentation Slides — ein Skill für Claude Code

## Die meisten Präsentationen scheitern nicht am Design — sondern am Inhalt

Folien werden neu gestaltet, Schriften gewechselt, Farben angepasst. Und der Vortrag zündet trotzdem nicht. Das eigentliche Problem liegt fast immer tiefer: kein klarer roter Faden, Überschriften, die beschriften statt zu schlussfolgern, Argumente, die behauptet statt gezeigt werden — und ein Sprecher, der sich selbst zur Hauptfigur seiner Geschichte macht.

Dieser Skill gibt Claude Code ein evidenzbasiertes Framework, das genau dort ansetzt: **bei Inhalt und Struktur, bevor das erste Bild gewählt wird.**

---

## Was der Skill leistet

### Narrativer Bogen vor dem ersten Slide

Bevor einzelne Folien strukturiert werden, braucht ein Deck einen dramatischen Bogen. Das Gehirn speichert Wissen als Geschichten — Narration ist keine rhetorische Dekoration, sondern das Betriebssystem der Kognition. Daten allein verändern selten Verhalten; eine Geschichte mit Daten darin schon.

Der Skill kennt sechs bewährte Erzählstrukturen und wählt die passende anhand von Ziel, Publikum und Format aus:

| Struktur | Wann einsetzen |
|----------|----------------|
| **Five-Act-Arc** | Change-Proposals, interne Pitches, strategische Initiativen |
| **SCQA** | Executive-Briefings, Consulting-Empfehlungen, Board-Updates |
| **Problem-Solution** | Produkt-Pitches, Sales-Präsentationen, Feature-Proposals |
| **Sparkline** | Vision-Keynotes, Kulturwandel, inspirierende Vorträge |
| **Data-driven** | Research-Präsentationen, analytische Reports, Evidenz-Briefings |
| **Journey / Chronologisch** | Unternehmens-Retrospektiven, Case Studies, Gründungsgeschichten |

### Das Publikum ist der Held — nicht der Sprecher

Das ist der häufigste strukturelle Fehler in Präsentationen: Der Sprecher macht sich selbst zur Hauptfigur.

*Schwach (Sprecher als Held):*
> „Unser Tool hat die schnellste Pipeline auf dem Markt, gebaut von Top-Ingenieuren."

*Stark (Publikum als Held):*
> „Ihr verbringt jeden Freitagabend mit manuellen Deployments und seid die Letzten, die das Büro verlassen. Das ändert sich mit einem Klick."

Der Skill hält das Publikum konsequent im Zentrum — und positioniert den Sprecher als Mentor, der dem Publikum das Werkzeug reicht, sein Problem zu lösen.

### 10 Regeln für Folieninhalt und -struktur

Abgeleitet aus Kognitionswissenschaft und Präsentationsforschung (Paivio, Mayer, Zeigarnik, Von Restorff) — gruppiert in drei Bereiche:

**Umfang:** Eine Idee pro Folie · ~1 Minute pro Folie · Überschriften schlussfolgern · nur was gesprochen wird

**Inhaltsstrategie:** Zeigen statt behaupten · keine kognitive Überlast · verständlich ohne Narration

**Aufmerksamkeit & Gedächtnis:** Kernbotschaft zuerst · früh einen Loop öffnen · das Muster einmal brechen

---

## Was der Skill nicht abdeckt

Visuelle Gestaltung gehört in spezialisierte Design-Skills:

- Typografie, Schriftgrößen und -gewichte
- Farbpaletten und Kontrastverhältnisse
- Bühnen- und Projektionsbeschränkungen
- Layout-Grids, Abstände und Padding

**Dieser Skill beantwortet: Was gehört auf die Folie, und wie ist der Vortrag strukturiert — nicht: wie sieht er aus.**

---

## Installation

### Via Marketplace (empfohlen)

Marketplace einmalig hinzufügen und Plugin installieren:

```
/plugin marketplace add https://github.com/3m5suchandt/effective-slides-skill
/plugin install slides@slides-marketplace
```

### Skill aufrufen

Sobald das Plugin geladen ist:

```
/slides:effective-presentation
```

Claude fragt nach Ziel, Publikum und Format — und leitet daraus den passenden Aufbau ab.

---

## Warum ein Skill statt eines einmaligen Prompts?

Ein Prompt wird einmal angewendet. Ein Skill wird in jede Claude-Code-Session geladen, in der an einer Präsentation gearbeitet wird — die Prinzipien wirken konsistent über Projekte und Sitzungen hinweg.

Der Skill erzwingt außerdem Disziplin beim Scope: Er deckt ausschließlich Inhalt und Struktur ab. Für visuelle Gestaltung existieren separate Skills (`/ui-ux-pro-max`, `/frontend-design`).
