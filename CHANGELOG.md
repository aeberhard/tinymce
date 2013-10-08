Changelog TinyMCE-Addon Version 2.4.1
=====================================

### Version 2.4.1 (2013-10-08)

* Behebung Sicherheitslücke in functions.inc.php tinymce_generate_image()

### Version 2.4 (2013-05-07)

* Modul-Installation/Aktualisierung
* Konfiguration erweitert um Bildparameter
* Anpassung der Einbindung von Bildern an den Bildparameter, jetzt auch ImageResize + ImageManager möglich

### Version 2.3 (2013-02-13)

* Update TinyMCE auf Version 3.5.8

### Version 2.2 (2012-08-22)

* Update TinyMCE auf Version 3.5.6

### Version 2.1.1 (2012-05-29)

* Versionsinfo angepasst
* Bugfix für PHP < 5.3, wg. function header_remove()

### Version 2.1 (2012-05-14)

* Update TinyMCE auf Version 3.5.0.1
* Bugfix doppelte ob_end_clean()
* nach Upload im MP funktionierte "Datei übernehmen" nicht
* Header mit Dateiname, bei "speichern unter" wird jetzt der Dateiname übernommen
* Beispielkonfiguration mit Tabellen-Buttons aufgenommen

### Version 2.0 (2012-03-09)

* Addon komplett neu geschrieben
* Update TinyMCE auf Version 3.4.9
* Einbindung TinyMCE im Backend und Frontend möglich
* verschiedene Konfigurationen werden jetzt in der DB gespeichert
* keine Tiny-Klasse mehr
* lauffähig ab Redaxo 4.0

### Version 1.6.1.1 (2011-07-15) - Tobias Krais

* Opera Bug im TinyMCE Redaxo Plugin behoben

### Version 1.6.1 (2011-07-08) - Tobias Krais

* Update TinyMCE auf Version 3.4.3.2
* Deutsches und Englisches Sprachpaket aktualisiert
* Emoticons und Media als Standard hinzugeuegt
* Anpassungen für REDAXO 4.2.x

### Version 1.6 (2010-03-29)

* Update TinyMCE auf Version 3.3.2
* Bugfix: Init-Script wird jetzt über die index.php ausgeliefert, tiny_mce_init.php entfällt da oft Rechteprobleme auftraten
* Medienpool-Popup überarbeitet, Datei übernehmen funktioniert jetzt auch nach Uploads	
* Medienpool übernimmt jetzt auch den Medien-Titel in das Tiny-Popup
* Bugfix: korrekter Pfad für content.css, Anzeige Dateiname bei CSS-Editor
* Addon-Konfiguration angepasst, neuer Parameter für individuelle Tiny Konfiguration, Optionen für Smileys, Media und Syntaxhighlighter entfernt
* Smileys und Media in Standardbuttons aufgenommen
* Anpassung redaxo-Plugin für Tiny
* Syntaxhighlighter entfernt
* JavaScript-Sourcen entfernt
* abschliessende ?> entfernt
* Anpassung für REDAXO 4.1.x, 4.0.x, 3.2.3

TODO:
* Security-Patch, siehe http://blog.webvariants.de/security-fix-fuer-redaxos-tinymce-addon
* evtl. um Syntaxhighlighter erweitern

### Version 1.5 (2009-03-25)

* Addon komplett ueberarbeitet
* Update TinyMCE auf Version 3.2.2.1
* Anpassung an neues Backend-Style
* Klasse pclzip entfernt, TinyMCE Source wird jetzt in das files-Verzeichnis kopoert, kein entpacken mehr notwendig
* .htaccess im Verzeichnis addons/tinymce/files/ hebt den Verzeichnisschutz auf für REDAXO < 4.2
* Konfiguration des Addons, Aktivierung, Standardsprache, Theme + Skin usw.
* Editiermoeglichkeit des Stylesheets fuer den WYSIWYG-Editor/Vorschau

### Version 1.0.1 (R4.0.1 Compatible) (2008-02-xx)

* TinyMCE Update auf 2.1.3
Bugfixes:
* Installation gibt jetzt korrekte Fehlermeldungen zurueck

###Version 1.0 (R4 Compatible) (2007-10-14)

* initial release
