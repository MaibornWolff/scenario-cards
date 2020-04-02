# Szenario # 
"Auswahl eines Zielortes im Navigationssystem"

## Standardfall
Auswahl des Zielortes über eine ABC-Liste von Orten

## Alternative
Eingabe des Zielortes über ein Freitextfeld

## Ausnahme
Das Navigationssystem hat den eingegebenen Zielort (Abweichung vom Alternativszenario) nicht im Datenbestand 
vorrätig. 

Es informiert darüber den Benutzer und ersucht ihn, einen anderen Zielort in der Nähe des ursprünglichen Zielorts einzugeben.

## Negativfall
Der Benutzer gibt Zahlen (z.B. Repräsentant von Geo-Koordinaten) statt Buchstaben in das Freitextfeld ein.
 
Das System kann die numerische Eingabe nicht verarbeiten, startet daher keine Suche nach dem Zielort im Datenbestand und fordert den Benutzer auf, seine Eingabe nochmals zu überprüfen und für die Zielorteingabe nur Buchstaben zu verwenden.

## Missbrauch
Der Benutzer gibt für den Zielort in das Freitextfeld mehr Buchstaben ein, als zulässig sind bzw. vom Navigationssystem verarbeitet werden können. 

Das System stürzt nicht ab und fordert den Benutzer auf einen Zielort mit max. n Zeichen einzugeben.