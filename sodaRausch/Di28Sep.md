# Aufgabe 1 Infoblatt Normalisierung

## folgende Probleme
+ einfügeanomalien
+ Änderungsanomalien
+ Löschanomalien
  
## Auftrag 1 normalform erstellen
#
***Tabelle mitglieder***
| M.            | VorName            | Nachname  | MW    | Straße | Ort | PLZ     |
| ------------- |:------------------:| :-------: |:-----:|:------:|:---:|--------:|
|1|Marco|Fieker|m|halenerstrasse 73| duisburg|47198|
|2|urlich |becker|m|ottoweg| duisburg|47198

***Tabelle Sportarten***
| SportartenID  | Sportart           | beitrag   |
| ------------- |:------------------:| ---------:|
|1|H|110,00|
|2|S|160,00|
|3|L|110,00|

***Tabelle MitgliederSportarten*** `verknüpfungstabelle`
| MID           | SportartenID       |
| ------------- | ------------------:|
|1              |1                   |
|2              |1                  |
|3              |3                  |
