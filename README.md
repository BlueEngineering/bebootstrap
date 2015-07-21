# Mai und Juni 2015

## Nav Pills Entfernt
bootstrapskin.skin.php
-> navigation nav nav-pills pull-right searchform-disabled entfernt

## Titelzeile PHP
bootstrapskin.skin.php
-> row als erstes bei output html page
[ ] Link beim Bild setzen

## Titelzeile CSS
-> der Untertitel ist noch blau, CSS ändern
-> schriftgewicht auf 600 gesetzt, größe geändert, margin nach oben festgelegt
-> verhalten bei hover geändert
-> subtitle angepasst
[ ] BE wechselt noch die farbe

## .headertitle
theme.css
-> .headertitle passt den titel/subtitel an

## Render Logo
bootstrapskin.skin.php
-> private function renderlogo angepasst
-> logo heißt immer noch wiki.png, ggf. in localsettings ändern
[ ] das Logo hat noch keinen Link zur Hauptseite

## <!-- Header --> 
bootstrapskin.skin.php
-> renderlogo rausgenommen
[ ] da steht noch irgendwas mit grouppermissions - noch gebraucht?

## LESS / CSS
-> less kompiliert mittlerweile richtig
[ ] wofür wird die theme.css im CSS ordner kompiliert?, achtung das ist nicht die customize theme.css

## Schrift
variables.less
-> open sans als familie hinzugefügt
-> link bei google eingefügt
[ ] ich bin mir noch nicht sicher, ob die dateien richtig von google geladen werden - mit woff ist schicker, oder?

## Menubar PHP
bootstrapskin.skin.php
-> sehr unschön habe ich über copy'n'paste aus einer alten funktionierenden datei das ganze rüberkopiert
-> ich musste erst lange suchen, bis der "responsive" button wieder kommt und dabei habe ich den einfach nur nicht rüberkopiert in der PHP
[ ] ich habe einfach nicht die richtige stelle gefunden, wo ich das einfügen muss und wie

## Menubar CSS
theme.css
-> einfach alles, was mit hadron zu tun hat aus dem original rüberkopiert,
-> das padding und margin-top angepasst in navbar.less und variables.less
-> unterstrich/box-shadow bei links in navbar.less eingefügt
[ ] irgendwie hat er es hinbekommen, dass das in der bootstrap.css steht...keine ahnung wie, wenn er immer wieder neu kompiliert
[ ] das ganze ist gerade mit border style dotted - auf der originalseite wird es mit einer 1x2 png gelöst - bessere optische qualität?

## Menubox die ausgeklappt wird CSS
theme.css
->die dopplungen page, personalnav, actions, toolbox rausgenommen
-> bilder gesetzt

## Seitenbreite
scaffolding.csss
-> ist jetzt auf 1100px gesetzt

## Responsive Menu Bar
[ ] das kleine bildchen ist überhaupt nicht schön

## Menu CSS gelöscht
bootstrapskin.php
-> weil die für ein anderes menu zusständig war

## .row
theme.css
-> Neue Zeile .row mit margin-left und margin-right auf 15px
XX eigentlich kommt das aus grid.less aber ich habe keine Ahnung wie

## Margin-Left und Right
grid.less und vielleicht andere
-> 15px links und rechts festgesetzt, damit alles auf einer Linie ist
-> Anpassung erfolgt dann bei den einzelnen Elementen

## Primary Panel
-> Punkte Border

## Footer
footer.php
-> Icon und all rights reserved rausgenommen
-> eigene Sachen reingeschrieben

## Footer II
bootstrapskin.skin.php
-> jede Menge Quatsch rausgenommen, Searchbar usw.

## Theme.css oder Scree.css
Was ist da eigentlich der Unterschied?

# Juli 2015

## Tims Änderungen eingepflegt
Die Änderungen von Tim, die ich mal über FTPUpload gelöscht hatte - jetzt in die Github Version eingepflegt
Suche auskommentiert - weil sie noch nicht "schön" ist