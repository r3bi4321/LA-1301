# Projekt-Dokumentation


Rebecca Willi, Salma Tanner

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|15.09.2023| 0.0.1   | Ausdenken des Projekts Kapitel 1.1 & 1.2 ausgefüllt und Mockup begonnen.  |
|22.09.2023| 0.0.2   |Kapitel 1.3 -3 bearbeitet, Realisierung begonnen|
| 29.09.2023| 0.0.3   |  Fortsetzten mit realisieren, besprechen der Fortschritte| 
|27.10.2023| 0.0.4   |Realisieren fortsetzten, Projekktdokumentation aktualisieren|
|03.11.2023| 0.0.5   |Realieren abschliessen, Projektdokumentation abschliessen, anfangen mit Portfolioeintrag|
|10.11.2023| 0.0.6   |Abschliessen mit Portfolioeintrag|

## 1 Informieren

### 1.1 Ihr Projekt

Wir programmieren eine To-Do Liste.

Unser Ziel ist es eine To-Do Liste zu programmieren. Sie soll auf einer Webseite mit einem Login angerufen werden können. Man soll Aufgaben erstellen können, diese werden dann in OFrm einer Liste angezeigt.
Evtl. soll auch ein Kalender ersichtlich sein welcher die Deadline aller Aufgaben bei dem Datum anzeigt.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    | Muss            | Funktional| Als User möchte ich, dass ich mich mit einem Login anmelden kann, um auf meine gespeicherten Dienste zugreifen zu können. |
| 2    | Muss            | Funktional| Als User möchte ich, dass ich meine To-Do Liste einsehen kann, um meine Aufgaben erledigen zu können.|
| 3    | Muss            | Funktional| Als User möchte ich neue Aufgaben erfassen, um mir die Aufgaben merken zu können.| 
| 4    | Muss            | Funktional| Als User möchte ich den neuen Aufgaben einen Namen, eine Deadline, ein Prioritätslevel und  Notitzen hinzufügen können. | 
| 5    | Muss            | Funktional| Als USer möchte ich, dass ich Aufgaben bearbeiten kann, um Änderungen der Aufgaben festzuhalten.|
| 6    | Muss            | Funktional| Als User möchte ich, dass ich erledigte Aufgaben abhäckeln kann.| 
| 7    | Kann            | Qualität  | Als User möchte ich, dass die Aufgaben für die Arbeit eine andere Farbe haben als die Arbeit für das Privatleben, um dieses Durcheinander zu vermeiden.|
| 8    | Kann            | Qualität  | Als User möchte ich, dass ich beim erstellen einer neuen Aufgabe angeben kann, ob es eine Aufgabe für die Arbeit oder das Privatleben ist.| 
| 9    | Muss            | Qualität  | Als User möchte ich, dass die Aufgaben nach Priorität sortiert werden, um diese schneller einzusehen.| 
| 10   | Muss            | Funktional| Als User möchte ich, dass die Aufgaben in einer Liste dargestellt werden.|
| 11   | Kann            | Qualität  | Als User möchte ich, dass die Aufgaben in einem Kalender angezeigt werden, um zu wissen, bis wann die Aufgaben erledigt sein müssen.| 
| 12   | Kann            | Qualität  | Als User möchte ich, auf meine Logindaten zugreifen können, um evtl. Änderungen vorzunehmen.|
| 13   | Kann            | Qualität  | Als User möchte ich, eine Dauer der Aufgabe zuordnen können.|
| 14   | Kann            | Qualität  | Als User möchte ich eingeben können, wenn sich die Aufgabe immer wieder widerholt.|
| 15   | Muss            | Funktional| Als User möchte ich ein neues Login erstellen können.| 
| 16   | Muss            | Funktional| Als User möchte ich mich registrieren können.| 
| 17   | Muss            | Funktional| Als User möchte ich mich auf der Startseite in die Funktion/den Aufbau von den To-Do Listen einlesen können. | 



### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Startseite ist geöffnet, Anmeldefeld für Login angewählt | Login eingeben  | Anmeldung war erfolgreich |
| 2.1  | Login ist korrekt eingegeben| *Enter*| To-Do Liste erscheint|
| 3.1  | Eingeloggt auf der To-Do Liste| *Aufs + Klicken*| Fenster um eine Aufgabe zu erstellen öffnet sich|
| 4.1  | Fenster um eine Aufgabe zu erstellen ist geöffnet| *Alle Felder ausfüllen*| Aufgabe wird mit diesen Daten gespeichert|
| 5.1  | Aufgabe auswählen| Priorität von sehr wichtig zu wichtig ändern| Update wird gespeichert|
| 5.2  | Aufgabe auswählen| Notitzen hinzufügen| Update wird gespeichert|
| 6.1  | To-Do lIste geöffnet| Häckchen bei der Aufgabe setzten| Aufgabe wird gestrichen|
| 7.1  | Einloggen| *Enter* | Blaue und grüne Balken sind am RAnd der Aufgaben.| 
| 8.1  | Aufgabe erstellen| Privat auswählen| Aufgabe hat einen blauen Balken|
| 8.2  | Aufgabe erstellen| Arbeit auswählen| Aufgabe hat einen grünen Balken|
| 9.1  | Aufgabe erstellen| Priorität tief | Aufgabe wird zu unterst eingeordnet|
| 9.2  | Aufgabe erstellen| Priorität hoch | Aufgabe wird zu oberste eingeordnet|
| 10.1 | Login eingeben |*Enter* | Aufgaben erscheinen in einer Liste|
| 11.1 | To-Do Liste ist geöffnet| *Wechsel auf Kalenderansicht*| Aufgaben werden im Kalender angezeigt.|
| 12.1 | Eingeloggt| *Mein Konto auswählen*| Persönliche Daten erscheinen.| 
| 13.1 | Aufgabe erstellen| Dauer: 45 min | Daten werden gespeichert|
| 14.1 | Aufgabe erstellen| Wiederholung der Aufgabe: Alle 7 Tage| Daten werden gespeichert|
| 15.1 | Registrierungsseite geöffnet| Registrieren| Bestätigung für Registrierung erscheint.|
| 16.1 | Registrierungsseite geöffnet| Registrieren| Registrierung erfolgreich abgeschlossen.|
| 17.1 | Startseite geöffnet|Scrollen auf der Seite| Ausgabe Text/Anleitung für To-Do Listen|







### 1.4 Diagramme



## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  | 22.09.2023|  ST   |  Erstellen des Logins, evt. versuchen, Liste damit zu verbinden|   45min            |
| 2.A |   22.09.2023    |   ST        |  Verbinden der Listenseite, durch GUI            |  45min             |
| 3.A |  22.09.2023     |   RW        |  Eingabefeld für das Erfassen der neuen Aufgaben            |     45min          |
| 4.A  |  22.09.2023    |  RW         |    Funktionen der Aufgaben hinzufügen          |       60min            |
| 5.A  |  29.09.2023    |  RW         |     Aktualisierung der Aufgaben ermöglichen         |       45min            |
| 6.A  |29.09.2023      |   RW        |     Erledigte Aufgaben abhäckeln können         |         45min          |
| 7.A  |  27.10.2023     |    RW       |     Aufgaben mit Farben kennzeichnen können         |        45min           |
| 8.A  |  27.10.2023     |     RW      |      Aufgaben zwischen Arbeit/Privat unterscheiden       |       45min            |
| 9.A  |    27.10.2023   |    RW       |     Aufgaben nach Priorität sortieren        |       45min            |
| 10.A  |   27.10.2023    |   RW        |     Aufgaben in Liste einsehen können        |        45min           |
| 11.A |   03.11.2023    |    RW       |     Aufgaben in Kalender anzeigen        |        45min           |
| 12.A |   03.11.2023    |    ST       |      Zugriff auf Logindaten gewähren       |       45min            |
| 13.A |  03.11.2023     |    RW       |     Dauer einer Aufgabe hinzufügen können         |        45min           |
| 14.A |  03.11.2023     |     RW      |      Wiederholbarkeit der Aufgaben einstellen können       |          45min         |
| 15.A |  29.09.2023     |     ST      |      Erstellung eines neuen Logins für Benutzer      |       120min           |
| 16.A |  27.10.2023     |     ST      |      Registrierung erstellen      |          60min        |
| 17.A |    03.11.2023   |      ST     |       Startseite formatieren      |        120min           | 


