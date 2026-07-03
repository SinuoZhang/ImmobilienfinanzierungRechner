# Immobilienfinanzierung Rechner

Ein statischer Rechner zur groben Simulation von Immobilienfinanzierung, Kaufnebenkosten, Eigenkapitalbedarf, Monatsrate, Sondertilgung und vorzeitiger Ablösung. Die Oberfläche unterstützt Deutsch, Englisch, Chinesisch und Japanisch. Deutsch ist die Standardsprache.

## Haftungsausschluss

Alle Annahmen und Informationen in diesem Rechner basieren auf allgemein zugänglichen Online-Informationen und vereinfachten Modellrechnungen. Die Ergebnisse dienen ausschließlich als grobe Schätzung und Orientierung.

Dieses Tool ersetzt keine Finanzierungsberatung, keine Steuerberatung, keine Rechtsberatung und kein verbindliches Bankangebot. Für die Richtigkeit, Vollständigkeit oder Nutzbarkeit der Ergebnisse wird keine Haftung übernommen.

## Verwendung

1. Öffne `index.html` direkt im Browser.
2. Wähle oben rechts die Sprache. Zahlen verwenden Leerzeichen als Tausendertrennzeichen; das Dezimalzeichen folgt der gewählten Sprache, zum Beispiel `1 234,56` auf Deutsch oder `1 234.56` auf Englisch.
3. Trage Kaufpreis, gewünschtes Bankdarlehen oder eingesetztes Eigenkapital sowie aktuelle liquide Mittel ein.
4. Prüfe und passe Kaufnebenkosten wie Grunderwerbsteuer, Notar/Grundbuch, Makler und fixe Zusatzkosten an.
5. Trage Sollzins, Tilgung, Zinsbindung und Simulationsdauer ein.
6. Optional: Sondertilgung oder vorzeitige Ablösung simulieren.
7. Nutze die Übersicht, die jährliche Rückzahlungstabelle und den Vergleichsbereich zur Orientierung.
8. Bei Bedarf kann ein Datensatz als JSON exportiert und später wieder importiert werden. Lokale JSON-Dateien werden durch `.gitignore` nicht ins Repository aufgenommen.

## Sprachen beitragen

Die Sprachdaten liegen in `i18n.js`, damit neue Übersetzungen ohne Änderungen an der Rechnerlogik ergänzt werden können.

1. Füge den neuen Sprachcode zu `supportedLanguages` hinzu, zum Beispiel `fr`.
2. Ergänze die passende Locale in `locales`, zum Beispiel `fr: "fr-FR"`.
3. Ergänze in jedem Eintrag unter `translations` den neuen Sprachcode.
4. Falls ein Text noch fehlt, fällt der Rechner auf Deutsch zurück.

Neue UI-Texte in `index.html` müssen einen passenden Schlüssel in `i18n.js` bekommen. Das gilt für `data-i18n`, `data-i18n-placeholder` und direkte Aufrufe von `t("...")`.

## Git-Hinweis

Die Datei `.gitignore` ignoriert `*.json`, damit gespeicherte Rechner-Datensätze oder lokale Szenarien nicht versehentlich hochgeladen werden.
