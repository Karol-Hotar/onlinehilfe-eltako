## IQONTROL NEO Changelog

### Version 1.20 Bugfix Release

Device Integration

``` 
  IP-1768 JAB Anstoetz Integration
  IP-1816 Integration von neuen Eltako Geräten
  IP-1782 Integration von HMIP-FSI16 inkl. Integration von neuen HMIP Settings für V6 Serie
  IP-1655 Gealan Lüfter
  IP-1796 HMIP-BSM Unterstützung mit V5+ 
```

Feature

``` 
  IP-1611 Raumbezeichnung für Geräte in Szenen anzeigen lassen
```

Bug

``` 
  IP-1780 internorm i-tec Beschattungen als unbekanntes Gerät
  IP-1813 Alpha Fehlermeldung
  IP-1812 WIR Löschung von einem Gerätekanal
  IP-1810 Gatewaybackup erstellen aus Backup wiederherstellen
  IP-1809 Heizplan bearbeiten und löschen
  IP-1808 Eingabefelder Sonderzeichen Filter überarbeiten
  IP-1807 Android Zurück-Taste schließen von Popups
  IP-1805 V5+ Standort wird nicht korrekt abgeholt / gesetzt
  IP-1804 V5+ Pushgeräte im Task speichert nicht unter iOS
  IP-1803 Netatmo Module werden als offline angezeigt    
  IP-1778 Task Geräteadresse Zahl
  IP-1799 Elero anlernen ohne SID nicht möglich
  IP-1797 Fritzbox einbinden mit Sonderzeichen im Passwort
  IP-1787 V6+ Einrichtung speichert kein Passwort
  IP-1785 Hersteller HmIP aus Kategorie CO2 entfernen
```

### Version 1.19.2 Bugfix Release

Bug

``` 
   [IP-1784] - In-App Purchase unter iOS
   [IP-1794] - Smart Guard 2: Auf kleinen android Geräten kann Gerät nicht gelöscht werden
```

Verbesserung

``` 
   [IP-1790] - Cloudsystem Statusabfrage
```

### Version 1.19.1 Bugfix Release

Device Integration

``` 
  [IP-1759] - Brel M und B Motoren
  [IP-1756] - Blanke Systems Smart Home Activ
  [IP-1757] - Blanke Systems Smart Home Basic
  [IP-1762] - eltako FWS81 Wassermelder
  [IP-1771] - Elero Schalter, Dimmer und Heizung Integration
  [IP-1746] - Gaposa 434 MHz anlernen
```

Feature

``` 
  [IP-1750] - Internorm IV 40 Lüfter Updatemöglichkeit
  [IP-1755] - elero: Update auf 60 Kanäle
```

Bugfixes

``` 
  [IP-1658] - IQF-Sense Kipp Status
  [IP-1703] - HM Rollladen Spinner Anlerntext
  [IP-1745] - elero Anlernen: Kanäle werden als Int und nicht al Hex gesendet
  [IP-1748] - Coulisse Fehlermeldung in Detailansicht
  [IP-1749] - Anlegen von mehr als 6 Auslösern / Bedingungen / Aktionen auf V6+
  [IP-1751] - Firmware Update V6+
  [IP-1753] - Geräteliste lässt sich nicht öffnen, wenn Openweathermap als Gerät eingebunden ist.
  [IP-1760] - Unbekannter Gerätetyp in Taskmanager
  [IP-1765] - Smart Guard 1: Empfindlichkeitseinstellung in Einstellung entfernen
  
```

### Version 1.19 Release

Device Integration

``` 
  [IP-1568] - Integration Füllstandsensors HM-Sen-Wa-Od
  [IP-1625] - Coulisse Integration
  [IP-1645] - Integration Kopp Freecontrol 3
  [IP-1621] - Integration HmIP-SLO Lichtsensor
  [IP-1634] - Integration HmIP Wetterstation
  [IP-1607] - Homematic IP Access Point als Cloudanbindung
  [IP-1666] - Integration HmIP-BSL Schalter mit Signalleuchte
  
```

Feature

``` 
  [IP-519] - Einstellungen für HM / HM-IP Rolladen
  [IP-1303] - Erstellen Gateway Backups
  [IP-1604] - Bewegungsmelder HmIP-SMO - "Einstellung der Auslösehelligkeit"    
  [IP-1613] - Direktverknüpfung TF-DTB mit Dimmer Geräten
  [IP-1614] - Taskmanager: Hysterese bei Geräten mit <=/>= Einstellungen einstellbar machen
  [IP-1617] - Direktverknüpfung Heizung
  [IP-1618] - Direktverknüpfung Taster An/Aus
  [IP-1620] - Spanische Sprache
  [IP-1636] - Smartguard 2 Anlernen über QR Code
  [IP-1710] - Smart Guard2: Empfindlichkeitseinstellungen PIR Sensor
  [IP-1735] - HM / HmIP Beschattung Einstellung: Position invertieren
  
```

Verbesserung

``` 
  [IP-1148] - Demo beenden Option in Menüliste ergänzen
  [IP-1446] - Senden WLAN Passwort verschlüsselt im AP Modus
  [IP-1570] - HmIP Hunter Douglas Motoren: Endlagen einstellen
  [IP-1572] - Passwortabfrage bei Gateway Löschung
  [IP-1619] - Buttontexte von MConfirmDialogues
  [IP-1648] - Wiederholtes drücken auf Zurück Button auf Android öffnet entsprechend viele Popups
  [IP-1651] - HmIP Access Point Codeanpassung Funktions-Rückgabe
  [IP-1656] - Task Popups vertikale Zentrierung bei Auslöserwechsel
  [IP-1659] - Aufteilung HmIP Wetterstation Gateway / AP Integration
  [IP-1678] - Header Titel Bezeichnung Zentrierung
  [IP-1679] - Raum Header Infos Aktualisierung
  [IP-1681] - SmartGuard: Beim Löschen auch aus Alarm löschen
  [IP-1688] - SmartGuard: Nach Alarm zurücksetzen in Alarm Tasks wieder hinzufügen
  [IP-1692] - Taskauslöser Bei "Voltage" Sliderschritt auf 0.1 setzen
  [IP-1700] - Hysteresewert einstellbar machen
  [IP-1705] - Homematic BidCos Helligkeitssensor
  [IP-1718] - GW Backup Dialog: Kein Overlay bei Passwortabfrage
  [IP-1721] - Laden und Wiederherstellen von Gatewaykonfiguration bei Backup Prozess
  [IP-1728] - Konfiguration laden von GW Fehlermeldung
  
```

