# Lern-Periode 6
<!--
**ANLEITUNG**

Dies ist die Vorlage für die Dokumentation einer Lernperiode. Hinweise an Sie
als Lernende:n stehen in solchen HTML-Kommentaren. Sie sind nur in der
Quellcode-Ansicht sichtbar.
Diese Blöcke können Sie entfernen oder zur Orientierung stehen lassen.

1.  Passen Sie die Nummer der Lernperiode an.
2.  Passen Sie den Namen an.
3.  Passen Sie den Zeitraum an. Achten Sie auf das Datumsformat tt.mm.jjjj
4.  Füllen Sie die Grobplanung aus in den Abschnitten Noten, Veränderungen,
    Projekte und Generelle Ziele. Behalten Sie alle Abschnitte bei.
5.  Erstellen Sie Platzhalter für die Tagesplanungen der Lernperiode.
6.  Planen Sie den ersten Arbeitstag.
7.  Löschen Sie allfällige Anweisungs-Blöcke, die Sie nicht mehr haben wollen.
8.  Speichern Sie die Datei und publizieren Sie sie (`git push`).
-->

- Name: Leonardo Miranda Gomes
- Zeitraum: 23.10.2026 bis 18.12.2026

## Grob-Planung

### Noten
<!--
Wo stehen Sie mit Ihren Noten? In welchen Modulen waren Sie besonders stark;
in welchen sind die ungenügend? Welche davon sind besonders wichtig?
-->

...Ihr Text...

### Veränderungen
<!--
Was möchten Sie generell im Vergleich zur letzten Lernperiode anpassen?
-->

- Ich möchte an einem Projekt dranbleiben, bis ich es fertiggestellt habe, also mindestens bis eine V1.0 entstanden ist.


### Projekte / neue Technologien
<!--
Was für Projekte/neue Technologien möchten Sie gerne in dieser Lernperiode lernen?
Verlinken Sie zu den GitHub Repos Ihrer Projekte.
(Können Sie später nach und nach einfügen.)
-->

