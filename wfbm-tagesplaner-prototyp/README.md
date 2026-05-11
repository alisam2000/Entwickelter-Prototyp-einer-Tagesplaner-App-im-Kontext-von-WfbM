# Entwickelter Prototyp einer Tagesplaner-App im Kontext von WfbM

## Kurzbeschreibung

Dieses Repository enthält den entwickelten Prototyp einer webbasierten Tagesplaner-App im Kontext von Werkstätten für behinderte Menschen (WfbM).

Die Anwendung unterstützt Nutzerinnen und Nutzer durch eine visuelle Tagesstruktur, schrittweise Aufgabenführung, Erinnerungen, Planänderungen und einen einfachen Hilfezugang.

## Kontext

Der Prototyp wurde im Rahmen einer Bachelorarbeit entwickelt. Ziel ist die prototypische Darstellung einer digitalen Assistenzlösung zur Unterstützung strukturierter Arbeitsabläufe im WfbM-Kontext.

## Zielsetzung

Die App soll exemplarisch zeigen, wie digitale Unterstützungssysteme Menschen im Arbeitsalltag durch klare visuelle Orientierung, einfache Bedienung und reduzierte kognitive Belastung begleiten können.

## Hauptfunktionen

- Tagesübersicht mit mehreren Aufgaben
- Schritt-für-Schritt-Ansicht
- Bildbasierte Aufgabenführung
- Erinnerungsansicht
- Planänderungsansicht
- Pausenansicht
- Feierabendansicht
- Hilfe-Funktion
- Einstellungsbereich mit PIN-Zugang
- Reizarme Darstellungsmodi
- Kontrastmodus
- Optionale Sprachausgabe
- Verschiedene Zeitdarstellungen

## Präsentationsmodus

Der Prototyp enthält einen Präsentationsmodus. Dieser dient dazu, zentrale Anwendungsszenarien im Rahmen der Bachelorarbeit schnell und reproduzierbar vorzuführen.

Weitere Informationen: [`docs/praesentationsmodus.md`](docs/praesentationsmodus.md)

## PIN-Funktion

Der PIN-geschützte Einstellungsbereich dient im Prototyp ausschließlich der Demonstration eines geschützten Bereichs. Die PIN-Funktion ist nicht als produktive Sicherheitslösung zu verstehen.

## Projektstatus

Prototyp / Demonstrator.

Die Anwendung ist keine produktive Software, kein Medizinprodukt und wurde nicht klinisch validiert.

## Nutzung

Die Anwendung kann lokal im Browser geöffnet werden.

Dazu die Datei `index.html` im Browser öffnen.

Alternativ kann ein lokaler Server verwendet werden:

```bash
python -m http.server 8000
```

Danach im Browser öffnen:

```text
http://localhost:8000
```

## Projektstruktur

Die Projektstruktur wurde nach dem Abschnitt „Nutzung“ eingefügt, weil hier gezeigt wird, welche Dateien für Start, Darstellung und Verhalten der App relevant sind.

```text
wfbm-tagesplaner-prototyp/
├─ index.html
├─ README.md
├─ css/
│  └─ styles.css
├─ js/
│  └─ app.js
└─ docs/
   └─ praesentationsmodus.md
```

## Grenzen des Prototyps

- Keine echte Nutzerverwaltung
- Keine persistente Speicherung
- Demo-Daten sind fest im Code hinterlegt
- PIN dient nur der Demonstration
- Präsentationsmodus ist nicht Teil einer finalen Produktivversion
- Keine klinische Validierung
- Kein Medizinprodukt

## Hinweis zu UI-Texten

Einige Texte sind bewusst einfach, direkt und prototypisch formuliert. Der Fokus liegt auf Verständlichkeit, visueller Führung und reduzierter kognitiver Belastung.

## Abgabehinweis

Für die Bachelorarbeit sollte auf die konkrete Repository-Version verwiesen werden, zum Beispiel durch einen GitHub-Release oder einen Commit-Hash.