Bug

``` 
  [IP-1465] - INTERTECHNO Dimmer
  [IP-1469] - Inbetriebnahme Zurück-Button
  [IP-1494] - In GW-Einstellungen gefangen
  [IP-1546] - Dashboard Alarm Unendlich Spinner mit V5+
  [IP-1623] - HMIP-BROLL - "Bei der Abfrage ist ein Fehler aufgetreten"
  [IP-1637] - Push Geräte werden in den Alarm Einstellungen auf iOS nicht angezeigt {1}{1}...
  [IP-1638] - Eltako FMZ61 kann nicht eingelernt werden
  [IP-1641] - keine Nachrichten mehr als Aktion beim Alarm - Android
  [IP-1649] - Experteneinstellungen/Alarm zurücksetzen tippen
  [IP-1652] - HM Bidcos Rollladen Sliderelement verkehrt herum (V6)
  [IP-1653] - HmIP Hunter Douglas Motor Position
  [IP-1660] - EnOcean: eltako/elero FRM60 Status vertauscht
  [IP-1661] - Tasks auf 2 Gateways besitzen die selbe ID    
  [IP-1671] - Dashboard Oco Kamera -> Unbekannter Fehler
  [IP-1672] - Falscher Text bei QR-Code löschen
  [IP-1680] - WLAN Ändern funktioniert nicht
  [IP-1687] - Anlerntexte Homematic
  [IP-1689] - MACO eTronic Anlernvorgang
  [IP-1706] - Demomodus Bugs
  [IP-1708] - Hm Wetterstation: Listen- / Detailansicht
  [IP-1711] - SmartGuard 2 QR Code Archiv    
  [IP-1717] - HMIP Wetterstation Taskauslöser
  [IP-1723] - HMIP-BSL über HMIP AP Aktionen in Taskmanager
  [IP-1724] - HmIP-SLO reagiert nicht im Task als Auslöser
  [IP-1726] - Direktverknüpfung Heizung - Verknüpftes Gerät wird gelöscht führt zu Javascript execption
  [IP-1739] - Phillips Hue Color Lamp - Task Fehler
  [IP-1740] - Verzögerung in Sekunden -> Ein unbekannter Fehler ist aufgetreten
```

### Version 1.18.1 Bugfix Release

Feature

``` 
  [IP-1616] - IQF-Sense Fenstersensor
```

Verbesserung

``` 
  [IP-1626] - V6+ bei Inbetriebnahme über V5+ anzeigen
```

Bug

``` 
  [IP-1622] - Mit dem V6+ werden keine Tasks ausgeführt/lassen sich nicht bearbeiten
  [IP-1624] - Wassermelder HmIP SWD funktioniert nicht vollständig
  [IP-1627] - Siegenia aeromatVT hat keine Steuerelemente
  [IP-1629] - V6+ Anlernen von EnOcean Geräten erfordert EnOcean Stick
```

### Version 1.18 Release

Feature

``` 
  [IP-1519] - Verzögerung Szenen ausführen
  [IP-1557] - Szenen als Favoriten anlegen
  [IP-1584] - Integration V6+ Gateway
  [IP-1603] - Nobily UP-Aktor
  [IP-1606] - Feste Sprache in Einstellungen
  [IP-1610] - Schieberegler für Lampenhelligkeit auf Prozentsatz einstellen
  [IP-1592] - Neuer Opus Dimmer
```

Verbesserung

``` 
  [IP-1467] - Szenen in Cloud speichern
  [IP-1488] - Debug Informationen Support Anfrage erweitern
  [IP-1573] - Löschung letzten Gateways soll App zurücksetzen
  [IP-1578] - Integration Italienisch
  [IP-1586] - Italian language support
  [IP-1589] - Kalenderansicht: Deaktivierte Tasks als solche Kennzeichnen
  
```

Bug

``` 
  [IP-1574] - Favoriten festlegen: Unbekannter Fehler
  [IP-1594] - Centronic Rollläden Darstellung in Tasks "unbekanntes Gerät"
  [IP-1602] - Passwort vergessen Feld
  [IP-1605] - Afriso CO2 Sensor in Taskmanager
  [IP-1608] - eltako BR14 FSR wird als Licht angelernt, aber als Schalter dargestellt
  [IP-1609] - FS20 Dimmer im Raum - ein unbekannter Fehler ist aufgetreten
  [IP-1615] - V6+ Wlan Wechseln
```

### Version 1.17.1 Bugfix Release

Improvement

``` 
  [IP-1579] - Gateway Neustart in Gateway Experteneinstellungen
  [IP-1581] - Unterstützung Französisch
```

Bug

``` 
  [IP-1580] - Gateway gesperrt: Fehlermeldung beim Editieren Gateways von Drittanbietern
  [IP-1582] - Rückauflösung Fritzbox Dect Alarmaktionen fehlerhaft
  [IP-1583] - Gateway entsperren: PIN Nr. wird bei Eingabe abgeschnitten
  [IP-1587] - SSID Länge im Setup
  [IP-1590] - "Powered by OpenWeathermap" überschneidet sich mit Statusicons (Dashboard) 
  [IP-1591] - Verbindungsprobleme bei SSIDs mit Sonderzeichen
  [IP-1593] - FWS61-24DC nicht auswählbar
```

### Version 1.17

Device Integration