[MoodleClient](https://github.com/Leonardo-MGomes/MoodleClient)

### Generelle Ziele
<!--
Was haben Sie für klare und messbare Ziele in dieser Lernperiode?
-->

Ich will mein MoodleClient innerhalb dieser Lernperiode auf ein benutzbaren zustand bringen, dass heisst: Meistbenutzten Endpoints implementiert und auth und session decouplen. Ein Testing framework und CI/CD mache ich nachdem den Projekt stabil genug ist für ein V1.

## Tagesplanungen
<!--
Planen Sie die Lernperiode. Dazu planen Sie Arbeitspakete (jeweils für den
kommenden Arbeitstag) und erstellen am Ende jedes Tages eine kurze Reflexion.

Wenn Sie an einem Tag gefehlt haben, schreiben Sie direkt unter die
Tagesüberschrift eines dieser Schlüsselwörter allein auf eine Zeile:
absence, absent, Absenz, abwesend, krank, Krankheit.
-->

### Planung 23.10.2026
<!--
Planen Sie 3 bis 5 **klar messbare** Arbeitspakete.
Umfang: ca. 30 - 60 Minuten je Arbeitspaket
Markieren Sie beendete Arbeitspakete mit einem x.

Beispiele:
- [ ] noch nicht erledigte Aufgabe
- [x] erledigte Aufgabe
-->

- [ ] MoodleClient
    - [x] authentication beenden
    - [x] user-agent dynamisch erstellen
    - [x] moodle_endpoint decorator erstellen um code-duplication zu vermeiden


#### Tagesreflexion
<!--
Mögliche Themen: Was lief erstaunlich gut/schlecht? Wo ging der Plan nicht auf
und wieso? Was konnten Sie daraus für Ihr Vorgehen lernen?
Nicht wiederholen, was die Checkboxen schon aussagen.
Umfang: 50 - 100 Wörter (ungefähr 3 - 6 Sätze)
-->

Ich konnte heute alles machen was geplant war, auch wenn es zeitlich ein bisschen knapp war. Der moodle_endpoint decorator ist ein decorator der ein log machen soll (welche func, daten und evt. errors?) und den request auf den richtigen endpoint schickt. Dies macht es durch die Methodensignatur, die den namen der Endpoint schon hat. Ich fand das eine gute möglichkeit über Decorators zu lernen.


<!--
Fügen Sie hier die weiteren Tage der Lernperiode ein.
-->

### Planung 30.10.2026

- [ ] MoodleClient
    - [x] debug problem über decorator
    - [x] moodle_endpoint decorator zu alle Services einfügen 
    - [x] experimental branch testen
    - [x] experimental branch mergen
    - [ ] 1 CourseService endpoint implementieren

#### Tagesreflexion

Ich habe heute sehr viel Zeit mit Debugging verbracht. Ich konnte den Fehler irgendwie lange nicht finden, was meine Zeitplanung durcheinandergebracht hat.
Beim Testen des Experimental-Branches fand ich keine Probleme bei den grossen Features, was ich ein bisschen überraschend fand.
Ich hatte am ende keine Zeit mehr, um einen Endpoint zu implementieren, dazu kann ich leider nichts berichten.


### Planung 06.11.2026

- [ ] MoodleClient
    - tba

#### Tagesreflexion

tba


### Planung 20.11.2026

- [ ] Planner
    - [x] KI guidelines erstellen
    - [x] Projektidee, MVP-Umfang und Techstack gewählt/festgelegt
    - [x] Umgebung einrichten
    - [x] Git repo initialisieren
    - [x] Monorepo mit workspaces aufgesetzt
    - [x] Dependencies installiert
    - [x] TypeScript konfiguriert
    - [x] Ersten einfachen Express server geschrieben

#### Tagesreflexion

Ich habe ein neues Projekt angefangen: einen Planner für mich. Das MVP umfasst Folgendes: Tasks mit Titel, Kategorie, erledigt-Checkbox und Fälligkeitsdatum erstellen, sehen, bearbeiten und löschen. Ich werde es als RESTful API schreiben, damit ich später nicht nur Web-Clients, sondern auch native Clients in C# oder anderen Sprachen schreiben kann.
Da es mein erstes Projekt mit NodeJS ist, musste ich noch einiges über die Umgebung lernen, zum Beispiel, wie TSConfig geschrieben wird.

Für dieses Projekt habe ich mich entschieden, KI als Hilfe zu nutzen. Ich habe Richtlinien erstellt, denen die KI folgen soll. Kurz zusammengefasst:

- Die KI ist ein Mentor und kein Code-Generator: Den Code schreibe ich selbst.
- Sie gibt keine fertigen Lösungen, ausser ich verlange ausdrücklich danach.
– Wenn ich feststecke, hilft sie mir mit schrittweisen Hinweisen. Fragen, Konzepte, Doku-Links und Vergleiche mit Sprachen, die ich schon kenne (Python, C#).
– Syntax, Befehle und Konzepte darf sie direkt erklären.
– Sie achtet von Anfang an auf professionelle Standards und weist mich sofort auf bessere Lösungswege hin.
– Sie fragt mich regelmässig zu gelernten Themen ab und stellt Übungsaufgaben.
– Sie dokumentiert meinen Lernfortschritt, sodass sie in jeder Sitzung weiss, wo wir stehen.

So stelle ich sicher, dass ich diesen Techstack wirklich lerne und das Projekt selbst entwickle.

(Diese Plannung und Tagesreflexion wurde am 27.11.2026 nachgeführt)


### Planung 27.11.2026

- [ ] Planner
    - [] 

#### Tagesreflexion

tba


## Lernperiode Reflexion
<!--
Am Ende der Lernperiode schreiben Sie eine Reflexion über die gesamte Lernperiode.
Mögliche Themen: Wie gut passt Ihr Endresultat zu dem, was Sie sich vorgenommen
hatten? Unterm Strich, was ist Ihr grösstes Lernresultat? Was nehmen Sie für die
Zukunft mit aus dieser Lernperiode?
Umfang: 100 - 200 Wörter (ungefähr 6 - 12 Sätze)
-->

...Ihr Text...
