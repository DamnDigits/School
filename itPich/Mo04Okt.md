# Aufgabe 1 

## Vorteile Hardware-RAID

1. Hohe geschwindigkeit
2. Extra Festplattencache

## Nachteile Hardware-RAID

1. Hohe Kosten

## Vorteile Software-RAID

1. Niedrige Kosten da kein Controller Notwendig

## Nachteile Software-RAID

1. CPU muss die aufgabe des Controllers übernehmen

# Aufgabe 2

| RAID-Level    | Mindestanzahl Laufwerke  | Anzahl möglicher defekter laufwerke   | Ausnutzung Festplattenkapazität in % |
| ------------- |:------------------------:|:-------------------------------------:| ---------:|
|0|2|0|100|
|1|2|1|50|
|10|4|2|50|
|5|3|1|67|
|6|4|2|50|

# Aufgabe 3

## Arbeitsweise RAID 5

bei einem RAID 5 System Speichern 2 von 3 Platten die Daten während die Dritte Platte Durch speichern von Checksummen für die ausfallsicherheit sorgt.

## Arbeitsweise RAID 6

bei einem RAID 6 System Sind die helfte Der zum einsatz kommenden Festplatten für das Speichern der Daten zuständig die andere Hälft ist für die Prüfsummen reserviert.

# Aufgabe 4

### Wie viele Festplatten brauche ich für 2TB Nutzdaten bei einer Stückgrösse von 500gb

### `Raid 1`
8 Fesplatten a 500GB

### `Raid 5`
5 Fesplatten a 500GB

### `Raid 10`
8 Fesplatten a 500GB

# Aufgabe 5

Ein RAID 15 System ist ein RAID 5 System welches als subsystem jeweils ein raid 1 system hat  
Mindestanzahl platten: `6` 

Vorteil: Hohe ausfallsicherheit
Nachteil: hohe kosten

# Aufgabe 6
In GB: 1500
in prozen: 1500 von 1750

# Aufgabe 7 
