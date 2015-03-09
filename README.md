Massenbestellung (BulkOrder)
==================

Massenbestellung ist ein Shopware-Plugin und kann über den Shopware Community Store bezogen werden: 
Beschreibung und Download im Shopware Community Store.

Deutsch: http://store.shopware.com/triebw00878/massenbestellung.html 
English: http://store.shopware.com/en/triebw00878/bulk-order.html

### Beschreibung
Mit dem Plugin „Massenbestellung“ wird eine zusätzliche Listen-Ansicht für Artikel bereitgestellt. Aus dieser Ansicht können Kunden direkt mehrere Artikel in den Warenkorb legen. 

### Demo
Eine Frontend-Demo von "Massenbestllung" finden Sie hier: http://demo.agentur-triebwerk-shop.de/


## Installation
### Manueller Upload
1. Extrahieren Sie die Inhalte aus der heruntergeladenen ZIP-Datei.
2. Laden Sie den Ordner /TriebwBulkOrder per FTP auf Ihren Webserver in den Ordner /engine/Shopware/Plugins/Local/Frontend/.
3. Loggen Sie sich nun in Ihr Shopware-Backend ein.
4. Wählen Sie „Einstellungen“ -> „Plugin-Manager“.
5. Wählen Sie im „Plugin-Manager“ im linken Menü „Alle Erweiterungen“.
6. Suchen Sie in der Auflistung der „inaktiven Plugins“ nach „Massenbestellung“.
7. Klicken Sie in der Zeile von „Massenbestellung“ rechts auf das grüne Symbol. Das Plugin wird jetzt installiert. Wenn die Installation abgeschlossen ist, erscheint rechts oben im Backend eine Info, dass das Plugin erfolgreich installiert wurde.
8. Im sich nun öffnenden Pop-up wählen Sie „Plugin aktivieren“, nehmen die gewünschten Grundeinstellungen vor und klicken auf „Plugin-Einstellungen speichern“


### Installation über den Community Store
1. Loggen Sie sich nun in Ihr Shopware-Backend ein.
2. Wählen Sie „Einstellungen“ -> „Plugin-Manager“.
3. Wählen Sie den Tab „Community Store“ und suchen „Massenbestellung“.
4. Laden Sie das Plugin in Ihr System.
5. Öffnen Sie im Plugin-Manager den Tab „Einkäufe / Erweiterung“ und folgen dem manuellen Upload ab Schritt 5.


### Konfiguration des Plugins
1. Öffnen Sie die Grundeinstellungen und wählen dort „Weitere Einstellungen“ > „Massenbestellung“.
2. Nehmen Sie die gewünschten Anpassungen vor und klicken auf „Speichern“.


## Plugin-Einstellungen
#### Nur für eingeloggte Kunden
Legen Sie fest ob die „Massenbestellung“ nur eingeloggten Kunden oder auch nicht eingeloggten Besuchern zur Verfügung steht.

![BulkOrder_einstellungen_eingeloggte_kunden.jpg](http://doku.agentur-triebwerk-shop.de/bulkorder/BulkOrder_einstellungen_eingeloggte_kunden.jpg)


#### Auf diese Kundengruppen beschränken
Legen Sie fest ob die „Massenbestellung“ nur bestimmten Kundengruppen zur Verfügung steht. Beispiele:
* leeres Textfeld =  Massenbestellung  steht allen Kundengruppen zur Verfügung
* „B2B“ = Massenbestellung   steht nur der Kundengruppe  „B2B / Haendler“ zur Verfügung
* „B2B|EK“ = Massenbestellung   steht der Kundengruppe  „B2B / Haendler“ und der Kundengruppe  „Shopkunden“ zur Verfügung

![BulkOrder_einstellungen_kundengruppen.jpg](http://doku.agentur-triebwerk-shop.de/bulkorder/BulkOrder_einstellungen_kundengruppen.jpg)

#### Menüpunkt im Headermenü anzeigen
Legen Sie fest ob im Headermenü der Navigationspunkt „Massenbestellung“ angezeigt werden soll. 

![BulkOrder_einstellungen_menuepunkt.jpg](http://doku.agentur-triebwerk-shop.de/bulkorder/BulkOrder_einstellungen_menuepunkt.jpg)

![BulkOrder_frontend_menuepunkt.jpg](http://doku.agentur-triebwerk-shop.de/bulkorder/BulkOrder_frontend_menuepunkt.jpg)

#### Artikel-Sortierung im Navigationspunkt Massenbestellung
Legen Sie die Sortier-Eigenschaft für die Artikel im Navigationspunkt Massenbestellung (Kategorie übergreifende Ansicht) fest.

![BulkOrder_Screen_BE_Sortierung.jpg](http://doku.agentur-triebwerk-shop.de/bulkorder/BulkOrder_Screen_BE_Sortierung.jpg)


#### Umschalter für Listendarstellung aktivieren
Legen Sie fest ob Nutzer in den Artikel-Kategorien – neben dem Standard „Tabellen-Ansicht“ und  „Listen-Ansicht“ – in die „Massenbestellungs-Ansicht“ wechseln können.

![BulkOrder_Screen_BE_Umschalter_Liste.jpg](http://doku.agentur-triebwerk-shop.de/bulkorder/BulkOrder_Screen_BE_Umschalter_Liste.jpg)

![BulkOrder_frontend_listview_switch.jpg](http://doku.agentur-triebwerk-shop.de/bulkorder/BulkOrder_frontend_listview_switch.jpg)

#### Bewertungssterne in Listendarstellung ausblenden
Unterbinden Sie die Anzeige der Bewertungssterne in den Listenansichten von Massenbestellung

![BulkOrder_Screen_BE_Bewertungen_ausbelden.jpg](http://doku.agentur-triebwerk-shop.de/bulkorder/BulkOrder_Screen_BE_Bewertungen_ausbelden.jpg)



## Plugin-Anpassung  
### Bezeichnungen ändern
Sie können die verwendeten Standard-Bezeichnung des Punktes (und dessen englische Übersetzung) ändern unter: 
Einstellungen > Textbausteine. 

![BulkOrder_textbausteine.jpg](http://doku.agentur-triebwerk-shop.de/bulkorder/BulkOrder_textbausteine.jpg)

## Versionshistorie

1.1.0
- Anzeige der Artikel-Bewertung (Sterne) über Plugin-Konfiguration steuerbar
- Sortierung im Navigationspunkt "Massenbestellung" (Artikel-Liste über alle Kategorien) wählbar: Nach Name oder nach Artikelnummer

1.0.2
- Textbausteine in Englisch vorhanden

1.0.1 Anpassung für Shopware 4.1.3 und 4.2.
* Template-Anpassungen (box_article_bulk.tpl)
* Anpassung des Controllers an neue/angepasste Shopwarefunktionen

1.0 Erste öffentliche Pluginversion

## Unverträglichkeiten
Hier werden die bekannten Unverträglichkeiten gelistet.
Wenn Sie Fragen zur Plugin-Verträglichkeit der Massenbestellung haben, kontaktieren Sie gerne vorab unseren Support: shopware@agentur-triebwerk.de

* Shopware Developer Toolbar: 
Wenn die Toolbar für das Frontend aktiviert ist, kann es zu Problemen mit dem verfügbaren Speicher von PHP kommen
 


