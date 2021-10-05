# TCP 

+ Verbindungsorientiert (d.h. gleiche empfang wie sende rheihenfolge)
+ Gewährleistet durch sequenznummern 
- Fehlt ein Paket wartet  tcp bis entweder das Paket eingetroffen ist oder eine bestimmte zeit überschritten ist ist dies der fall wird eine Fehlermeldung an den Empfänger ausgegeben
UDP
- Verbindungsloses Protokoll (kein ordnungsgemäße Erreichen der Datenpakete beim empföger gewährleistet)

````
Durch die Berechnung der squenznummer und damit verbundene Vorgänge ist tcp langsamer als Udp dafür aber genauer in fällen wo die Pakete unbedingt die richtige reheinfolge behalten müssen wie z.b. bei Daten Übertragung von Bildern oder Dateien benutzt man tcp in fällen wo mal ein packet in einer anderen Rheinfolge ankommen kann wie z.b. bei telefonie wird auf das schnellere Udo zurückgegriffen
````

Sequenznummern:
Jedes Paket erhält eine mit der Rheinfolge verknüpfte Nummer.
Der empfönger sortiert nach dieser 

1. Physikal layer 
2. data Link layer
3. network layer
4. transport layer 
5. session layer
6. presentation layer 
7. application layer 
