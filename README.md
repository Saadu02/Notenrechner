# Notenrechner

Name: Sathana Suganthasri

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 06.10.2023 | 0.0.1     | Projekt fertig erstellt.|
| 06.10.2023 | 0.0.2     | Dokumentation fertig erstellt.|


## 1 Informieren

### 1.1 Ihr Projekt

In meinem Projekt geht es darum, dass man Noten eingeben kann und später wird den Durchschnitt angezeigt mit Bewertung. 

### 1.2 Anforderung

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1 | muss | Funktion | Man muss Zahlen/Noten eingeben können. |
| 2 | muss | Qualität | Das Programm soll in C# geschrieben werden.|
| 3 | muss | Funktion | Nach jeder Eingabe, soll der Notendurschnitt zeigen. |
| 4 | muss | Funktion | Die Fehlermeldungen sollen abfangen.|
| 5 | muss | Funktion | Man kann nur Zahlen von 1 bis 6 eingeben können.|
| 6 | muss | Funktion | Es muss am Anfang eine Begrüssung haben.|
| 7 | muss | Funktion | Am Schluss muss eine Bewertung angezeigt werde. Also es wird gesagt, ob meine Noten sehr gut, gut, genügend oder ungenügend sind.|
| 8 | muss| Qualität| Es sollen passende Farben haben Anhang von Ergebnissen des Bewertungs anzeigen.|



### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1 | Programm startet | 6 | Ihr Notenschnitt ist 6. Möchten sie weitere Noten eingeben? y oder n | 
| 1.2 | Möchten sie weitere Noten eingeben | y | Geben sie ihre Note ein: |
| 3.1 | Ihr Notenschnitt ist ... Möchten sie weitere Noten eingeben | n | Ihr Noten schnitt ist und heisst .....  |
| 4.1 | Programm startet | doqjd | Ungültige Eingabe. Bitte geben sie eine Zahl ein.|
| 4.2 | Möchten Sie weitere Noten eingeben? | fojwe | Bitte geben Sie eine y oder n.|
| 5.1 | Programm startet | 10 | Bitte geben sie eine Zahl zwischen 1 bis 6. |
| 6.1 | Programm startet: Herzlich Willkommen im Notenrechner. Bitte geben sie ihre Note ein:  | 3 | Ihr Notenschnitt ist eine 3. Möchten Sie weitere Noten eingeben y oder n? |
| 7.1 | Zahlen eingegeben | n | Ihr Notenschnitt ist 3.125 und heisst ungenügend. |



## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A | 13.09.2023 | Sathana | Eingabe Noten Speicherung | 40min |
| 1.B | 13.09.2023 | Sathana | Durchschnitt Speicherung  | 30min |
| 4.A | 18.10.2023 | Sathana | Fehlermeldung abfangen | 30 min|         
| 7.A | 18.10.2023 | Sathana | Noten-Skala | 20 min |
| 8.A | 18.10.2023 | Sathana | Farbe | 15 min|
| 5.A | 01.11.2023 | Sathana | Zahl zwischen 1 bis 6 | 25 min |
| 7.B | 01.11.2023 | Sathana | Ergebnisse anzeigen| 15 min |


Total: 7


## 3 Entscheiden

Ich habe mich entschieden den Notenschnittrechner im Visual Studio zu implementieren.


## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  | 05.10.2023 | Sathana | 40min | 35min |
| 1.B  | 05.10.2023 | Sathana | 30min | 20min |
| 4.A  | 05.10.2023 | Sathana | 30min | 40min |
| 7.A  | 05.10.2023 | Sathana | 20min | 20min|
| 8.A  | 05.10.2023 | Sathana | 15min | 10min |
| 5.A  | 05.10.2023 | Sathana | 25min | 25min |
| 7.b  | 05.10.2023 | Sathana | 15min | 15min |


## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  | 06.10.2023 | OK | Sathana |
| 1.2  | 06.10.2023 | OK | Sathana |
| 4.1  | 06.10.2023 | OK | Sathana |
| 7.1  | 06.10.2023 | OK | Sathana |
| 8.1  | 06.10.2023 | OK | Sathana |
| 5.1  | 06.10.2023 | OK | Sathana |
| 7.2  | 06.10.2023 | OK | Sathana |

Das Spiel wurde im HP Windows 11 Pro getestet und funktioniert fehlerfrei.

