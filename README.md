# Coding Dojo 2024
Thema: Generative KI Modelle in der Softwareentwicklung

## Warnung: Datenschutz und Rechtliches
* Niemals private Daten in einem öffentlichen Repository speichern.
* Niemals private Daten an Dritte weitergeben, das gilt auf für generative KI Modelle.
* Daten, die euch nicht gehören, dürfen nicht verwendet werden.
* Der Autor dieser Zeilen ist kein Anwalt und gibt keine Rechtsberatung.

## Idee für dieses Dojo
Irgendwie mit KI Unterstützung was bauen. 
Erfahrung sammeln. 
Üben mit der KI Unterstützung umzugehen.
"Total" darauf einlassen.

Das, was man nutzt, bestmöglich (im Sinne des Erfinders) nutzen:
- Web-IDE von einem Anbieter (e.g. Github -> Codespaces)
- IDE-Integration von einem Anbieter (e.g. Github Copilot)
- ChatGPT neben deiner IDE
- Was immer du noch dabei hast/nutzt ...
- 

### Anleitung zum Einrichten von Github Copilot in Codespaces
- Registriere dich bei Github und melde dich an
- Forke dieses Repository
- Aktiviere CoPilot in deinem Konto (Testversion)
- Datenschutzeinstellungen.
- Öffne den Fork dieses Repos als Codespace in Github
- Installiere die Copilot-Erweiterung: 

## Einige Hinweise
- Selektion, offene Dateien, offene Projekte, alles ist wichtig und kann als Kontext berücksichtigt werden.
- CoPilot basiert auf Trainingsdaten aus 2021 und einem GPT-4 Modell von OpenAI.
- Kleine Schritte sind besser als große Schritte.
- CoPilot lernt von dir, also gib ihm Feedback (wenn du das willst)

## Iteration 1 - Erst Test dann Funktionen. 

Erzeuge eine Java-Klasse unter Test mit dem Namen CalculatorTest.

Gibt per */tests* den Befehl Tests zu erzeugen.

Nutze die Reparatur-Vorschläge der IDE und CoPilot um die Funktionalität zum Test zu erzeugen.

Wiederholen mit weiteren Funktionen, die ggf. im CalculatorTest noch fehlen.

## Iteration 2 - Erst die Funktion dann den Test.

Erzeuge eine Java-Klasse (in main) mit dem Namen PrimeCalculator.
Erzeuge eine Funktion isPrime(int n) die true zurückgibt, wenn n eine Primzahl ist.
...
Ende mit dem Test durch Befehle */tests*.

## Iteration 3 - Repariere mir meinen Code! 
Nimm irgendein Stück des bisherigen Codes und erzeuge einen Fehler.

Markiere den Code und gib CodeCopilot den Befehl */fix*.

## Iteration 4 - Code Vervollständigung vs. Vorschläge vs. Chat

* Explizit ausprobieren.
  * z.B. Automatische Code-Completion anschalten/abschalten.
* Iterationen wiederholen.

## Iteration 5 - Erkläre mir den Code!
Markiere den Code und gib CodeCopilot den Befehl */explain*
Modus: Zeile für Zeile.

* Auf den Ergebnissen aus Iteration 1-4.
* Auf dem WeatherForecast Beispiel.
* 

## Iteration 6 - Dokumentiere meinen Code!

Nutze die Dokumentationsfunktion von CoPilot: */doc* auf dem erzeugten Code Iteration 1-5.

## Iteration 7 - Make it simple!

Nutze die Vereinfachungsfunktion von CoPilot: */simplify* auf dem erzeugten Code Iteration 1-5.

## Iteration 8 - Beispieldaten

Probiere die Datengenerierungsfunktion von CoPilot zur Erzeugung von Testdaten.

## Iteration 9 - Namen und Texte

Überprüfe die Namensgebung von Variablen und Funktionen. 
Ggf. auch Texten.
Lass die Vorschläge anzeigen.

Wenn in deinem Programm Exception-Handling vorkommt, dann experimentiere mit den Texten der Exceptions.
