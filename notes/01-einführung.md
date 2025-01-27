# Einführung

Hier sind meine Notizen zur Einführung in Daten.
Was ist Redundanz?
Was sind die Vor- und Nachteile von Redundanz?
Vorteile: Gut, um alle Inforationen zu haben
Nachteile: Blockiert viel Speicherplatz; Informationen müssen stetig wieder angepasst werden;

OBJEKTE
Ball-Aufgabe evtl für Prüfung relevant

KOMPLEXE DATEN
Verschachtelung lohnenswert: 
```
JSON
 {
"vorname": Ronja
"nachname" Ramseier
"familienmitglieder": 
{
"mutter":
"vater":
"schwester":
"katze1": Katana
"katze2": Fluffy
}
}
```

Klasse = Bauplan für Objekt, beschreibt ohne Werte Eigenschaften des Objekts
```
JSON
class Animal {
art
spezies
lebensraum
lebensdauer
}
{
"art": Säugetier
"spezies": Katze
"lebensraum": Land
"lebensdauer": ca 15 Jahre
}
{
"art": Fisch
"spezies": Koi
"lebensraum": Wasser
"lebensdauer": ca 25-35 Jahre
}
{
"art": Reptil
"spezies": Salamander
"lebensraum": Land und Wasser
"lebensdauer": 20-50 Jahre
}
```

Vererbung = Übernahme von Eigenschaften eines vorherigen Objekts
Instanz der Klasse Hund (Beispiel Prüfungsfrage)
Erklärung, weshalb Vererbung praktisch ist
