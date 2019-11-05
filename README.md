# ge�ndert durch Simon Hofbauer

# Example Projekt for DHBW lectures

[![Build Status](https://travis-ci.org/barclay-reg/dhbw-painground.svg?branch=master)](https://travis-ci.org/barclay-reg/dhbw-painground)

## Start development

### Checkout & Start
1. clone repo
1. run `mvnw clean install` in terminal
1. run `mvnw spring-boot:run` in terminal or launch class `net.kleinschmager.dhbw.tfe.painground.PaingroundApplication` as main class within Eclipse
1. view UI at http://localhost:8080/
1. You can look at http://localhost:8080/liquibase to review the list of db scripts.
1. View H2 console at http://localhost:8080/h2-console so that you can review the state of the database (the default jdbc url is `jdbc:h2:mem:testdb`).

### IDE Setup

1. ensure, that you have the [EditorConfig](https://editorconfig.org) Plugin in your IDE/Editor of your choice

### Know-How

For documentation on using Vaadin Flow and Spring, visit [vaadin.com/docs](https://vaadin.com/docs/v10/flow/spring/tutorial-spring-basic.html)

For more information on Vaadin Flow, visit https://vaadin.com/flow.

## Stories

### Story 1

>Ich möchte für alle (meine) Mitarbeiter ein Profil anlegen: dies soll den Namen, den Geburtstag und ein Bild beinhalten.

### Story 2

>Ich möchte, dass sich jeder Mitarbeiter mit Namen anmelden kann und nur sein eigenes Profile bearbeiten kann.

### Story 3

>Ich möchte, dass das Profile auch Felder für die private Adresse, private Telefonnummer und Hobbies enthält.

### Story 4

>Die PersonalAbteilung will die Skills jedes Mitarbeiters per REST-Schnittstelle in ihr eigenes System importieren.

### Story 5

>Ich möchte, dass ein Mitarbeiter in seinem Profi seine "Skills" pflegen kann, in ein Textfeld - ein Wort == ein skil

### Story 6

>Ich möchte, dass die Skills gewichtet werden können - Gewichtungen: Novize, Erfahrener, Experte

### Story 7

>Ich möchte, dass beim Erfassen eines weiteren Skills an einem Profile eine Liste an passenden - bereits erfassten Skills angezeigt werden soll (suggest)

### Story 8

>Ich möchte eine Liste aller erfasster Skills sehen, dazu die Anzahl der Mitarbeiter, die dieses Skill "haben"

### Story 9

>Ich möchte, dass ein Mitarbeiter den Skill (inkl. dessen Gewichtung) eines Kollegen bestätigen kann. Im Profil des Mitarbeiters kann man dann sehen, wie viele "Kollegen" den Skill & Bewertung bestätigt haben.

### Story 10


>Ich möchte, dass ein Mitarbeiter seine Bewertung eines Skills ändern kann - diese Änderung soll mit Zeitstempel gespeichert werden sodass später die "Entwicklung" dieses Skills beobachtet werden kann.

### Story 11


>Ich möchte, dass die Bewertungen der Kollegen ebenfalls mit Zeitstempel gespeichert werden - so kann man später eine "Entwicklung" der Bewertungen & Bestätigungen aufzeigen.

### Story 12

>Ich möchte eine Liste aller Projekte, bei jedem Mitarbeiter in der Profilansicht, sehen. Die Reihenfolge ist nach dem aktuellsten Projekt sortiert. Zu jedem Projekt wird der Name, Beginn und Ende angezeigt.

### Story 13

>Ich möchte ein seperates Fenster haben, in dem ich eine Auswahl an Profilen zwischen speichern kann. Dabei können die Profile per drag and drop in das Fenster verschoben werden.
