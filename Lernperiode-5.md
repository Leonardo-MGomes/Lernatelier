# Lern-Periode 5

- Name: Leonardo Miranda Gomes
- Zeitraum: 14.08.2026 bis 25.09.2026

## Grob-Planung

### Noten
> Wo stehen Sie mit Ihren Noten? In welchen Modulen waren Sie besonders stark; in welchen sind die ungenügend? Welche davon sind besonders wichtig?

Meine noten in Informatik sind alle ziemlich gut, ich muss mich keine sorgen machen.

### Veränderungen
> Was möchten Sie generell im Vergleich zur letzten Lernperiode anpassen?

Ich muss die Lernperiode besser plannen und protokolieren, letzten Lernperiode habe ich das fast nie gemacht. Ich versuche ab dieser Lernperiode jede woche zu Plannen und protokolieren.

### Projekte / neue Technologien
> Was für Projekte/neue Technologien möchten Sie gerne in dieser Lernperiode lernen?

- Unit-testing (In Python)
- C/C++

### Generelle Ziele
> Was haben Sie für klare und messbare Ziele in dieser Lernperiode?

- [MoodleClient](https://github.com/Leonardo-MGomes/MoodleClient) beenden
- Mit C++ anfangen, genug um ein simples Console spiel zu machen

### Projekte
- [ ] MoodleClient
- [ ] Schulplanner
- [ ] Netacad C++
- [ ] C++ Projekt

## Tagesplanungen

### Planung 14.08.2026

- [ ] MoodleClient
  - [x] Unit testing für auth.py fertig schreiben
  - [ ] Unit testing für session.py anfangen
  - [x] Recherche über neue automatische Loginmöglichkeiten nach SSO implementierung

Heute konnte ich die Unit-Tests für Auth.py fertigstellen. Es ist das erste Mal, dass ich überhaupt Tests schreibe. Das heisst, dass ich keine Ahnung habe, was ein guter oder schlechter Test ist. Wahrscheinlich sind sie eher schlecht geschrieben.
Bei meiner Recherche habe ich herausgefunden, wie die Mobile App ein Token unter SSO Login holt. Das einzige Problem ist, dass SSO Login nur unter einem Webbrowser möglich ist und ich keinen vollständigen automatischen Login-Prozess erstellen kann. Eine Möglichkeit wäre, den SysAdmin zu fragen, ob ich ein WebToken erstellen könnte. Dafür bräuchte ich entweder die Berechtigung "moodle/webservice:createmobiletoken" oder "moodle/webservice:createtoken", wobei die erste Option sicherer ist, aber mehr Restriktionen hat. (Die erste Option ist die, die bereits aktiviert ist.)


### Planung 21.08.2026

- [ ] MoodleClient
  - [ ] core_course_get_categories implementieren
  - [ ] core_course_get_contents implementieren
- [ ] C++ Essentials in Netacad
  - [x] C++ environment installieren und einstellen (Clion + Clang)
  - [x] Modul 1 durcharbeiten + test bestehen
  - [ ] Modul 2 anfangen

Heute habe ich nicht an MoodleClient gearbeitet, sondern habe damit begonnen, den Kurs "C++ Essentials 1" bei Cisco Netacad zu absolvieren.
Ich habe bereits Erfahrungen mit C++ und in diesem Modul wurden ohnehin nur die Grundlagen wie Variablen, cout, cin usw. behandelt. Kurz gesagt fand ich es ziemlich einfach.


### Planung 28.08.2026

- [ ] MoodleClient
  - [ ] core_course_get_categories implementieren
  - [ ] core_course_get_contents implementieren
- [ ] C++ Essentials in Netacad
  - [ ] Modul 3 beenden (3.4 - 3.9) + test bestehen

Heute habe ich leider nichts vollständig abgeschlossen. Es sind viele ungeplante Probleme aufgetreten, die mich beeinträchtigt haben.
Ich habe an C++ Essentials weitergearbeitet, genauer gesagt an Modul 3, ich fand es ein bisschen schwieriger (als letzte woche).
Pointer und Referenzen sind mir noch ein bisschen fremd. Ich verstehe es langsam immer besser, aber ich brauche mehr Übung, um damit die richtig zu nutzen.


### Planung 04.09.2026

- [ ] C++ Essentials in Netacad
  - [x] Modul 3 beenden (3.8 - 3.9) + test bestehen
  - [x] Modul 4 anfangen (4.1 - 4.2)
- [ ] Ersten C++ Projekt anfangen
  - [x] Scope wählen
  - [x] Anforderungen notieren / dokumentieren
  - [ ] Environment erstellen und kleiner beispiel kompilieren lassen

Ich habe heute fast alles geschafft, was ich geplant hatte. Ich hatte wenige Probleme bei Netacad und bei der Planung meinen C++ Projekt.
Allerdings habe ich das Gefühl, dass ich mir zu viel vorgenommen habe. Ich habe noch andere Projekte offen (z. B. MoodleClient, Schulplaner usw.), die ich gerne fertigstellen würde.
Das heisst also, dass ich einige Dinge für später aufheben und an den Dingen arbeiten soll, die ich entweder brauche oder schon kann. Ich werde also oben unter Grobplanung eine Liste führen, die meine Projekte in der gewünschten Bearbeitungsreihenfolge repräsentiert.


### Planung 11.09.2026

- [ ] MoodleClient refactoring (auth.py)
  - [x] UML-Design erstellen um das Refactoring besser zu planen
  - [-] Classen abstrahieren
  - [-] Typnamen & Classnamen bereinigen
  - [x] Authentizierungslogik in httpx integrieren
  - [x] Modulschnittstellen aktualisieren (anderen variablen- und classnamen z.B.)
  - [ ] session.py decouplen (eigener/granulärer arbeitspaket?)
  - [ ] Integrationsstest aktualisieren
  - [ ] Integrationsstest durchführen

Heute war ich extrem produktiv und habe viel mehr erledigt als sonst.
Wie letzte Woche beschrieben, habe ich meine Projekte aufgelistet und sie nach Priorität geordnet, d. h., ich habe entschieden, welche Projekte ich persönlich bearbeiten will. Das heisst nicht, dass ich das eine oder andere Projekt bevorzuge oder dass ich es bearbeite bis es 100 % fertig ist. Ich werde sowieso einen Mix haben, nur nicht alle gleichzeitig.
Die Sortierung und Filterung erfolgte vor allem nach meiner persönlichen Lust, ansonsten nach den Projekten, die ich am wichtigsten finde oder bei denen ich schon weit bin.
Das UML-Design hat mich beim Refactoring viel Zeit gekostet, aber ich konnte einen viel besseren Überblick gewinnen. Ohne diese UML als Hilfe hätte ich sicher viele Fehler gemacht. Ein zusätzlicher Vorteil ist, dass ich während der Arbeit mit UML an verschiedenen Stellen gesehen habe, dass es Abstraktion oder Delegation benötigen könnten, danke UML!


### Planung 18.09.2026

- [ ] MoodleClient refactoring (auth.py)
 - [ ] Classen abstrahieren
 - [ ] Typnamen & Classnamen bereinigen
 - [ ] session.py decouplen
 - [ ] Integrationsstest aktualisieren
 - [ ] Integrationsstest durchführen

(Heute habe ich... (50-100 Wörter))


### Planung 25.09.2026

- [ ] Erstes Arbeitspaket
- [ ] ...
- [X] Viertes AP

(Heute habe ich... (50-100 Wörter))

## Lernperiode Reflexion
(In dieser Lernperiode habe ich... (100-150 Wörter))
