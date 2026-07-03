# Immobilienfinanzierung Rechner

Ein statischer Rechner zur groben Simulation von Immobilienfinanzierung, Kaufnebenkosten, Eigenkapitalbedarf, Monatsrate, Sondertilgung und vorzeitiger Ablösung. Die Oberfläche unterstützt Deutsch, Englisch und Chinesisch. Deutsch ist die Standardsprache.

## Haftungsausschluss

Alle Annahmen und Informationen in diesem Rechner basieren auf allgemein zugänglichen Online-Informationen und vereinfachten Modellrechnungen. Die Ergebnisse dienen ausschließlich als grobe Schätzung und Orientierung.

Dieses Tool ersetzt keine Finanzierungsberatung, keine Steuerberatung, keine Rechtsberatung und kein verbindliches Bankangebot. Für die Richtigkeit, Vollständigkeit oder Nutzbarkeit der Ergebnisse wird keine Haftung übernommen.

## Verwendung

1. Öffne `index.html` direkt im Browser.
2. Wähle oben rechts die Sprache: Deutsch, English oder 中文.
3. Trage Kaufpreis, gewünschtes Bankdarlehen oder eingesetztes Eigenkapital sowie aktuelle liquide Mittel ein.
4. Prüfe und passe Kaufnebenkosten wie Grunderwerbsteuer, Notar/Grundbuch, Makler und fixe Zusatzkosten an.
5. Trage Sollzins, Tilgung, Zinsbindung und Simulationsdauer ein.
6. Optional: Sondertilgung oder vorzeitige Ablösung simulieren.
7. Nutze die Übersicht, die jährliche Rückzahlungstabelle und den Vergleichsbereich zur Orientierung.
8. Bei Bedarf kann ein Datensatz als JSON exportiert und später wieder importiert werden. Lokale JSON-Dateien werden durch `.gitignore` nicht ins Repository aufgenommen.

## Git-Hinweis

Die Datei `.gitignore` ignoriert `*.json`, damit gespeicherte Rechner-Datensätze oder lokale Szenarien nicht versehentlich hochgeladen werden.