Total: 930min

## 3 Entscheiden

Wir haben uns dazu entschieden, die Arbeitspakete aufzuteilen. Rebecca Willi macht den Listen bereich, wo man die Aufgaben erfässt und Salma Tanner macht die Startseite, den Loginbereich und die Registrierung.

## 4 Realisieren

| AP-№ | Datum | Zuständig | tatsächliche Zeit |
| ---- | ----- | --------- | ----------------- |
| 1.A  | 22.09.2023     |  ST          |     60min          |                   
| 2.A     | 22.09.2023     |  ST          |   65min            |                   
|  3.A    | 22.09.2023   |   RW         |     50min          |                   
|    4.A  | 22.09.2023 |   RW         |       45min        |                                     
| 6.A     |  29.09.2023      |   RW         |    45min           |                                                                          
| 10.A     |   27.10.2023      |   RW         |    125min             |                                     
| 12.A     |  03.11.2023     |   ST        |   45min            |                   
| 13.A     |  03.11.2023     |  RW          |  50min             |                   
| 14.A     |  03.11.2023     |  RW          |  65min             |                   
| 15.A     |  03.11.2023     |  ST          |     120min            |                   
| 16.A     |    27.10.2023     |  ST          |      45min         |                   
| 17.A     |   29.09.2023     |  ST          |        110min         |                   



## 5 Kontrollieren

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  | 03.11.2023      | Loginformular wurde erstellt, man kann es benutzen         |  ST      |
| 2.1     | 03.11.2023      |  Mithilfe von Button kommt man von Startseite auf Listenseite.        | ST       |
| 3.1     | 03.11.2023      | Fenster für das Erstellen einer neuen Aufgabe wird geöffnet.|  RW      |
| 4.1     |03.11.2023       | Daten zu der neuen Aufgabe können eingegeben werden.|  RW      |
| 6.1     | 03.11.2023      | Häcken neben der Aufgabe erscheint. | RW       |
| 10.1     | 03.11.2023      | Dadurch dass das BackEnd nicht funktioniert ist dies nicht möglich. |  RW      |
| 12.1     |  03.11.2023     | Zugriff auf die Logindaten hat nur der Verwalter der Formulare, der Benutzer kann sie nicht ändern.|  ST      |
|  13.1    |  03.11.2023     | Daten werden nicht gespeichert. Eingaben sind aber möglich. |  RW      |
|  14.1    |  03.11.2023     | Eingabe ist möglich. Das Speichern jedoch nicht.|   RW     |
| 15.1     |  03.11.2023     |   Formular für Login kann man ausfüllen, es funktioniert, Daten werden gesendet, jedoch funktioniert Login nicht wirklich, man kann seine Listen  nicht perönlich speichern.        | ST     |
| 16.1     |  03.11.2023     |   Formular für die Registrierung funktioniert, Daten werden versendet bzw. man erhält Bestätigung, jedoch merkt sich die Webapplikation die Registrierung nicht.       | ST       |
|  17.1    |   03.11.2023    |  Startseite funktioniert, man kann sich gut einlesen.        |  ST      |


Die Webseite an sich funktioniert und erfüllt ihren Zweck. Man kann Aufgaben erstellen und diese einsehen, das ist das wichtigste. Es gibt beim Login/Registrierung/Erstellen der Aufgabe Probleme mit dem BackEnd, d.h die Daten werden zwar gesendet, jedoch nicht verarbeitet. Deshalb kann man seine persönliche Liste nicht auf seinem Konto speichern, sonst erfüllt sie ihren Zweck.



