# Notenrechner

# Projekt-Dokumentation

Name: Sathana Suganthasri

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 06.10.2023 | 0.0.1     | Projekt fertig erstellt.|
| 06.10.2023 | 0.0.2     | Dokumentation fertig erstellt.|


## 1 Informieren

### 1.1 Ihr Projekt

In meinem Projekt geht es darum, dass man Noten eingeben und am Schluss den Ergebnis angezeigt werden. 

### 1.2 Anforderung

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1 | muss | Funktion | Als benutzer möchte ich, dass man Noten eingeben kann. |
| 2  | muss | Qualität | Das Programm soll in C# geschrieben werden.|
| 3  | muss | Funktion | Die Fehlermeldungen sollen abgefangt werden.|
| 4  | muss | Funktion | Man kann nur Zahlen von 1 bis 6 eingeben können.|
| 5  | muss | Funktion | Es muss am Anfang eine Begrüssung haben.|
| 6  | muss | Funktion | Am Schluss muss eine Bewertung angezeigt werde. Also es wird gesagt, ob meine Noten sehr gut, gut, genügendend oder ungenügend sind.|
| 7 | muss| Qualität| Es sollen passende farben haben.|



### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Spiel startet | Person 1 klickt ein Figur und bewegt sie. | Gegner ist dran.|
| 3.1  | Spiel startet | Person 1 klickt ein Figur und wählt auf ein grünes Feld. | Figur bewegt sich.|
| 5.1  | Spiel startet | Person 1 klickt den Turm (Zombie mit violette Hose und Erwachsen aussieht).| Der Turm kann nur Horizontal und Vertikal bewegen. |
| 6.1  | Spiel startet | Person 1 klickt den Bauer (Zombie mit violette Hose und wie ein Kind aussieht.)| kann nur zwei Schritt vorwärts bewegen.|
| 7.1 | Spiel läuft | Person 1 klickt seine Figur auf den Gegner seine Figur. | Gegners Figur verschwindet.|
| 8.1 | Spiel startet | Person 1 klickt sein Figur. | Wege werden in grün angezeigt.|
| 9.1 | Spiel beendet | Person 1 klickt Restart. | Das Spiel wird neu gestartet.|
| 9.1  | Spiel beendet | Person 1 klickt Exit. | Das Spiel schliesst.|

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A | 13.09.2023 | Nicola | für Zwei Spieler erstellen | 45min |
| 2.A | 13.09.2023 | Carina | Darstellung/ Design | 2 x 45min |
| 3.A | 18.10.2023 | Ava & Nicola | Figuren Bewegung | 50 min|             |
| 4.A | 18.10.2023 | Ava & Sathana | Zwei Untersciedlichkeit der Figur | 20 min | |
| 5.A | 18.10.2023 | Sathana | Schachregel | 60 min|
| 6.A | 01.11.2023 | Sathana | Figuren Eigenschaften | 70 min |
| 7.A | 01.11.2023 | Nicola | Figuren verschwindet, nach dem sie geschlagen wurde.| 90min |
| 8.A | 01.11.2023 | Sathana | man klickt eien Figur und es werden die Richtungen  in grün angezeigt. | 45 min|
| 9.A | 01.11.2023 | Nicola | Restart button | 45 min |

Total: 9


## 3 Entscheiden

Notenrechner im Visual Studio.


## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  | 05.10.2023 | Sathana | 45 min | 2x 45min |
| 2.A  | 05.10.2023 | Sathana | 2x 45min |12x 45min |
| 3.A  | 05.10.2023 | Sathana | 50min | 3x 45min |
| 4.A  | 05.10.2023 | Sathana | 20min | 2x 45min|
| 5.A  | 05.10.2023 | Sathana | 60min | 2x 45min |
| 6.A  | 05.10.2023 | Sathana | 70min | 3x 45min |
| 7.A  | 05.10.2023 | Sathana | 90min | 2x 45min |
| 8.A  | 05.10.2023 | Sathana | 45min | 50min |
| 9.A  | 05.10.2023 | Sathana | 45min | 3x 45min |


## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  | 06.10.2023 | OK | Sathana |
| 3.1  | 06.10.2023 | OK | Sathana |
| 5.1  | 06.10.2023 | OK | Sathana |
| 6.1  | 06.10.2023 | OK | Sathana |
| 7.1  | 06.10.2023 | OK | Sathana |
| 8.1  | 06.10.2023 | OK | Sathana |
| 9.1  | 06.10.2023 | OK | Sathana |
| 9.1  | 06.10.2023 | OK | Sathana |


Das Spiel wurde im HP Windows 11 Pro getesten und funktioniert fehlerfrei.