``` 
  [IP-1535] - Schüco SensTrack Verschlusskontakt
  [IP-1536] - Hunter Douglas Ease HmIP
  [IP-1563] - Gaposa Motoren
  [IP-1565] - Nobily PR und PRE Motoren
  [IP-1537] - Integration WIR 4-Kanal Schaltaktor
  [IP-1555] - Integration Eltako Wetterstation FWS61-24DC
  [IP-1562] - Eltako 2fach Kanal Schalters FMS61NP-230V
  [IP-1421] - Integration V5+ Möhlenhoff Alpha
```

Feature

``` 
  [IP-1447] - Alarm Szenario Rehau
  [IP-1519] - Verzögerung Szenen ausführen
  [IP-1541] - QR Code Archiv
  [IP-1569] - whats new - Anzeige von neuen Features/Verbesserungen in der neuen Version
```

Improvement

``` 
  [IP-1042] - Gerät hinzufügen: Bei mehreren Gateways muß das jeweilige 2x ausgewählt werden
  [IP-1439] - Konfigurationen Auflistung Reihenfolge
  [IP-1489] - Möhlenhoff Alpha Live Soll-Temperatur
  [IP-1502] - Supportformular getStates mit config Parameter erweitern
  [IP-1521] - Einlernen FTKE: Bild des TF-FKE wird gezeigt
  [IP-1522] - Verbesserungen eltako Kategorien
  [IP-1524] - Sliderfeedback: Anzeige Ändern Werte Temperatur & Dimmer
  [IP-1529] - Sortierung Szenen
  [IP-1532] - Importieren Szenen Kommandos in Tasks
  [IP-1544] - Prüfen, ob Gateway gesperrt ist, bevor Geräte gelöscht werden können
  [IP-1545] - Alarm: Erzwingen Änderung Default PIN
  [IP-1547] - Konto löschen: Kontopasswort Abfrage bevor Konto gelöscht wird
  [IP-1553] - Kaiser Nienhaus Mercator: Status abrufen Detailansicht
  [IP-1556] - Firmware Update: Prüfe auf Lock
  [IP-1558] - HM Rollläden Laufzeit einstellen
  [IP-1559] - Roto Dachfenster wird unter Geräte als Beschattung angezeigt (Ticketnr. 26688)
  [IP-1564] - Becker Rolladen - Feedback Detailansicht
```

Bug

``` 
  [IP-834]  - Devices: smartwares window contact status is vice versa
  [IP-1528] - Möhlenhoff Alpha 2 Geräte werden immer nur vom ersten Alpha Gateway eingelesen
  [IP-1531] - RS2W 2Fach Funkwandschalter
  [IP-1546] - Dashboard Alarm Unendlich Spinner mit V5+
  [IP-1548] - Elero Zwischen-/Lüftungsposition im Task vertauscht
  [IP-1561] - HM Detailansicht Position vom Sliderelement nicht dargestellt
  [IP-1530] - Alarmtaskzeitschaltung ändert Zeitschaltung in anderen Tasks
```

### Version 1.16

Device Integration

``` 
  [IP-1520] - Integration eltako FRM60 Rollladen
  [IP-1384] - Integration Siegenia Drive Geräte
  [IP-1385] - Siegenia Fenstersensor
  [IP-1436] - Integration Becker EnOcean Rollladenmotor
  [IP-1498] - Rohrmotor24 Geräte
  [IP-1500] - RS2W Jalousie Aktor
  [IP-1503] - FRITZ!DECT 301 Heizkörper Thermostat
  [IP-1505] - Elero EnOcean Beschattung
  [IP-1508] - Eltako Baureihe 14/61
  [IP-1293] - Ring Cloudgerät
```

Improvement

``` 
  [IP-998] - FS20 Dimmer integrieren
  [IP-1506] - Hinweis: Android Mobile Daten ausschalten, wenn kein Gateway gefunden wurde
```

Bug

``` 
  [IP-1011] - elero Rollladen wird in Cloud exportiert mit Kategorie Temperature
  [IP-1337] - Elero Rollladen Zwischenposition
  [IP-1432] - Warema Rollladen Task "unbekanntes Gerät"
  [IP-1491] - HM-LC-Sw2PBU-FM in Taskmanager
  [IP-1497] - HM 4fach Schalter Taskaktion
  [IP-1501] - Internorm Fensterkontakt Status Geschlossen
  [IP-1504] - eltako Baureihe 14 kein Anlernen bei zwei Gateways
  [IP-1511] - IOS Input nicht zuverlässig defokusiert
  [IP-1514] - elero: Einstellen der Zwischen-/Wendeposition funktioniert nicht
```

### Version 1.12

Device Integration

``` 
  [IP-1474] - Integration Hm Regensensor HM-Sen-RD-O
  [IP-1471] - elero Rollladen mit Flüstermodus
  [IP-1482] - Philips HUE SmartPlug
  [IP-1483] - Internorm Fenstersensoren
  [IP-1484] - Internorm Lüfter
  [IP-1485] - Internorm Blinds
```

Improvement

``` 
  [IP-1443] - Verbesserungen Hautau Feedback
  [IP-1461] - Fragezeichen für undefined-Status durch anderes Symbol ersetzen
  [IP-1480] - Feedback Hoppe Fenstergriff QR Codes
  [IP-1481] - Feedback Roto eDrive
  [IP-1487] - Rollladen / Jalousie Button-Icons austauschen
```

Bug

``` 
  [IP-1453] - Tasks: HM-LC-Dim1L-Pl Aktion Bezeichnung "onTo"
  [IP-1457] - GW Passwort setzen fehlender Sprachschlüssel
  [IP-1458] - Fehlende Sprachschlüssel Hoppe eFenstergriff
  [IP-1459] - Update Account Passwort im Cloudservice Module
  [IP-1472] - Entfernen Position Button HM Blind Detailansicht
  [IP-1473] - Verbesserung RF/IR Geräte anlernen
  [IP-1478] - shutter2 Gerätetypen werden unter Gerätekategory Sonstiges angezeigt
```

### Version 1.11

Device Integration

