---
title: Übung - Suche und Facetten
date: 2021-12-5
---

Für diese Übung war die Vorraussetzung die VuFind Installation erfolgreich abgeschlossen zu haben.
Ich war froh, dass die Installation von VuFind schnell und einfach war, so konnte ich gleich mit der Übung starten. Zu Beginn änderte ich noch die Dateiberechtigungen mittels Befehls: "*sudo chown -R $USER:$GROUP /usr/local/vufind/local/config*"

Ich folgte und führte in meinem VuFind fast alle Schritte aus, welche im Video, welches wir für die Übung anschauen mussten, aufgezeigt wurden. Ein paar Einstellungen setzte ich dann wieder zurück aber getestet hatte ich alle, um nachvollziehen zu können was sich ändert. 

**Suche konfigurieren** (search.ini) 

Zuerst erstellte ich  eine Kopie der searches.ini File um den jetzigen Stand vor meinen Änderungen zu sichern.
Hier blendete ich die Funktion ein, per Drop-Down selbst entscheiden zu dürfen wieviel Suchergebnisse auf einer Seite angezeigt werden sollten. Ich selbst nutze diesen Filter immer, weshalb er hier auch nicht fehlen durfte. Ausserdem sortierte ich die Suchergebnisse nach Alphabetischer Reihenfolge und erweiterte die Suchfelder (oben neben dem Suchschlitz) um ein Feld mehr "Journal Title".

Vorher: ![vufind](https://user-images.githubusercontent.com/85638168/147700228-65071598-9792-4e5b-837f-e0dadf5fe342.png)

Nachher: ![vufind2](https://user-images.githubusercontent.com/85638168/147700268-b1e8bf10-f123-427a-8637-50c7dee2deae.png)

**Facetten konfigurieren** (facets.ini)

Bei den Facetten änderte ich nur wenig. Hier kann man schnell den User überfordern wenn auf der rechten Seite alle Facetten aufgeklappt werden und jegliche Filter aktiv sind. Ich habe deshalb  bewusst eingestellt dass nur maximal 3 Facetten pro Kategorie aufgeklappt angezeigt werden. Ausserdem habe ich die Ausschliessen-Funktion aktiviert, damit der User die Möglichkeit hat Facette auszuschliessen. Für Language und Format habe ich zudem die Mehrfachauswahl aktiviert. Dies aber mehr zu Testzwecken.
![vufind3](https://user-images.githubusercontent.com/85638168/147699942-c982e97f-d455-41a2-889d-853bb1a7ed18.png)
