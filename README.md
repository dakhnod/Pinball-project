# Flipper

## Kurzanleitung

Falls der Flipper irgendwo rumsteht, einfach am Knauf rechts vom Münzeinwurf ziehen, loslassen, die Knöpfe auf der linken und rechten Seite drücken und schauen was passiert.

## Zusammenfassung

Der Flipper wurde dem Projektteam des Studienganges "Technische Informatik" 2023 zur modernisierung übergeben.
Im Flipper vorhanden waren
- das Gehäuse
- sämtliche Elektromagneten (etwa 25 Stück)
- alle sensoren (binäre Schalter)
- der Münzeinwurf
- ein paar Mark

Im Zuge des Projektes wurde der Flipper ergäzt um
- einen Raspberry Pi (CM, samt eigenem Motherboard)
- fünf STM32 (samt eigenen Platinen)
- Infrastruktur für einen CAN bus (Ethernet Buchsen und Kabel)
- Leistungselektronik für die Ansteuerung der Elektromotoren
- software für die Ansteuerung der Aktoren und Sensoren,
- die zentrale Software für die Umsetzung der Spielelogik

## Weiterführende Links

- [zentrale Spielelogik](https://gitlab.com/flipper2/team-raspberry-pi/gamecore/-/blob/Recent_Gamelogic/main.py?ref_type=heads)
- [STM32 Trägerplatine](https://gitlab.com/flipper2/team-satellit/circuit-board/-/tree/main/Satellite?ref_type=heads)
- [Auflistung aller Sensoren und Aktoren](https://gitlab.com/flipper2/team-raspberry-pi/ItemRegistry/-/blob/main/items.yaml?ref_type=heads)
- [Raspberry PI CM4 Trägerplatine](https://gitlab.com/flipper2/team-mainboard/pcb)
- [Gesamtes Projekt](https://gitlab.com/flipper2)

## Team und Kontakt
- Johannes Hofmann (PCB und Satellit, johannes02.hofmann@t-online.de)
- Daniel Dakhno (Software, dakhnod@gmail.com)
- Jannis Gröger
- Mario Wegmann
- Tobias Hilsenbeck
- Simon Hüttinger
- Maximilian Hoffmann
- Julian Wilhelmy
- ...