``` 
  [IP-1249] - Einbinden Hoppe eFenstergriff
  [IP-1380] - Hautau Geräte
  [IP-1381] - Roto DST
  [IP-1389] - uHoo Sensor
  [IP-1410] - Roto Comtec V5+9 Integration
  [IP-1427] - Roto eDrive
  [IP-1464] - Hörmann Homematic IP Modul
```

Feature

``` 
  [IP-943] - Hilfe-i bei Warema ergänzen
  [IP-996] - HmIP Wassersensor Sabotage Status
  [IP-1424] - Integration V5+ Hautau Task Bedingungen
  [IP-1425] - Hautau Discovery
  [IP-1372] - Cloud Access 14-Tage kostenlos Testen Aktivierung in App integrieren
```

Improvement

``` 
  [IP-1316] - HM-LC-Sw4-PCB: Kanal 2-4 Einbinden
  [IP-1333] - Sonos Listenelement Tablet
  [IP-1341] - Roto Comtec Sensoren Integration in V5+
  [IP-1353] - UI Heizkomponenten: Die Anzeige von Soll- und Istwert ist bei den unterschiedlichen Marken sehr unterschiedlich.
  [IP-1359] - Touchfeedback Code / IR Vorlagen
  [IP-1374] - Live Slider Feedback
  [IP-1387] - Timeout beim Anlernen verlägern
  [IP-1394] - eltako Dimmer Befehle von dimTo auf on und off ändern
  [IP-1411] - Dashboard Überarbeitung Kategorie "Sensoren"
  [IP-1413] - Hersteller alphabetisch sortieren
  [IP-1417] - Detailansicht HmIP ASIR Sirene
  [IP-1418] - Verbesserung Alarm aktiv/inaktiv Icon
  [IP-1419] - Wassersensor Alarmicon: Alarmzustand muss besser sichtbar sein
  [IP-1426] - FS20 Dimmer Slider zum dimmen
```

Bug

``` 
  [IP-686] - Tasks: HMIP-STH, Save Error, many fields can not be used as a trigger or an action.
  [IP-732] - Tasks: HM-LC-Dim1L-Pl darker and birghter action do not work
  [IP-762] - Devices: Intertechno ITLR-300 (dimmer) controls are not in sync
  [IP-944] - Device: Siral Rollland functionality and unimplemented feature.
  [IP-1050] - Homematic IP-Rollladenaktoren werden nicht korrekt angelernt
  [IP-1075] - FS20 ist unter Licht nicht aufgeführt. Dimmer können nur über Typ "Schalter" integriert werden.
  [IP-1317] - INTERTECHNO Dimmer
  [IP-1370] - Hilfe i führt bei Warema in eine "Sackgasse"
  [IP-1379] - Devices: delete a becker device
  [IP-1390] - Rückauflösung von Kaiser Nienahaus Mercato Aktionen in Taskmanager
  [IP-1397] - Brennenstuhl B4 hat keinen Status
  [IP-1403] - V5+ Heizplan: Kein Speichern, wenn Cloud Access Passwort gesetzt ist
  [IP-1404] - Anlernen/Steuern von ELRO (Brennenstuhl)
  [IP-1405] - Heizplan Geräteauswahl nicht scrollbar
  [IP-1406] - Gateway Experteneinstellungen: WLAN ändern: WLAN Liste scrollt nicht
  [IP-1407] - Nach Themewechsel falsches Info-Icon auf Dashboard
  [IP-1408] - Cloudverbindung authorisieren mit Sonderzeichen
  [IP-1409] - FS20 Rollladenaktor: Sendet falsche Befehle
  [IP-1412] - Steuerung von Intertechno Rollläden (Support)
  [IP-1414] - Iconauswahl Fernbedienungen
  [IP-1415] - HM-ES-PMSw1-Pl keine Anzeige von Verbrauch auf V5+
  [IP-1416] - Dashboard: Sensoren -> Wetterstation hat kein Icon
  [IP-1433] - Cloud Services Test angezeigt bei User mit Unlimited Cloud Access
  [IP-1437] - KaiserNienhaus Mercato Statusabfrage beim Aktualisieren
```

### Version 1.10

Feature

``` 
  [IP-995] - Umsetzung der neuen Ansicht zur zeitbasierten Kontrolle von Heizungen
  [IP-1342] - Direktverknüpfung HmIP Geräte
  [IP-1350] - Integration HmIP Fußbodenheizung (HmIP-FAL230-C6)
```

Verbesserung

``` 
  [IP-913] - UI : focus on Password field on 3rd step of gw setup
  [IP-1043] - Homematic Rauchmelder: Bestätigungsmeldung hinzufügen, wenn Reset-Taste gedrückt wurde
  [IP-1088] - Intertechno Geräte anlernen ohne Fernbedinung
  [IP-1184] - QR Code Herstellerliste: GW Prüfung
  [IP-1203] - Erfassung und Aktualisieren von GW-Infos
  [IP-1340] - Roto Com-Tec Sensoren: Verbesserung Anlernprozess
  [IP-1343] - Verbesserung Listenansicht Phone Ansicht
  [IP-1344] - Anpassung Touchfeedback
  [IP-1348] - Heizplan: Vorlage speichern rausnehmen
  [IP-1354] - Gleichzeitige HTTP-Anfragen bei Cloud Verbindungen
  [IP-1376] - Opus 2-Kanal Aktor Cloudexport
  [IP-1377] - Opus Blind: Detail view
  [IP-1378] - Opus Adresse in Geräteeinstellung anzeigen lassen
  
```

Bug

