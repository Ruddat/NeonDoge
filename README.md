# NeonDoge / Void Runner

Ein kleines, schnelles **HTML5-Canvas-Endless-Shooter-Game** im Neon-Arcade-Stil.

Du steuerst ein Raumschiff durch wechselnde Void-Sektoren, sammelst Powerups, wählst Upgrades, kämpfst gegen Gegnerwellen, Würmer und Bossgegner – und versuchst so lange wie möglich zu überleben.

## Jetzt spielen

**Live-Version:**  
[https://ruddat.github.io/NeonDoge/](https://ruddat.github.io/NeonDoge/)

## Screenshot

> Screenshot folgt. Das Spiel läuft direkt im Browser über `index.html`.

## Gameplay

Void Runner ist als Endlosspiel aufgebaut. Der Score steigt durch zerstörte Gegner, Würmer und Bossgegner. Sobald genug Punkte erreicht sind, steigt das Level. Mit jedem Level wird das Spiel schneller, dichter und aggressiver.

Beim Level-Up erscheint ein Upgrade-Menü. Dort wählst du eine Verbesserung für dein Schiff. Zusätzlich ändert sich je nach Level der komplette Hintergrund-Sektor.

## Features

- HTML5-Canvas-Spiel ohne Framework
- direkt spielbar im Browser
- Endless-Runner-/Shooter-Loop
- dynamische Level-Ups
- Upgrade-Auswahl nach Levelwechsel
- Waffen-Cooldown-System
- gedeckelte permanente Upgrades
- temporäre Powerups mit Ablaufzeit
- Gegnerwellen mit steigender Schwierigkeit
- Wurmgegner mit Segmenten
- Bossgegner mit Rage-Phase
- dynamische Level-Biome
- Parallax-Deko und Speedlines
- Screen-Shake und Explosionseffekte
- Entity-Limits gegen Performance-Probleme

## Steuerung

| Aktion | Steuerung |
|---|---|
| Schiff bewegen | Maus bewegen |
| Schießen | Linke Maustaste halten |
| Upgrade wählen | Karte im Level-Up-Menü anklicken |

## Level-Biome

Das Spiel wechselt je nach Level in unterschiedliche Sektoren. Jeder Sektor bringt eigene Farben, Hintergrundeffekte und leichte Gameplay-Modifikatoren mit.

| Zone | Stil |
|---|---|
| Neon Orbit | klassischer Neon-Weltraum mit Ringen |
| Crimson Rift | rote Rift-Zone mit aggressiverem Look |
| Toxic Nebula | grüne Nebelzone mit organischem Effekt |
| Violet Grid | violetter Cyber-Grid-Sektor |
| Solar Wreckage | orangefarbene Trümmerzone |
| Ice Void | kalte blaue Kristallzone |

## Upgrades

Permanente Upgrades bleiben aktiv, sind aber bewusst gedeckelt, damit der Bildschirm nicht endlos voll läuft.

| Upgrade | Effekt |
|---|---|
| Satellit | Drohne kreist um den Spieler und schießt automatisch |
| Magnet | zieht Powerups aus größerer Entfernung an |
| Großkaliber | erhöht Projektilgröße und Schaden |
| Turbo | verbessert die Steuerreaktion |
| Heilung | stellt Lebenspunkte wieder her |
| Mehrschuss | erhöht die Anzahl gleichzeitiger Projektile |
| Kühlkörper | reduziert den Waffen-Cooldown |

## Powerups

Temporäre Powerups laufen nach wenigen Sekunden ab. Dadurch bleibt das Spiel kontrollierbar und eskaliert nicht unbegrenzt.

| Powerup | Effekt |
|---|---|
| Health | heilt das Schiff |
| Rapid Fire | erhöht kurzzeitig die Schussrate |
| Shield | macht kurzzeitig unverwundbar |
| Spread | erweitert kurzzeitig den Schusswinkel |
| Bomb | räumt Gegner und Projektile auf dem Bildschirm ab |

## Gegner

- Standard-Gegner mit steigendem Tempo und mehr Lebenspunkten
- Hazard-/Minengegner in bestimmten Biomen
- Wurmgegner mit mehreren Segmenten
- Bossgegner alle paar Level
- Boss-Rage-Phase bei niedriger HP

## Technik

Das Projekt ist bewusst simpel gehalten:

- **HTML**
- **CSS**
- **Vanilla JavaScript**
- **HTML5 Canvas**
- keine externen Libraries
- keine Build-Pipeline
- keine Server-Abhängigkeit

Die komplette Spiellogik befindet sich aktuell in:

```text
index.html
```

## Lokal starten

Repository klonen:

```bash
git clone https://github.com/Ruddat/NeonDoge.git
cd NeonDoge
```

Dann `index.html` direkt im Browser öffnen.

Alternativ mit einem kleinen lokalen Server:

```bash
python -m http.server 8000
```

Danach öffnen:

```text
http://localhost:8000
```

## GitHub Pages

Das Spiel ist für GitHub Pages geeignet, weil es nur aus statischen Dateien besteht.

Aktuelle Live-Adresse:

```text
https://ruddat.github.io/NeonDoge/
```

## Aktueller Status

Spielbar und aktiv in Entwicklung.

Der aktuelle Fokus liegt auf:

- besserem Spielgefühl
- mehr Abwechslung pro Level
- sauberer Performance bei hoher Gegner- und Projektilzahl
- besserem Bossdesign
- Arcade-Feeling mit mehr visueller Wucht

## Roadmap

Mögliche nächste Schritte:

- Startscreen statt sofortigem Spielstart
- Game-Over-Screen ohne Browser-Alert
- lokales Highscore-System
- Soundeffekte für Schüsse, Explosionen und Powerups
- Hintergrundmusik pro Biome
- weitere Boss-Typen
- zusätzliche Gegnertypen
- mobile Steuerung
- echte Sprite-Grafiken statt reinem Canvas-Shape-Rendering
- Balancing-Pass für Level 10+

## Projektidee

NeonDoge / Void Runner ist ein kleines Arcade-Experiment: schnell starten, sofort spielen, direkt Feedback sehen und Stück für Stück zu einem besseren Browsergame ausbauen.

Kein Login. Kein Installer. Kein Build. Einfach öffnen und loslegen.

---

Made with Canvas, Neon und etwas Chaos.
