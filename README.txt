BACKEN OHNE STRESS – iPad Web-App 3.0
===================================
KEINE zusätzlichen Cloud-Abos notwendig. Die Website besteht aus statischen Dateien.

SO STARTET DIE APP AUF DEM IPAD:
1. Diese fünf Dateien (index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png) zusammen in einem statischen kostenlosen HTTPS-Webhosting veröffentlichen, z.B. GitHub Pages (öffentliches Repository im Free-Tarif). .nojekyll mit hochladen.
2. Safari auf dem iPad → veröffentlichte https://… Adresse öffnen.
3. Teilen-Symbol → Zum Home-Bildschirm → Hinzufügen.
4. Das Studio startet ab dann über das App-Symbol.

WICHTIGE GRENZEN:
* Das Studio funktioniert ohne Windows-PC für Rezeptplanung, Storyboard, Mediathek und Projekt-Backups.
* Das MP4-Recording hängt von Safari und iPadOS ab. Nicht auf jedem iPad möglich; keine Garantie.
* OpenRouter-Aufträge verbrauchen Guthaben, aber nur nach ausdrücklicher Freigabe. Auf iPad kann Browser-CORS direkte API-Aufrufe blockieren. Das wurde nicht mit einem echten Schlüssel getestet.
* Keine API-Schlüssel ins Repo oder die Projektdateien schreiben. API-Feld bleibt nur für die laufende Sitzung.
* Die Dateien im GitHub Pages Repository sind öffentlich, aber Rezepte und Mediendateien werden im Browser gespeichert und nicht ins Repository hochgeladen.
* Keine automatische Synchronisation zwischen iPad und Samsung. Regelmäßig ZIP sichern und z.B. im Google Drive Ordner ablegen.

GitHub Pages (kostenfreie Variante): auf GitHub Repository anlegen (Public) > Dateien ins Root hochladen > Settings > Pages > Deploy from a branch > main, /(root) > Save. HTTPS wird automatisch eingerichtet. Bei Veröffentlichung kann es einige Minuten dauern. Ohne GitHub-Anmeldung können wir die Website nicht für dich live schalten.