``` 
  [IP-701] - Push in Tasks bei nicht eingerichtetem Push-Gerät ohne Hinweis nicht wählbar
  [IP-904] - Devices: teach-in the Intertechno devices without a remote control does not work
  [IP-946] - Device Status: Homematic HM-LC-Dim1L-PI displays wrong status.
  [IP-1010] - Task-Manager: Gespeicherte Tasks werden sind nach Speichern und Neuöffnen verändert
  [IP-1085] - FS20 Bewegungsmelder: wird nicht als Bewegungsmelder sonder Schalter angelernt
  [IP-1100] - Somfy Switch als Task Aktion bei V6
  [IP-1178] - FW-Update Popup erscheint mehrmals nach Zurücksetzen
  [IP-1234] - Bei IR Geräten fehlt die Auswahlmöglichkeit des IR-Ausgangs
  [IP-1237] - Devices: HMIP-eTRV boost and auto don't work and in tasks cause problem
  [IP-1322] - TF 100A 230V auf V5+: Anzeigefehler des Icon beim Anlernen
  [IP-1338] - Bei mehreren Sonos Geräten lässt sich keins hinzufügen
  [IP-1349] - Eltako Thermostat FKS: Taster sperren entsperren
  [IP-1355] - Becker Jalousie fährt nicht in die Endlagen
  [IP-1362] - IPhone 6s als Pushgerät anmelden nicht möglich
  [IP-1363] - iOS 13: Push Nachrichten funktionieren nicht mehr
  [IP-1365] - OPUS QR Code mit nur zwei Feldern können icht anglernt werden
  [IP-1371] - Heizplan: Eltako FKS hat auf V5+ nicht reagiert
```

### Version 1.09

Device Integration

``` 
  [IP-1257] - eltako TF-2ZT Integration
  [IP-1258] - eltako TF-4PT Integration
  [IP-1260] - Integration eltako TF-AHDSB-FAH
  [IP-1261] - Integration eltako TF-AHDSB-TF
  [IP-1264] - eltako TF-BSB
  [IP-1265] - eltako TF-BSB55
  [IP-1266] - eltako TF-DTB
  [IP-1267] - eltako TF-FGB
  [IP-1268] - eltako TF-FKS
  [IP-1269] - eltako TF-FTSB
  [IP-1270] - eltako TF-IUS
  [IP-1271] - eltako TF-TRHB, MODUS FHK
  [IP-1272] - eltako TF-TRHB, MODUS TF61
  [IP-1273] - eltako TF-TRHB55, MODUS FHK
  [IP-1274] - eltako TF-TRHB55 , MODUS TF61
  [IP-1275] - eltako TF-TRSB, MODUS FHK
  [IP-1276] - eltako TF-TRSB, MODUS TF
  [IP-1277] - eltako TF-TRSB55, MODUS FHK
  [IP-1278] - eltako TF-TRSB55, MODUS TF
  [IP-1279] - eltako TF100A-230V
  [IP-1281] - eltako F6T65B
  [IP-1282] - eltako FAH60
  [IP-1283] - eltako FIH65B-wg
  [IP-1286] - Hermann Uhr / Enjoy Motors
  [IP-1292] - eltako TF-WTB / TF-WTB55
  [IP-1296] - Roto Com-Tec Basic
  [IP-1297] - Roto Com-Tec Comfort
  [IP-1298] - Roto Com-Tec Comfort S
```

Feature

``` 
  [IP-1299] - V6 Serie: LED des Gateways schalten als Taskmanager Aktion
```

Verbesserung

``` 
  [IP-1030] - Erweiterte Logs: Loggen von Exceptions
  [IP-1136] - Tasks/ Szenen: Warnhinweis bei Zurück Button nach Veränderung
  [IP-1160] - Szenen sollten schon im Erstellen Dialog testbar sein
  [IP-1240] - Kameraansicht Startseite: auf Gruppenansicht Kameras leiten
  [IP-1241] - Supportanfrage: Eingabemöglichkeit Support Ticket No.
  [IP-1247] - OPUS: Anlernen Sensoren mit QR Code
  [IP-1250] - OPUS Beschattungsaktoren: setAngle, stepUp, stepDown Befehle integrieren
  [IP-1263] - Anzeige RSSI Wert in eltako Geräte Eigenschaften
  [IP-1290] - Kalenderansicht: es werden keine Astro Trigger dargestellt
  [IP-1294] - OPUS Bridge 2-Kanal Funktion
  [IP-1312] - Tasks: Hinzufügen von Auslöser, Bedingungen und Aktionen unter den Task Elementen
  [IP-1318] - Rehau NEA Smart als Gateway hinzufügen
  [IP-1319] - Kopp Fußbodenheizung als Gateway hinzufügen
  [IP-1327] - SSID in Gateway Info
  [IP-1328] - HM Dimmer Icon: Normale Glühbirne mit Status aus (zeigt keinen Status)
```

Bug

``` 
  [IP-1052] - Opus Schalter: Nach Anlernen in App nicht bedienbar bis Schalter manuell gedrückt
  [IP-1066] - HM-ES-PMSw-1-PI-DN-R1 kein Status unter V6 Gateways
  [IP-1242] - Opus Rauchmelder: Fehler beim Speichern als UND-Bedingung in Task
  [IP-1243] - Firtzbox: Anlegen mehrer Geräte
  [IP-1246] - Sonos Alarm in Tasks löst nicht aus
  [IP-1253] - Fehler bei Auswahl Sonos Alarm
  [IP-1254] - Sonos Alarm Task: 2. Sonos Speaker nicht auswählbar
  [IP-1256] - Importierte Cloudgeräte nicht mehr editierbar
  [IP-1289] - FS20 Geräte mit Fernbedienung anlernen funktioniert nicht
  [IP-1301] - Demomodus
  [IP-1305] - Task hängt sich auf, wenn Geräte nicht gefunden werden.
  [IP-1307] - Nuki Schloss: Listitem Buttons haben kein Touch Feedback
  [IP-1308] - Nuki: Gerät lässt sich in App nicht löschen, wenn keine Verbindung besteht
  [IP-1313] - Fernbedinungsvorlage: Taste "0" geht nicht in Szene
  [IP-1314] - Szenen und Kalender auf Startseite eines Tablet
  [IP-1321] - Import Nuki-Gerät: Meldung, dass bereits alle Geräte dieses Gateway hinzugefügt. Jedoch kein NUki-Gerät vorhanden.
  [IP-1325] - F6T65B: Andere Bezeichnungen & Zusatzfunktionen
  [IP-1326] - F6T65B: Scheint als Auslöser in Taskmanager nicht zu funktionieren
  [IP-1332] - Anlegen IP Geräte als Gateway darf nicht möglich sien, wenn V5+ angelegt ist.
```

