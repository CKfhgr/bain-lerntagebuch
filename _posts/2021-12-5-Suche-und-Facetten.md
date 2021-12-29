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

Vorher: ![vufind](https://user-images.githubusercontent.com/85638168/147689397-aaa62d39-86a9-4199-8969-9841f7051831.png)

Nachher: ![vufind2](https://user-images.githubusercontent.com/85638168/147698384-4a24186f-9298-4738-a1ec-3d47b9247aa1.png)


**Facetten konfigurieren** (facets.ini)

Bei den Facetten änderte ich nur wenig. Hier kann man schnell den User überfordern wenn auf der rechten Seite alle Facetten aufgeklappt werden und jegliche Filter aktiv sind. Ich habe deshalb  bewusst eingestellt dass nur maximal 3 Facetten pro Kategorie aufgeklappt angezeigt werden. Ausserdem habe ich die Ausschliessen-Funktion aktiviert, damit der User die Möglichkeit hat Facette auszuschliessen. Für Language und Format habe ich zudem die Mehrfachauswahl aktiviert. Dies aber mehr zu Testzwecken.
![vufind3](https://user-images.githubusercontent.com/85638168/147699942-c982e97f-d455-41a2-889d-853bb1a7ed18.png)
