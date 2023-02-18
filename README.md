# Vorlage für ein Lerntagebuch mit GitHub Pages

Diese Vorlage kann verwendet werden, um ein Blog mit GitHub Pages für den Kurs [Bibliotheks- und Archivinformatik](https://github.com/felixlohmeier/bibliotheks-und-archivinformatik) zu erstellen.

1. Bei GitHub anmelden
2. Mit dem Button [Use this template](https://github.com/felixlohmeier/lerntagebuch/generate) ein eigenes Repository anlegen
    * Name und Beschreibung ausfüllen.
    * Für die Nutzung von GitHub-Pages muss das Repository öffentlich (public) sein.
3. Die Einstellungen (Settings) des neuen Repositorys aufrufen
    * Im Menüpunkt "Pages" im Pulldown-Menü "Source" den branch `master` auswählen und Save-Button drücken
    * Die Seite lädt neu. Es erscheint jetzt die Meldung mit der Internetadresse des Blogs: "Your site is ready to be published at http://...".
    * Das Lerntagebuch ist jetzt bereits online. GitHub generiert nach jeder Änderung im Repository innerhalb von Sekunden neue HTML-Seiten, die unter der Adresse ...github.io... automatisch veröffentlicht werden.
4. Metadaten in Datei `_config.yml` anpassen:
    * Ändern Sie Titel, Autor/in, Beschreibung.
    * Ändern Sie die E-Mail oder löschen Sie die Zeile, falls sie keine angeben wollen.
    * Setzen Sie Ihre Nutzernamen bei Twitter und GitHub ein oder löschen Sie die Zeilen.
5. Titel und Willkommenstext in Datei `index.md` anpassen:
    * Die Angabe "title: ..." setzt den Untertitel der Seite.
    * Die Überschrift "## ..." und der Willkommenstext sind optional.
6. Diese Anleitung in Datei `README.md` löschen (oder Erläuterungen zum GitHub Repository ergänzen)
7. Blogposts im Ordner `_posts` anpassen
    * Die Vorlage enthält zwei Beispieldateien. Ändern Sie darin Text und Metadaten.
    * Die Dateien können auch umbenannt werden.
8. Neue Blogposts erstellen
    * Wenn Sie weitere Blogbeiträge erstellen wollen, müssen Sie im Ordner `_posts` neue Dateien mit der Endung `.md` erstellen.
    * Orientieren Sie sich dabei an den Beispielen. Für die Darstellung in GitHub Pages sind die Metadaten (title: ..., date: ...) wichtig.
9. Weitere Hinweise (optional):
   * Die Lizenz in Datei `LICENSE` anpassen: Voreingestellt ist der Lizenztext CC-BY 4.0. Diese Lizenz wird automatisch im GitHub Repository angezeigt. Falls Sie auch auf dem Lerntagebuch einen Lizenzhinweis ergänzen wollen, könnten Sie dies unter `index.md` tun.
   * Beschreibung im GitHub Repository ergänzen: Ganz oben kann ein kurzer Beschreibungstext und eine Internetadresse angegeben werden. Das erleichtert den Besucher\*innen des GitHub Repositorys ihr Lerntagebuch zu finden.
   * Viele weitere Optionen finden Sie in der [Dokumentation von GitHub Pages](https://help.github.com/en/github/working-with-github-pages/setting-up-a-github-pages-site-with-jekyll).