### Version 1.08

``` 
  Bug
  [IP-738] - EiMSIG Fenstersensor: Statusmeldungen unzuverlässig
  [IP-791] - Oco: recordings nicht zuverlässig aufrufbar
  [IP-797] - Oco: Beim Versuch Recordings zu laden, kann man nicht abbrechen
  [IP-810] - Devices: Renkforce(RS2W) window contact status does not change
  [IP-864] - Devices: Eltako FRW add in task error.
  [IP-871] - Task: Bei tradfri RGB-Lampe funktioniert Farbtemperatur nicht
  [IP-897] - Cloud Export: NIcht möglich --> Fehlermeldung
  [IP-921] - Firmware Update: Pop-Upmeldung erscheint nach Update erneut und sorgt für Crash
  [IP-922] - Firmware-Update: Fehler beim aktualisieren --> Gateway in App nicht erreichbar
  [IP-948] - Device Status: Homematic HM-ES-PMSw1-PI-DN-R1 displays wrong status.
  [IP-983] - Learning devices START button does nothing.
  [IP-989] - Bei zwei V5+ Modulen sind nur die Tasks von vom ersten Gateway unter "Alarmtasks"
  [IP-1003] - Device: IR-Fernbedienung has icon issue
  [IP-1008] - App crasht wenn Systemsprache nicht deutsch oder englisch ist
  [IP-1016] - Supportanfrage: SID wird in Gateway Daten nicht maskiert
  [IP-1017] - Supportanfrage: Ändern der Einstellungen nicht möglich
  [IP-1021] - V6: elero Aktionen werden nicht eingelesen
  [IP-1022] - Beschreibungstext beim Anlernen von Warema EWFS falsch
  [IP-1023] - Es kann nur ein Warema EWFS Gerät angelernt werden
  [IP-1024] - IR-Vorlage: Ausgewähltes Icon wird nicht angezeigt, wenn man den Befehl wieder öffnet.
  [IP-1049] - V6 Taskmanager Fehler beim Speichern eines Task mit mehreren Bedingungen
  [IP-1059] - Devices: IR connection - after code reset, the text field will not get any new value
  [IP-1065] - Wetterseite öffnet automatisch Geonames.org Verlinkung
  [IP-1074] - IR-Code: Anzeige und Übersetzung falsch/fehlt
  [IP-1081] - iOS: App verliert Inhalt
  [IP-1082] - Gateway Einstellungen: Bei Öffnen der Einstellungen kommt GW CRC Error
  [IP-1083] - Gateway Einstellungen: FW Update Endlosschleife
  [IP-1086] - Anzeige Sensormodus Gerät Anlernen
  [IP-1092] - Taskmanager: Zeitauswahl: 00:00 und 24:00 Uhr einstellbar
  [IP-1093] - Dark Scheme: Aktiv-Elemente nur schwer erkennbar
  [IP-1111] - Support-Mail: Text zurücksetzen funktioniert nicht
  [IP-1112] - Sonos-Gerät hinzufügen: Gerät wird gefunden, kann aber nicht hinzugefügt werden
  [IP-1114] - Gateway Infos unter Einstellungen werden nicht aktualisiert
  [IP-1117] - ELTAKO: Nur TF61D-230V ist als "Licht" auswählbar
  [IP-1118] - ELTAKO: FTKE Fensterkontakt sollte auch als Tür anlernbar sein
  [IP-1125] - eltako Generic "Rolladen" funktioniert noch nicht
  [IP-1128] - Fritzbox hinzufügen: Gatewayeinstellung --> Fehler bei "Fritzbox hinzufügen"
  [IP-1131] - Bei Alarm in der Hauptansicht wird bei mir immer ein ? angezeigt?
  [IP-1132] - Cloud Export Fehler
  [IP-1135] - Gateway disconnected icon verschwindet deutlich verzögert
  [IP-1140] - ELTAKO: FTR65HB wird mit eltako_thermo eingelernt
  [IP-1141] - ELTAKO: Heizung - Fehlende Beschriftung der Temperaturen
  [IP-1143] - eltako Geräte Einlernprozess: Drücken auf Abbruch trigged delSensor zweimal
  [IP-1149] - eltako Rolladen (Generic): keine Laufzeit einstellbar
  [IP-1152] - ELTAKO: TF-FTE the status is not changing in the devices page - sensors tab - favorite tab
  [IP-1153] - Eltako TF-4PT55 & 4PT liefert überhaupt keinen Status via V5Plus
  [IP-1154] - Eltako TF-1FT liefert überhaupt keinen Status via V5Plus
  [IP-1156] - Eltako Rauchmelder TF-RWB zeigt nur ausgelöst-Status
  [IP-1162] - Eltako TF-BHSB: Anlernen als TF geht nicht
  [IP-1163] - Eltako TF-BHSB: Anlernen als FBH geht, zeigt aber nur Helligkeitswerte und Fragezeichen
  [IP-1164] - Maco Fenstersensor: Anlernbar zeigt aber keinen Status / V6 mini E
  [IP-1165] - Eltako Fenstersensor FTK kann bei V5 Plus und V6 mini E nicht angelernt werden
  [IP-1166] - Eltako FTKB-Hg lässt sich nicht anlernen
  [IP-1167] - TF-FKE Statusanzeige geht nur unter "Räume"
  [IP-1169] - TF-1FT Status stimmt nicht
  [IP-1171] - Eltako QR-Code scannen Text unverständlich
  [IP-1174] - Eltako: FZS65 in tasks, reopening the task causes problem
  [IP-1176] - ELTAKO: FABH65S status as a trigger causes an error
  [IP-1177] - Eltako: FABH65S task is not triggered
  [IP-1183] - Eltako-RWB nicht als Auslöser wählbar
  [IP-1185] - Fehlermeldung Aktor steht noch auf TBD
  [IP-1186] - Fritz Statusanzeige aktualisiert nicht richtig
  [IP-1187] - Fritz Thermostat zeigt immer die falsche Temperatur an
  [IP-1188] - Eltako Aktor TF-61D ist nicht anlernbar
  [IP-1189] - Eltako Aktor TF-61J ist nicht anlernbar
  [IP-1190] - Statusabfrage im Remote-Modus mit getunnelten Geräten funktioniert nicht richtig
  [IP-1191] - Eltako Jalousie TF61J in Und-Bedingung crasht Task
  [IP-1199] - Tab-Anzeige doppelt (mehrfach) bei Drücken während der der Tab geladen wird
  [IP-1202] - ELTAKO: FBH65S is a motion sensor
  [IP-1205] - Eltako 100D-230V: Bei Einlernen falsch und später oft fehlerhaft
  [IP-1206] - Eltako 100D-230V: Anlerntext unverständlich
  [IP-1207] - Eltako 100L-230V: Anlerntext unverständlich
  [IP-1209] - TF-4FT löst keine Tasks aus
  [IP-1211] - Eltako TF 61D: Anlernbar und korrekt steuerbar, aber Statusanzeige häufig fehlerhaft
  [IP-1212] - Eltako TF61J: Alern- & steuerbar aber Statusanzeige und Reaktionen unter iOS/ V5 Plus merkwürdig
  [IP-1213] - Eltako TA 65J: Anlerntext falsch
  [IP-1214] - Eltako TA 65J: Problem wie bei IP-1212
  [IP-1215] - Eltako TA 55 DL: Anlerntext falsch siehe IP-1213
  [IP-1216] - Eltako TA 55 DL: Status wird manchmal nicht automatisch aktualisiert
  [IP-1217] - Eltako TA 65D: Anlerntext falsch siehe IP-1213
  [IP-1218] - Eltako TA 65 D: wie IP-1216
  [IP-1219] - Eltako TA 65L: Anlerntext falsch siehe IP-1213
  [IP-1223] - TF-BHSB nur als BHSB-TF anlernbar, nicht als BHSB-FBH
  [IP-1226] - Eltako: TF-4FT55 in tasks, unexpected problem
  [IP-1228] - V6 mini E Sprachsteuerung Eltako Jalousie Tf61J geht nicht
  [IP-1229] - Szenen mit mehreren TF-Aktor-Aktionen hintereinander: Einzelne Befehle werden teilweise nicht ausgeführt
  [IP-1232] - HM-LC-Sw1-PI-DN-R1 UDP Status Update
  [IP-1236] - Sonos Alarmsound wird über Task nicht abgespielt, obwohl Task ausgelöst wurde
  [IP-1238] - Übersetzung für status_motion fehlt
  [IP-1239] - Alpha nicht über die Cloud bedienbar?
```

