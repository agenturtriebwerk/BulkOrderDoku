Massenbestellung Dokumentation (BulkOrder)
==================

Massenbestellung ist ein Shopware-Plugin und kann über den Shopware Community Store bezogen werden: 
Beschreibung und Download im Shopware Community Store: http://store.shopware.de/template-design/massenbestellung

# Beschreibung
Mit dem Plugin „Massenbestellung“ wird eine zusätzliche Liste Ansicht für Artikel bereitgestellt aus der Shopkunden direkt bestellen können. 


# Installation
## Manueller Upload
1. Extrahieren Sie die Inhalte aus der heruntergeladenen ZIP-Datei.
2. Laden Sie den Ordner /TriebwBulkOrder per FTP auf Ihren Webserver in den Ordner /engine/Shopware/Plugins/Local/Frontend/.
3. Loggen Sie sich nun in Ihr Shopware-Backend ein.
4. Wählen Sie „Einstellungen“ -> „Plugin-Manager“.
5. Wählen Sie im „Plugin-Manager“ im linken Menü „Alle Erweiterungen“.
6. Suchen Sie in der Auflistung der „inaktiven Plugins“ nach „Massenbestellung“.
7. Klicken Sie in der Zeile von „Massenbestellung“ rechts auf das grüne Symbol. Das Plugin wird jetzt installiert. Wenn die Installation abgeschlossen ist, erscheint rechts oben im Backend eine Info, dass das Plugin erfolgreich installiert wurde.
8. Im sich nun öffnenden Pop-up wählen Sie „Plugin aktivieren“, nehmen die gewünschten Grundeinstellungen vor und klicken auf „Plugin-Einstellungen speichern“


## Installation über den Community Store
1. Loggen Sie sich nun in Ihr Shopware-Backend ein.
2. Wählen Sie „Einstellungen“ -> „Plugin-Manager“.
3. Wählen Sie den Tab „Community Store“ und suchen „Massenbestellung“.
4. Laden Sie das Plugin in Ihr System.
5. Öffnen Sie im Plugin-Manager den Tab „Einkäufe / Erweiterung“ und folgen dem manuellen Upload ab Schritt 5.


## Konfiguration des Plugins
1. Öffnen Sie die Grundeinstellungen und wählen dort „Weitere Einstellungen“ > „Massenbestellung“.
2. Nehmen Sie die gewünschten Anpassungen vor und klicken auf „Speichern“.


# Plugin-Einstellungen
![Grundeinstellungen](http://doku.agentur-triebwerk-shop.de/bulkorder/grundeinstellungen_bulkorder_2.png)
## Einstellungen
### Nur für eingeloggte Kunden
Legen Sie fest ob die „Massenbestellung“ nur eingeloggten Kunden oder auch nicht eingeloggten Besuchern zur Verfügung steht.

### Auf diese Kundengruppen beschränken
Beispiele:
* leeres Textfeld =  Massenbestellung  steht allen Kundengruppen zur Verfügung
* „H“ = Massenbestellung   steht nur der Kundengruppe  „B2B / Händler netto“ zur Verfügung
* „H|EK“ = Massenbestellung   steht der Kundengruppe  „B2B / Händler netto“ und der Kundengruppe  „Shopkunden“ zur Verfügung

### Umschalter für Listendarstellung aktivieren: ja/nein
Legen Sie fest ob Nutzer in den Artikel-Kategorien – neben dem Standard „Tabellen-Ansicht“ und  „Listen-Ansicht“ – in die „Massenbestellungs-Ansicht“ wechseln können.

### Menüpunkt im Headermenü anzeigen: ja/nein
Legen Sie fest ob im Headermenü der Navigationspunkt „Massenbestellung“ angezeigt werden soll. 

# Plugin-Anpassung  
## Bezeichnungen ändern
Sie können die verwendeten Standard-Bezeichnung des Punktes (und dessen englische Übersetzung) ändern unter: Einstellungen > Textbausteine. 


# Versionshistorie
1.0 Erste öffentliche Pluginversion

# Unverträglichkeiten
Hier werden die bekannten Unverträglichkeiten gelistet.
Wenn Sie Fragen zur Plugin-Verträglichkeit der Lieferampel haben, kontaktieren Sie gerne vorab unseren Support: shopware@agentur-triebwerk.de
* Shopware Developer Toolbar: wenn die Toolbar für das Frontend aktiviert ist, kann es zu Problemen mit dem verfügbaren Speicher von PHP kommen
 


