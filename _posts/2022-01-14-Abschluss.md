---
title: Was habe ich (nicht) gelernt?
date: 2022-01-15
---

Abschliessend möchte ich diesen Blogpost nutzen, um kurz in meinen eigenen Worten zu erklären um was es dem Schaubild geht, welches uns während des gesamtes Semester begleitet hat. Dies, um zu wiederholen was wir angeschaut haben, und um meine Eindrücke und (nicht) Erlerntes direkt zu den einzelnen Themen festzuhalten. Das Schaubild habe ich zu diesen Zwecken mit farblichen Rahmen markiert, um besser darauf zu referenzieren.

![2021-12-30 14_27_32-2021-12-30 14_24_02-6  Suchmaschinen und Discovery-Systeme - Bibliotheks- und Ar](https://user-images.githubusercontent.com/85638168/147758639-730a09e4-4f96-40e4-9d7b-1fba1e459268.png)

In Blau werden die Systeme aufgelistet, welche wir installiert und konfiguriert haben. Koha (Bibliothekssystem) und Archivesspaces (Archivsystem) haben wir auf den virtuellen Maschinen installiert und eigene Daten in diesen Systemen erstellt. Für DSpace nutzten wir die Demo Umgebung, erstellten dort aber eigenständig Inhalte. Alle Daten aus diesen drei Systemen wurden anschliessend über die OAI-PMH-Schnittstelle (Pink) zur Verfügung gestellt, damit diese auch zur Weiterverarbeitung verwendet werden konnten.

**Feedback zu dieser Thematik**: *Ich konnte hier einiges zur Anwendung solcher Systeme lernen. Ich denke aber nicht, dass ich zukünftig viel in der Arbeitswelt davon mitnehmen kann, da ich nicht mehr in diesem Bereich arbeite. Mitnehmen kann ich trotzdem die Erkenntnis, wie solche Systeme im Hintergrund aufgebaut sind und wie man diese bedienen kann. Ausserdem nehme ich viel zusätzliches Wissen im Bereich Linux und Anwendung der Commandline mit - diese Thematik wird bei mir sicher immer ein Thema bleiben und mich auf meinen weiteren Arbeitsweg begleiten. Ich hätte mir vielleicht mehr gewünscht noch mehr Befehle zu erlernen und auch zu verstehen, kann aber gut nachvollziehen, dass dies nicht auch noch in diesem Kurs eingebaut werden kann.*

Danach kam das Tool VuFindHarvest ins Spiel (Grün), ein Tool, um Daten zu harvesten bzw. abzurufen für die Weiterverarbeitung. So wurden alle Daten mittels dieses Tools in den entsprechenden Formaten abgespeichert: Für Koha *marcxml*, für Archivesspaces *ead* und DSpace *Dublin Core*. Mittels des Tools MarcEdit wurden die verschiedenen Format aus den Systemen alle einheitlich in MARC21-XML umgewandelt, damit diese auch für die Suche am Ende genutzt werden konnten.

**Feedback zu dieser Thematik**: *Bevor ich diesen Kurs besucht habe, hatte ich noch nie etwas zum Begriff "Harvesting" gehört - jedenfalls nicht zu dieser Thematik. Hier nehme ich jedenfalls die Erkenntnis mit, dass es so ein Tool überhaupt gibt!*

Parallel zu den Systemen wurden noch Daten aus einem .csv-Datensatz mittels OpenRefine geöffnet und bereinigt und diese dann anschliessend in MARC21-XML exportiert (Gelb).

**Feedback zu dieser Thematik**: *Für diese Thematik war ich sehr dankbar, denn es ist unglaublich wichtig Daten zu bereinigen. Dies ist ein Thema, welches mich bei meiner Arbeit begleitet und welches auch essentiell zur Weiterverarbeitung der Daten ist. Bisher nutzte ich nur Excel und Pandas (Python) um Datensätze zu bereinigen. Nun kenne ich ein weiteres Tool, welches ich gerne noch näher anschauen möchte und es eventuell auch dann meiner Firma vorstellen möchte.*

Am Ende standen dann 4 Datensätze aus 4 verschiedenen Systemen zur Verfügung. Deren Inhalte wurden dann mittels des Discovery Systems und des Suchindexes Solr (Rot) abrufbar gemacht und konnten somit in einem Suchsystem durchsucht werden!

**Feedback zu dieser Thematik**: *Auch hier kann ich sagen, habe ich sehr vieles mitnehmen können. Ich hatte nie richtig verstanden was ein Discovery System ist und was es dazu braucht, um eines aufzubauen. Gelernt habe ich, dass es dazu gar nicht so viel braucht! Da kann ich mich nur bedanken. Hier konnte ich viel lernen und werde diese Thematik definitiv im Hinterkopf behalten.*

Die letzte Thematik, Linked Data, wird in diesem Schaubild nicht aufgezeigt. Das Thema wurde leider sehr kurzgehalten und ich konnte hier nicht so viel mitnehmen wie in den letzten Unterrichtseinheiten. 

Persönlich interessiert hatte mich am meisten das Thema "Discovery Systeme" und natürlich auch das Tool "OpenRefine". Beide Themen haben mich sehr überzeugt und werden mich in Zukunft begleiten.