``` 
  Story
  [IP-1098] - Taskmanager: Zeitbedingung von - bis    
```

``` 
  Feature
  [IP-552] - Recover Firmware Button
  [IP-671] - Firmwareupdate Retry bei CRC-Error
  [IP-790] - Eltako Dimmer SetRampTime
  [IP-937] - Hilfe-i bei Tasks
  [IP-984] - Systemzeit in den Gw-Infos ausgeben
  [IP-987] - Kalenderansicht
  [IP-990] - WLAN ändern
  [IP-994] - Audio Aktionen im V5+ Taskmanager
  [IP-1002] - Speichern Konfiguration auf Gateway
  [IP-1014] - Sonos über Gateway tunneln
  [IP-1015] - Umstellung der Sonos-Integration
  [IP-1031] - Sonos: IP-Update
  [IP-1034] - Integration Fritzbox
  [IP-1036] - Umstellung Moehlenhoff Alpha auf neue IP-Geräte API
  [IP-1037] - Initialisieren der Alarm-Sounds
  [IP-1041] - Sonos-IP: Integration in den Taskmanager
  [IP-1045] - QR Code Anlernprozess
  [IP-1055] - Gardena Integration
  [IP-1056] - Nuki Integration
  [IP-1060] - Homematic IP Direktes Anlernen über QR-Code
  [IP-1063] - Konfiguration auf Gatewayspeichern: Für V5+ Anpassen
  [IP-1078] - ELTAKO: Anlernprozess "Sonstige Geräte" (ältere blaue Aktoren)
  [IP-1084] - Taskmananger Doku: In App hinzufügen
```

