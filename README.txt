ENGLER'S EVENTS – GitHub-Start für Android

1. Die aktuelle Apps-Script-Web-App-Adresse ist bereits in config.js eingetragen.
   Falls sich die Veröffentlichung später ändert, dort die /exec-URL ersetzen.
   Nie das Admin-Passwort oder einen geheimen Schlüssel hier ablegen.

2. Auf GitHub ein neues öffentliches Repository "englers-events" erstellen.
   Den Inhalt dieses ZIP-Archivs entpacken und alle sieben Dateien einzeln
   direkt in die oberste Ebene des Repositories hochladen (nicht die ZIP-Datei).

3. Im Repository: Settings > Pages > Build and deployment > Deploy from a branch.
   Branch: main; Ordner: /(root); Save.

4. Die bei Pages angezeigte Adresse auf dem Android-Handy in Chrome öffnen.
   Über das Drei-Punkte-Menü "App installieren" oder "Zum Startbildschirm
   hinzufügen" wählen. Das Logo erscheint auf dem Homescreen.

Die Startseite leitet nach kurzer Anzeige des Logos zur bestehenden
Google-Apps-Script-Web-App weiter. Buchungen und Administration bleiben dort.
Ohne gültige /exec-Adresse erscheint auf der Startseite ein Hinweis.

Bei späteren Änderungen den Start über die GitHub-Pages-Adresse prüfen.
Der Service Worker fragt Dateien zuerst vom Netz ab und nutzt den Cache nur
bei fehlender Verbindung, damit eine alte Startadresse nicht hängen bleibt.

Hinweis: Der Wechsel zur Google-Adresse liegt ausserhalb des Geltungsbereichs
der installierten GitHub-Seite. Je nach Android-/Chrome-Version kann danach
die Browser-Oberfläche angezeigt werden.
