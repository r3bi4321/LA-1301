# Projekt-Dokumentation

☝️ Alle Text-Stellen, welche mit einem ✍️ beginnen, können Sie löschen, sobald Sie die entsprechende Stellen ausgefüllt haben.

✍️ Ihr Gruppenname und Ihre Nachnamen

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|15.09.2023| 0.0.1   | Ausdenken des Projekts Kapitel 1.1 & 1.2 ausgefüllt und Mockup begonnen.  |
|22.09.2023| 0.0.2   |Kapitel 1.3 -3 bearbeitet, Realisierung begonnen|
|       | 1.0.0   |                                                              |

## 1 Informieren

### 1.1 Ihr Projekt

Wir programmieren eine To-Do Liste.

Unser Ziel ist es eine To-Do Liste zu programmieren. Sie soll auf einer Webseite mit einem Login angerufen werden können.
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



### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Startseite ist geöffnet, Anmeldefeld für Login angewählt | Login eingeben  | Anmeldung war erfolgreich |
| 1.2  | Startseite ist geöffnet, Anmeldefeld für Login angewählt |Richtiger Loginname falsches Passwort|Falsches Passwort|
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
| 15.1 | Startseite geöffnet| Registrieren| Feld für neues Login erscheint|
| 15.2 | Feld für neues Login ist geöffnet| Neues Login erstellen| Login wurde erfolgreich erstellt|



### 1.4 Diagramme



## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  | 27.10.2023|           |              |               |
| ...  |       |           |              |               |

Total: 

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |       |           |               |                   |
| ...  |       |           |               |                   |

✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