``` 
  Verbesserung
  [IP-624] - Registrierung: Keine Umlaute in der Mail-Bestätigung
  [IP-683] - Task mit Cloud Auslöser: Bei netatmo Regen und Windsensor genaue Werteeinstellung nur ganz schwer möglich.
  [IP-931] - Devices: HMIP-SMO there is no indication for activation of the device
  [IP-985] - UDP Port beim FW-Update
  [IP-999] - FS20 Rollladenaktor integrieren
  [IP-1009] - HMIP Geräte Anlernprozess verbessern
  [IP-1013] - Simu als Hersteller hinzufügen
  [IP-1018] - Tasks/Szenen Dashboard: "+" Task anlegen Button hinzufügen
  [IP-1019] - IR Fernbedienung: Vorlagen Vorschau
  [IP-1020] - IR Vorlage: Tablet PC Vorlage auf Querformat anpassen
  [IP-1027] - IR-Vorlage: "Text zurücksetzen" unter Codefeld
  [IP-1028] - IR-Vorlage: Evtl nicht zugewiesene Tasten ausgegraut darstellen
  [IP-1029] - Taskmanager: Anlegen von mehreren Geräten im Taskmanager
  [IP-1032] - Hilfstext lässt sich nicht mehr schließen (iPad 4)
  [IP-1039] - Cloud Export: Hinweistext, dass Gateway Cloud Access aktiviert werden muss
  [IP-1040] - Wetterforecast: Wettervorschau für die nächsten 5 Tage
  [IP-1044] - Integration Opus Aktoren / Remote Commisioning V6E / V6Emini
  [IP-1054] - Gateway-Konfiguration speichern: Speichern-Button wird sofort ausgeführt ohne Sicherheitsfrage bzgl. Überschreiben der alten Konfiguration
  [IP-1057] - ELTAKO: Überarbeitung der Ansicht zum Anlernen
  [IP-1076] - Anpassungen Konfiguration in Cloud Speichern Ansicht
  [IP-1077] - 868Mhz Ferbedienungen analog zu 433 anlegen
  [IP-1089] - Konfiguration Speichern: auch im Menüpunkt "Einstellungen" zur Verfügung stellen
  [IP-1090] - Konfiguration speichern: Name und Passwortfeld in der Reihenfolge austauschen
  [IP-1095] - Taskmananger: Abstand Elemente
  [IP-1099] - Account Registrierung Passwort Länge Validierung
  [IP-1107] - Gerätetypen Kameras: Öffnen der Ivideon App
  [IP-1108] - Update App Config mit eltako Geräten
  [IP-1109] - FS20: Toggle Schalter: Ändern in An / Aus Buttons
  [IP-1110] - Anlerntexte beim Eltako Anlernprozess ergänzen
  [IP-1115] - Einlernprozess TF61X
  [IP-1119] - TF61L und TF61R Einlernprozess: Gerätestatus und Testbuttons tauschen
  [IP-1121] - Einlernprozess TF61D
  [IP-1122] - eltako TF61J Icon
  [IP-1124] - eltako TF61J Anlernprozess
  [IP-1126] - ELTAKO: Generic Light / Blind listview
  [IP-1134] - Gateway disconnected Icon ist unschön positioniert
  [IP-1146] - Während Firmwareupdate Heartbeat stoppen
  [IP-1150] - ELTAKO: Blind Runtime
  [IP-1151] - UPD Messages von unbekannten Gateways verwerfen
  [IP-1155] - Licht -> eltako -> Sonstige in "Sonstige (Dimmbar)" ändern
  [IP-1157] - Eltako Rauchmelder Anlernvorgang: Text anpassen
  [IP-1195] - Tablet: Bearbeiten Button Raum in Header hinzufügen
  [IP-1196] - Konfiguration speichern: Doppelte Passwortabfrage entfernen
  [IP-1197] - Registrierung: Passwort bestätigen Abfrage entfernt
  [IP-1198] - Hinzufügen von externen Gateways (Fritzbox usw.): Buttonbezeichnung "falsch"
  [IP-1210] - Eltako Aktoren Einstellungen: Button zum Starten des "Learning Mode"
  [IP-1220] - Eltako: TF61J-230v and TF-TA65J step up and down range is not correct and not working
  [IP-1233] - Eltako: TF-TA55DL in tasks, "ON" action is not really ON[100%]
```

### Version 1.07.1

``` 
  Bugs:
  [IP-1033] - Somfy RTS Rollladen falscher Typ "shading"
  [IP-1047] - Anpassungen an V5+ TaskManager Json Format
  [IP-1058] - iOS Pushnachrichten
```

### Version 1.07

``` 
  Feature
  [IP-672] - Sensormodus Warnung beim Geräteanlernen
  [IP-957] - Geräte unter "Favoriten" sollten sortierbar sein
  
  Verbesserung
  [IP-579] - Dashboard: Swipe feature between screens for mobile devices.
  [IP-777] - UDP Port Fehler Benachrichtigung
  [IP-969] - Gateways der V6 Serie müssen gemischt werden können
  [IP-975] - V6 Taskmanager: HmIP und EnOcean Gerätestatus als Bedingungen hinzufügen
  
  Bugs:
  [IP-438] - Fehler beim Abrufen der GPS Koordinaten
  [IP-689] - Opus Fensterkontakt: Statusanzeige: nach mehrmaligem Statuswechsel, ändert sich das Icon nicht mehr
  [IP-752] - iOS App hängt sich immer wieder auf
  [IP-786] - Eltako Aktor Jalousie Laufzeit-Wert beim Anlernen
  [IP-817] - OPUS Wassermelder ECO: Anlerntext falsch
  [IP-870] - Szenen: RGB-Lampen über USB können keine Farben/ Farbtemperatur
  [IP-873] - Fenstersensoren /EnOcean Sensoren liefern unzuverlässige UDP-Messages
  [IP-875] - Openweathermap Task: Auslöser Windgeschwindigkeit mit Prozentslider
  [IP-900] - 2 Gateways: 1 davon "aufgehängt" --> Alarm & Task Fehler
  [IP-905] - Task IR-Auslöser: produziert Fehlermeldung
  [IP-911] - Garage Icons in allen Isonsets aktualisieren
  [IP-919] - GPS auf Gatewayseite - App hängt sich auf
  [IP-924] - Devices: wrong icon for HMIP-SRH
  [IP-930] - Maco Fenstersensor auch unter Türen hinzufügen.
  [IP-936] - HmIP Thermostat zeigt ? bei Ist-Temperatur
  [IP-945] - Intertechno Dimmer: Falsche Anzeigeelemente
  [IP-947] - Devices: HMIP-ASIR causes error in TASKS and SCENES
  [IP-950] - Task: Homematic HM-ES-PMSw1-PI-DN-R1 could not execute the task.
  [IP-955] - Tasks: email action - message field is one line and does not accept space
  [IP-962] - Scenes and Tasks: Unknown error occurred! Selecting device is not working.
  [IP-965] - Devices: HMIP-MOD-TM motor is not actuated
  [IP-970] - GPS-Standort Abruf auf iOS
  [IP-971] - Task: Keine Aktion kann mehr angelegt werden nachdem ein HmIP Rauchmelder angelernt wurde
  [IP-973] - Ruhezustand wird während des Firmware Updates aktiviert
  [IP-974] - Firmware Update: "Fertig" Button bricht Firmware Update ab
  [IP-1008] - App crasht wenn Systemsprache nicht deutsch oder englisch ist
  
```
