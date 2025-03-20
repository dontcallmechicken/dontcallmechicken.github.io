---
date: 2025-03-20T02:48:12+01:00
lastmod: 2025-03-20
# image: ""
showTableOfContents: true
title: "Live Schachturnier"
description: "Erstes Schachturnier im Gockel Strøm"
tags: ["schach","schachturnier","stroem",]
type: "post"
draft: false
---

# Kleines Schachturnier
- Organisation: Elmo aka KnOOspa, Freeze und Gockel
- Veranstalter/Moderator: Der olle Gockel
- Kommentator: ? wird noch gesucht, bitte melden!  
Wenn sich kein Kommentator findet, können auch Teilnehmer abwechselnd zwischen ihren Partien die aktuell gespielte Partie zusammen mit dem Gockel kommentieren.

## Austragung
Während der Echtzeitübertragung beim Gockel auf dem [Twitch Kanal *DontCallMeChicken*](https://www.twitch.tv/dontcallmechicken)
- Donnerstag, 20. März 2025
- ca. 20:00 Uhr


## Ausführung
Schachserver/-webseite: [Chess.com](https://www.chess.com/).  
Mit dem [Freundschaftslink von Gockel](https://link.chess.com/friend/zegRb1), findet eine direkte und automatische Befreundung statt.

Da das integrierte Turniersystem bei Chess.com nicht optimal für unser Turnier ist, werden Einzelpartien  gespielt.
Diese sollten am besten über die **Freundesliste** gestartet werden.  
Alternativ:
1. Spieler A startet Partie
2. Spieler A lädt Spieler B zur Partie ein
3. Spieler B tritt der Partie bei
4. Link zur Partie (Adresszeile Browser) an Gockel senden

## Schachvariante
Standard, Blitzschach.
- 3 - 7 Minuten
- individuell nach Einigung der Kontrahenten

## Turniersystem
Turnier nach Schweizer System[^1].
- 4 Runden

- Spiel-Punkte:
  - Gewonnen 1
  - Verloren 0
  - bei ungerader Teilnehmeranzahl: Aussetzen (Bye) 0.5

### Tie Breaks
Zur Wertung der Ergebnisse sind im Turniermanagement diese Tie Breaks eingestellt:
  - Direct Encounter
  - Buchholz Cut 1[^2]
  - Buchholz Total[^3]

Reihenfolge der Tiebreak-Kriterien (Order of tiebreak criteria[^4]):
> For Swiss tournaments for individuals (not teams), FIDE's 2019 recommendations are:
> 1. Buchholz Cut 1 (the Buchholz score reduced by the lowest score of the opponents);
> 2. Buchholz (the sum of the scores of each of the opponents of a player);
> 3. The greater number of wins;
> 4. The greater number of wins with Black pieces, not counting forfeits.

## Turniermanagement
Das Turnier wird über die Webseite von [SwissSystem.org](https://swisssystem.org/) verwaltet.  

### Turniertabelle
Die [Rangliste](https://swisssystem.org/full-standings/bb17bfec2ff9424d9ceb5be219c91e6d) zum Turnier wird automatisch aktualisiert.

:information_source: Falls Werbebanner unter der Tabelle angezeigt werden, können diese über ein Menü (drei untereinanderliegende Punkte) *direkt im Banner* deaktivert und ausgeblendet werden.

#### OBS Browserquelle
Möchte man die Turniertabelle als Browserquelle in OBS[^5] integrieren, empfiehlt es sich unter `Benutzerdefiniertes CSS` folgendes zu ergänzen:

Sorgt dafür, dass der Hintergrund transparent[^6] ist und nur die Tabelle angezeigt wird:
```css
ant-layout { background-color: rgba(0, 0, 0, 0); }
``` 

Optional, Anpassung des äußeren Rahmens[^7] der Tabelle:
```css
table { border: 3px solid black; }
```

[^1]: https://de.wikipedia.org/wiki/Schweizer_System#Anwendung_beim_Schach
[^2]: https://de.wikipedia.org/wiki/Feinwertung#Verfeinerte_Buchholz-Wertung_(Buchholz-Buchholz-Wertung)
[^3]: https://de.wikipedia.org/wiki/Feinwertung#Buchholz-Wertung
[^4]: https://en.wikipedia.org/wiki/Tie-breaking_in_Swiss-system_tournaments#Order_of_tiebreak_criteria
[^5]: https://obsproject.com/kb/browser-source
[^6]: https://www.w3schools.com/Css/css_colors.asp
[^7]: https://www.w3schools.com/css/css_border_shorthand.asp
