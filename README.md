# 2015-06-01 - Menü umbenannt, umgeordnet und die Sidebar (für Extensions) deaktiviert
**Änderung in Bootstrapskin.skin.php**
* Menü Umbenennung in Zeile 201
* Link zu "Help create wikiEvolved!" umbenannt in "Help center", Link auf die Startseite des Help Centers umgemappt und in der Anordnung an letzte Position gesetzt.
* Sidebar in Zeile 327 auskommentiert um die Ausgabe von Linkeinträgen der Extensions zu unterdrücken.


# Nav Pills Entfernt
bootstrapskin.skin.php
-> navigation nav nav-pills pull-right searchform-disabled entfernt

# Titelzeile
bootstrapskin.skin.php
-> row als erstes bei output html page
XX der Untertitel ist noch blau, CSS ändern

# Render Logo
bootstrapskin.skin.php
-> private function renderlogo angepasst
-> logo heißt immer noch wiki.png, ggf. in localsettings ändern
XX das Logo hat noch keinen Link zur Hauptseite

# <!-- Header --> 
bootstrapskin.skin.php
-> renderlogo rausgenommen
XX da steht noch irgendwas mit grouppermissions - noch gebraucht?