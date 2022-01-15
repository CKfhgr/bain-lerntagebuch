---
title: Abschluss
date: 2022-01-14
---

Zum Abschluss des Unterrichts, möchte ich in diesen Blogpost nutzen um hier kurz in meinen eigenen Worten zu erklären um was es dem Schaubild geht, welches uns während des gesamtes Semester begleitet hat.

![2021-12-30 14_27_32-2021-12-30 14_24_02-6  Suchmaschinen und Discovery-Systeme - Bibliotheks- und Ar](https://user-images.githubusercontent.com/85638168/147758639-730a09e4-4f96-40e4-9d7b-1fba1e459268.png)


Im Blauen Rahmen werden die Systeme aufgelistet, welche wir im Rahmen des Kurses installiert und konfiguiert haben. Koha (Bibliothekssystem) und Archivesspaces (Archivsystem) haben wir auf der Virtuellen Maschine installiert und eigene Daten in diesen System erstellt. Für DSpace nutzten wir die zur Verfügung gestellte Demo Umgebung, erstellten dort aber auch eigenständig Inhalte. Alle Daten, welchen aus diesen drei Systemen generiert wurden wurden anschliessend über die OAI-PMH-Schnittstelle (Pinker Rahmen) zur Verfügung gestellt, damit diese auch zur Weiterverarbeitung verwendet werden konnten.

Da kam das Tool VuFindHarvest ins Spiel (Grüner Rahmen), ein Tool um Daten zu harvesten also abzurufen für die Weiterverarbeitung. So wurden alle Daten mittels dieses Tools in den entsprechenden Formaten abgespeichert: Für Koha *marcxml*, für Archivesspaces *ead* und DSpace *Dublin Core*. Für letzteres nutze ich die zur Verfügung gestellten Beispieldaten.

Mittels des Tools MarcEdit wurden die verschiedenen Format aus den Systemen alle einheitlich in MARC21-XML umgewandelt, damit diese auch für die Suche am Ende genutzt werden konnten.

Parallel zu den Systemen wurden noch Daten aus einem .csv-Datensatz mittels Openrefine geöffnet und bereinigt und diese dann anschliessend auch in MARC21-XML exportiert (Gelber Rahmen)

Am Ende standen dann vier Datensätze aus 4 verschiedenen Systemen zur Verfügung. Deren Inhalte wurden dann mittels des Discovery Systems und des Suchindexes Solr (Roter Rahmen) abrufbar gemacht und konnten somit in einem Suchsystem dursucht werden!
