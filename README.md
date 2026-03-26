# Testgetriebene-Entwicklung-TDD

Red – Test schreiben, der fehlschlägt (Funktion existiert noch nicht)
Green – minimalen Code schreiben, damit der Test besteht
Refactor – Code aufräumen, ohne das Verhalten zu ändern

Fast – schnell ausführbar
Independent – Tests beeinflussen sich nicht gegenseitig
Repeatable – überall gleiche Ergebnisse
Self-validating – klares Pass/Fail, kein manuelles Prüfen
Timely – Test wird vor dem Code geschrieben

Black Box – kennt nur Output
White Box - kennt nur Code
Gray BoxTeilweise – Teile von Code und Output

Unit-Tests
Solitary – alle Abhängigkeiten werden durch Mocks ersetzt
Sociable – echte Abhängigkeiten werden mitgenutzt (z. B. andere Klassen)
Mocks – gefälschte Objekte, die Verhalten simulieren und Aufrufe verifizieren

Integrationstests
Testen das Zusammenspiel mehrerer Komponenten (z. B. Service + Datenbank). Langsamer als Unit-Tests.

UI / End-to-End / Systemtests
Testen das komplette System aus Nutzersicht – vom Klick im Browser bis zur DB. Sehr langsam, fehleranfällig.
Akzeptanztests
Prüfen, ob das System die fachlichen Anforderungen erfüllt
