# Anforderungen

## Benutzerinteraktionen
- Espresso, Latte, Cappuccino
- Falsche oder ungültige Eingaben abgreifen

## Ausschalten des Automats
- Zum Ausschalten der Befehl `off`
- Das Wartungspersonal hat extra Befehle mit Passwort

## Statusbericht
- Mit `report` geben wir einen Statusbericht aus
- Angezeigte Ressourcen (Beispiel):
  ```
    Water: 150ml
    Milk: 50ml
    Coffee: 75g
    Money: 35,50€
  ```

## Zustandsprüfung
- Sind Zutaten vorhanden?
- Benutzerfreundliche Meldung ausgeben, falls Zutaten nicht vorhanden

## Bezahlvorgang
- Vorher Zutaten prüfen
- Nur Münzen erlaubt: `5ct | 10ct | 20ct...`
- Annahme: Der Automat hat unendlich viel Rückgeld
- Prüfen ob echtes Geld
- Benutzer kann jederzeit Bezahlvorgang abbrechen

## Getränkezubereitung
- Erst nach erfolgreicher Zahlung
- Zutaten werden aufgebraucht

## Verbrauch der Zutaten
- Espresso:
  - 15 g Kaffee
  - 50 ml Wasser
  - 100 ml Milch

## Wartungsbefehle
- `Fill milk`: Milchvorrat zurücksetzen
- `Fill water`
- `Take money`
 
 # Flowchart für die Anwendung
 <img src="\images\Kaffeeautomat_flowchart.png" alt="Flowchart Kaffeeautomat" width=60%>

# Allgemeines zu CPS
  <img src="\images\CPS.png" alt="CPS" width=60%>