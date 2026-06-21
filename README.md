# OS – Pipeline System (v1.0)

Dieses Repository enthält ein minimales OS-Pipelinesystem bestehend aus:

- Pipeline 0 (index.html)
- Pipeline 13 (13.html)
- OS-Statusmodul (os13.js)

## Zweck
OS dient als einfacher Übergabepunkt zwischen zwei Pipeline-Stufen.
Es zeigt an, ob das System aktiv ist und ob Frames angenommen werden.

## Struktur
- **index.html**  
  Startpunkt. Öffnet Pipeline 13.

- **13.html**  
  Live-Ansicht. Zeigt den aktuellen OS-Status.

- **os13.js**  
  Setzt den Status-Text und signalisiert, dass Pipeline 1+2 bereit sind.

## Interne Marker
Das System unterstützt interne Marker wie:
- ID
- EICH
- GEN
- MODE

Diese Marker werden nicht öffentlich angezeigt, können aber über URL-Parameter übergeben werden.

## Formeln
Das System erlaubt interne Formdarstellungen (z. B. Würfel/Pyramide) als logische Modelle.
Diese Modelle haben keine grafische oder physische Funktion, sondern dienen nur als interne Struktur.

## Version
v1.0 – Minimal, stabil, kompatibel.

