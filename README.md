# BMI-Rechner

Ein Konsolenprogramm in Python, das den Body-Mass-Index (BMI) berechnet.
Man gibt Körpergröße und Gewicht ein, und das Programm zeigt den BMI 
und die passende Einstufung an.

## Berechnung
BMI = Gewicht in kg / (Größe in m)²

| BMI | Einstufung |
|---|---|
| unter 18,5 | Untergewicht |
| 18,5 – 24,9 | Normalgewicht |
| 25 – 29,9 | Übergewicht |
| ab 30 | Adipositas |

## Was ich dabei gelernt habe
- Benutzereingaben mit `input()` und Umwandlung in Zahlen mit `float()`
- Rechnen mit Variablen
- Bedingungen mit `if` / `elif` / `else` für die Einstufung
- Ausgabe mit gerundeten Werten, z. B. mit `round()` oder f-Strings

## So startest du das Programm
1. Python 3 installieren (python.org)
2. Datei herunterladen
3. Im Terminal ausführen:

    python [dateiname].py

## Ideen für später
- Prüfen, ob die Eingaben gültig sind (z. B. keine Buchstaben, keine negativen Werte)
- Eingabe der Größe wahlweise in cm oder m
- Grafische Oberfläche
