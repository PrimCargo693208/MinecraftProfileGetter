# MinecraftProfileGetter

![image](Terminal-1115x628.png)
[<svg xmlns="http://www.w3.org/2000/svg" width="78" height="20" role="img" aria-label="⭐: If Useful"><title>⭐: If Useful</title><linearGradient id="s" x2="0" y2="100%"><stop offset="0" stop-color="#bbb" stop-opacity=".1"/><stop offset="1" stop-opacity=".1"/></linearGradient><clipPath id="r"><rect width="78" height="20" rx="3" fill="#fff"/></clipPath><g clip-path="url(#r)"><rect width="21" height="20" fill="#555"/><rect x="21" width="57" height="20" fill="#bc4e99"/><rect width="78" height="20" fill="url(#s)"/></g><g fill="#fff" text-anchor="middle" font-family="Verdana,Geneva,DejaVu Sans,sans-serif" text-rendering="geometricPrecision" font-size="110"><text aria-hidden="true" x="115" y="150" fill="#010101" fill-opacity=".3" transform="scale(.1)" textLength="110">⭐</text><text x="115" y="140" transform="scale(.1)" fill="#fff" textLength="110">⭐</text><text aria-hidden="true" x="485" y="150" fill="#010101" fill-opacity=".3" transform="scale(.1)" textLength="470">If Useful</text><text x="485" y="140" transform="scale(.1)" fill="#fff" textLength="470">If Useful</text></g></svg>](https://github.com/PrimCargo693208/MinecraftProfileGetter)

MinecraftProfileGetter ist ein Tool zum Abrufen von Minecraft Profilen.

## Features

MinecraftProfileGetter bietet folgende Features:
- Abfragen der UUID des Spielers
- Abfragen der Skintextur des Spielers
- Rückgabe als JSON-Objekt
- Rückgabe als Klartext

## Installation

Installation wird nicht benötigt. Einfach den ZIP-Ordner entpacken.

## How to use

Es gibt mehrere verschiedene Modi, mit denen die Daten abgerufen werden können. 

### Hilfe

Zeigt die Hilfeseite an.

1. Starte die Datei `start_help.bat`

### Normal

Gibt die Spielerdaten als Text aus.

1. Starte die Datei `start.bat`
2. Gebe den Spielernamen ein
3. Drücke [Enter], um das Programm neuzustarten, oder gebe "exit" ein und drücke [Enter], um das Programm zu beenden.

### RAW

Gibt die Spielerdaten als JSON-Objekt aus.

1. Starte die Datei `start_raw.bat`
2. Gebe den Spielernamen ein
3. Drücke [Enter], um das Programm neuzustarten, oder gebe "exit" ein und drücke [Enter], um das Programm zu beenden.

### Clear on exit

Analog zum normalen Modus, aber mit der Ergänzung, dass sich das Terminal bei Programmende automatisch  leert.

1. Starte die Datei `start_clear.bat`
2. Gebe den Spielernamen ein
3. Drücke [Enter], um das Programm neuzustarten, oder gebe "exit" ein und drücke [Enter], um das Programm zu beenden und das Terminal zu leeren.

### Terminal

Oder tippe den Befehl einfach manuell im Terminal ab! \
`java -jar MinecraftProfileGetter.jar`

Führe den folgenden Befehl aus, um eine Hilfsseite zu erhalten: \
`java -jar Minecraftprofilegetter.jar -h`

## Deinstallation

Lösche den Ordner.

## Credits

Danke an
- **[stleary](https://github.com/stleary):** [org.json](https://github.com/stleary/JSON-java)
  ![image](https://github.com/stleary/JSON-java/blob/master/images/JsonJava.png?raw=true)

<a href="https://github.com/PrimCargo693208/MinecraftProfileGetter/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=PrimCargo693208/MinecraftProfileGetter" />
</a>
