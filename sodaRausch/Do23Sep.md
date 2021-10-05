# Datenhaltung am KBM
````mermaid
flowchart TD

B[Schülerdaten];

Sekreteriat-->B
Admin-->B
Bildungsgangleiter-->B
Bibliothek-->B
````

## nachteile dieser art
+ Hoher Arbeitsaufwand 
    + Redundanzen, Arbeitsspeicherung der gleichen Informationen
    + Anomalien, Wiedersprüchlichkeiten zwischen den Datenbestanden
    + verminderter Datenschutz & Datensicherheit
## Datenbanksystem (DBS)

Ist ein System zur elektronischen Datenverwaltung.
wesentliche aufgabe ist es große datenmengen effizient konsistent und dauerhaft zu speichern und bereitzustellen.

besteht aus zwei teilen 
+ Verwaltungssoftware (Datenbankmanagementsystem )
+ Datenmenge

## Aufbau eines Datenbanksystems
````mermaid
flowchart TD

A(sec)
B(admin)
C(Bl)
D[Datenbankmanagementsystem]
E(SChueler)
F(leitung)
G(Lehrer)

D-->E
D-->F
D-->G
````

`Datenbank:`
Eine Strukturierte Sammlung von Informationen zu einem Bestimmtem Thema.
`Datenbankmanagmentsystem:`
Verwaltet die daten in mindestens einer Datenbank.
`Datenbanksystem:`
besteht aus einem DBMS und einer DB.


## Datenbankmanagementsystem

Eigentschaften

+ Speichern der Daten
+ Datensicherheit: Speichern von informationen und zugriffsreche von benutzern. Schutz gegen datenverlust und unerlaubtem zugriff
+ Mehrbenutzerbetrieb durch transaktionen: absichern von daten gegen mehrfachveränderung
+ Sicherstellen der Datenintegrität: durch regeln die beschreiben wie daten verändert werden dürfen bsp. daten können nicht gelöscht werden wenn sie noch von einer anderen Tabelle benötigt werden.
+ Anfrageoptimierung: das DBMS stellt eine datenbanksprache zur Verfügung welche die anfragen verarbeitet diese sprache sollte möglichst effizient sein

Aufgabe 1:  
````
 Datenbank:
 Eine Datenbank ist ein zum speichern von daten zur verfügung gestellter speicher.

 Datenbanksystem:
 Ein Datenbanksystem ist ein system zur elektronischen datenverwaltung und besteht aus dem dem Datenbankmanagementsystem und der menge der Zu verwaltenen Daten der Datenbank.

 Datenbankverwaltungssystem:
 ist das system zur verwaltung der Daten in der Datenbank. Es stellt die datenbanksprache zur verfügung welche die anfragen auf die datenbank steuert. und sollte oben aufgelistete eigenschaften besitzen.
````
 ## Vor und nachteile des Datenbankeinsatzes