## Die Gateway-Einstellungen konfigurieren

Um verschiedene Einstellungen an Ihrem AIO GATEWAY vornehmen zu können,
gehen Sie ins *Hauptmenü* und von dort unter *Einstellungen* zu
*Gateways*.

![](/de/iqontrol_neo/iqneo_gateway_einstellungen.png)

Hier können Sie:

  - den Namen für Ihr Gateway ändern
  - die IP-Adresse Ihres AIO GATEWAYs anpassen
  - den Cloud-Access für die Einbindung von Cloud-Geräten oder die
    Remote-Steuerung aktivieren
  - den Cloud-Zugriff testen
  - die LED-Farbe Ihres Gateways ändern
  - den Die Zeitzone einstellen, sowie die Sommer- bzw. Winterzeit
    aktivieren
  - die Koordinaten für Ihren Standort abrufen oder manuell eintragen
  - die Systeminformationen Ihres Gateways einsehen
  - Ein [Firmware-Update](/de/iqontrol_neo/fwupdate) machen, falls eine
    neue Firmware für Ihr AIO GATEWAY verfügbar ist. 

Unter **Experteneinstellung** können Sie den Sensormodus ändern.

#### Der Sensormodus

Das AIO GATEWAY hat verschiedene Sensormodi zu Auswahl. Je nach
Gateway-Typ stehen hier verschiedene Modi aus folgender Liste zur
Auswahl:

  - Homematic
  - FS20
  - RS2W
  - WIR

Die AIO GATEWAYs der V6-Serie verfügen über einen speziellen 868 Mhz
Chip, in denen ein Sensormodus eingestellt werden kann. Das Einstellen
des Sensormodus sagt dem Chip, auf welchen Sensortyp dieser hören soll.
Der 868 Mhz Chips kann immer nur auf einen Sensortyp hören, z.B.
Homematic-Sensoren. Ist der Sensormodus auf Homematic eingestellt,
empfängt dieser Chip keine Meldungen von Sensoren anderer Hersteller.
Um also den Status der oben gelisteten Sensoren anzeigen zu können, muss
der Sensormodus in Ihrem Gateways entsprechend eingestellt werden.

Das V5 Plus verfügt über zwei 868 Mhz Chips, wobei hier einer immer im
Homematic-Modus läuft und der andere sich einstellen lässt.
