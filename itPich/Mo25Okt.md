# Datensicherung
+ Datensicherung Blatt 1 pdf
+ Datensicherung Blatt 2 pdf
  

<table border="1">
  <caption>Aufgabe 1</caption>
  <thead>
    <tr>
     <th>Aussage</th>
     <th>Richtig</th>
     <th>Falsch</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td colspan="">Datensicherung ist dasselbe wie Datensicherheit</td>
      <td colspan=""></td>
      <td colspan="">X</td>
    </tr>
    <tr>
      <td colspan="">Daten können auf Festplatten Magnetbänder cd dvd usb gesichert werden </td>
      <td colspan="">X</td>
      <td colspan=""></td>
    </tr>
    <tr>
      <td>Bei jeder Datensicherung werden immer alle Daten in einer Fesplatte gesichert.</td>
      <td></td>
      <td>X</td>
    </tr>
        <td>Datensicherung macht man am besten in der Mittagspause da hier die Mitarbeiter nicht arbeiten</td>
        <td></td>
        <td>X</td>
    </tr>
    </tr>
        <td>Die Sicherungsbänder des Backupservers sollen in der Nähe des Servers aufbewahrt werden damit sie schnell gewechselt werden können</td>
        <td></td>
        <td>X</td>
    </tr>
    </tr>
        <td>Die Sicherungsbänder des backupservers sollten in einem anderen Raum oder besser in einem anderen gebäude aufbewahrt werden </td>
        <td>X</td>
        <td></td>
    </tr>
    </tr>
        <td>Die Daten zu Sichern, dauert in der Regel nur wenige Minuten</td>
        <td></td>
        <td>X</td>
    </tr>
    </tr>
        <td>Datensicherung ist an jedem Arbeitstag Vorzunehmen</td>
        <td>X</td>
        <td></td>
    </tr>
    </tr>
        <td>Datensicherung ist einmal in der Woche ausreichend</td>
        <td></td>
        <td>X</td>
    </tr>
    </tr>
        <td>nach der Datensicherung werden die Daten auf den Festplatten gelöst</td>
        <td></td>
        <td>X</td>
    </tr>
  </tbody>
</table>


<table border="1">
  <caption>Table Caption</caption>
  <thead>
    <tr>
     <th></th>
     <th>Inkrementelle</th>
     <th>Differenzielle</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Vorteile</td>
      <td colspan="">Kurze Backupzeit<br> geringeres Datenvolumen<br> Kosten für speichermedien</td>
      <td colspan="">Kurze wiederherstellungszeit<br> Redundanz<br>Einfache wiederherstellung</td>
    </tr>
    <tr>
      <td>Nachteile</td>
      <td>Aufwendiger Wiederherstellung der Daten <br>Keine Redundanz</td>
      <td>Lange Backupzeit<br> Mehr Benötigter Speicher<br> höhere Kosten für Speichermedien<br></td>
    </tr>
  </tbody>
</table>

## generationsprinzip Großvater Vater Sohn

Das Grosvater Prinzip Ein sohn für jeden wochentag die wochentage werden jeden tag überschrieben die väter werden jeden monat überschrieben und die grosväter einmal im jahr 

***nochmal angucken***  


## Aufgabe 4 

siehe arbeitsblat DatensicherungBlatt2.pdf 

`Antwort`: um die Daten wieder herzustellen ist das Magnetband von mittwoch dem 20.01.2016 und das Magnetband vom 22.01.2016 notwendig.

## Aufgabe 5

Wie lange dauert das sichern von 1 TIB daten bei einer geschwindigkeit von  
`A: 360MB/s (unkomprimiert)`:  50,925 min.  
1TiB = 2^10 GiB.  
1GiB = 2^10 MiB.  
1MiB = 2^10 KiB.  
1KiB = 2^10 B

1MB =  10^3   KB
1KB =  10^3   B

`B: 900MB/S (komprimiert)`:  20,360 min

## aufgabe 6



`tägliche sicherung`:  
`bei 360MB/S`.   
500 MiB = 50,925/2 = 25,4625min   
Beginn der sicherung 4:00 uhr 
Anfange der Schicht 6:00 uhr
Zeit zum sichern 2 Stunden.  
benötigte zeit. 25min  
***Zeitüberschreitung bei derzeitiger sicherung 2,24 stunden.***.  
`bei 900MB/S`.   
500 MiB = 20,360/2 = 10,18 min.  
Beginn der sicherung 4:00 uhr 
Anfange der Schicht 6:00 uhr.  
Zeit zum sichern 2 Stunden.  
benötigte zeit 10 min.  
***puffer 0,3 stunden***

`Einmalige sicherung (Dienstag)`.  
`bei 360MB/S`.   
4 TiB = 4*50,925 = 203,7 min = 3,3 Stunden.  
beginn der sicherung dienstag 4:00 uhr   
Anfang der schicht 6:00 uhr.   
zeit zum sichern 2 stunden.  
***zeitüberschreitung bei derzeitiger sicherung 1,3 stunden***
`bei 900MB/S`.   
500 MiB = 4*20,360 = 81,44 min = 1,357 stunden.  
Beginn der sicherung 4:00 uhr   
Anfange der Schicht 6:00 uhr.  
Zeit zum sichern 2 Stunden.  
benötigte zeit 1,357 stunden.  


`Verbesserungs vorschläge`:  
+ 1 Aufwertung auf ein Bandlaufwerk mit 900 MB/s datentransfer.
+ verlegen der datensicherung auf abends nach feierabend
  um die initiale incrementelle sicherug nach der vollsicherung bewältigen zu können


