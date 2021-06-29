---
title: Inbetriebnahme der V6-Serie
author: Eltako Gmbh
categories: [AIO V6 Gateway]
tags: [AIO V6 Gateway]
math: true
mermaid: true
image:
src:
---

#### Inbetriebnahme der V6-Serie

#### Voraussetzungen

  - AIO GATEWAY V6, V6 E, V6 mini oder V6 mini E
  - AIO CREATOR NEO 2.6.2 oder höher
  - ConfigTool NEO 1.9.0 oder höher

Die aktuelle Version des Gateway ConfigTool NEO kann unter
[mediola.com](https://www.mediola.com/service#downloads?type=software&product=configtoolneo)
für macOS, Windows und Linux heruntergeladen werden.

Auf der Startseite des ConfigTool NEO erhält man eine Übersicht aller
Gateways im Netzwerk. Außerdem kann man hier ein Gateway hinzufügen.  

-----

#### Einrichtung des Gateways

![](/de/v6/config_v6_inbetriebnahme.png)

Um ein AIO GATEWAY V6 über das ConfigTool NEO einzurichten, klicken Sie
auf der Startseite des ConfigTools auf "Gateway hinzufügen".

![](/de/v6/configv6_strom.png)

Schließen Sie nun das Gateway an den Strom an. Ist das AIO GATEWAY V6
mit dem Strom verbunden, klicken Sie auf "Weiter".

![](/de/v6/configv6-connect-wifi.png)

Als nächsten Schritt verbinden Sie den Computer mit dem WLAN des
Gateways (nicht mit Ihrem Heim-WLAN). Gehen Sie dazu in die
WLAN-Einstellungen Ihres Computers und dort zur Liste der verfügbaren
WLANs. Verbinden Sie sich mit dem WLAN mit Namen „AIOGATEWAY–XXXXXX“
(anstelle XXXXXX werden die letzten Ziffern der MAC-Adresse Ihres
Gateways angezeigt). Wenn Ihr Computer mit dem Gateway-WLAN verbunden
ist, klicken Sie bitte auf „Gateway suchen“. Das Programm sucht jetzt
Ihr Gateway.

![](/de/v6/configv6-wlan.png)

Wurde das Gateway gefunden, erscheint unter dem "Gateway suchen"-Button
eine entsprechende Meldung.  
Mit einem Klick auf "Weiter" öffnet sich eine Seite, auf der Sie nun Ihr
Heim-WLAN auswählen, über welches Ihr Gateway schließlich erreichbar
bzw. steuerbar sein soll und geben das passende WLAN-Passwort ein.

![](/de/v6/configv6wlan2.png)

Mit einem Klick auf "Gateway verbinden" versucht sich das Gateway mit
dem ausgewählten WLAN zu verbinden.

![](/de/v6/configv6-fertig.png)

Mit einem Klick auf "Gateway verbinden" versucht sich das Gateway mit
dem ausgewählten WLAN zu verbinden. Während des Verbindungsaufbaus
blinkt die LED des Gateways orange. Ist eine Verbindung hergestellt,
hört die LED auf zu blinken und ist dann aus.  
Das Gateway ist nun zum Einsatz bereit.

<span class="underline">Hinweis</span>: Sollte die Verbindung
fehlschlagen, drücken Sie bitte die Reset-Taste auf der Rückseite des
Gateways und halten sie so lange gedrückt, bis die LED grün leuchtet.
Wenn Sie die Reset-Taste bei grün leuchtender LED loslassen, werden die
WLAN-Einstellungen zurückgesetzt. Wiederholen Sie bitte jetzt die
Prozedur beginnend bei Schritt 2.  
Mit einem Klick auf "Einstellungen öffnen" gelangt man auf die
Einstellungsseite.  
\*\* Hinweis: \*\* Diese kann auch aufgerufen werden, wenn das Gateway
auf der Startseite angeklickt wird.

Hier stehen sechs Menüpunkte zur Auswahl:

  - Allgemein
  - Netzwerk
  - Cloudzugriff
  - Erweitert
  - System
  - Debug

Um in den verschiedenen Tabs Änderungen vornehmen zu können, klicken Sie
immer zuerst auf "Formulare freischalten".  
Haben Sie für Ihr Gateway ein Passwort gesetzt, müssen Sie unter
"Formulare freischalten" zunächst Ihr Passwort eingeben, bevor Sie
Änderungen vornehmen können.

-----

\*\* Allgemein\*\*

![](/de/v6/configv6-allgemein.png)

Hier kann man den Namen des Gateways, den Standort und die Zeitzone
ändern, sowie die Firmware aktualisieren oder eine Firmware-Datei
direkt aufspielen.  
Außerdem erhält man dort Auskunft über die aktuelle Firmwareversion des
Gateways, welche dort manuell aktualisiert werden kann.

-----

\*\* Netzwerk \*\*

![](/de/v6/configv6-netzwerke.png)

Unter Netzwerk kann man die Netzwerkeinstellungen ansehen oder ändern.  
Es wird empfohlen hier nur Änderungen vorzunehmen, wenn man über
entsprechendes Fachwissen auf diesem Gebiet verfügt.  
[→ IP-Adresse ändern](/de/v6/ip_ändern)

-----

\*\* Cloudzugriff \*\*

![](/de/v6/configv6_cloud.png)

Unter Cloudzugriff kann der Cloudzugriff aktiviert, deaktiviert oder
getestet werden.  
[→ Cloudzugriff einrichten](/de/v6/cloudzugriff)

-----

\*\* Erweitert \*\*

![](/de/v6/configv6-erweitert.png)

Unter Erweitert kann man das Benutzer-Passwort des Gateways eintragen.  
Des Weiteren kann dort die Farbe der LED des Gateways individuell
gewählt werden und ein Gateway-Backup sowohl erstellt, als auch
eingespielt werden.

-----

\*\* System \*\*

![](/de/v6/configv6_system.png)

Unter System kann das Gateway per Befehl neu gestartet werden.

-----

\*\* Debug \*\*

![](/de/v6/config-v6-debug.png)

Unter Debug können Sie die Debug-Daten des Gateways abfragen.
Verschiedene Informationen über das Gateway können über den Reiter
"Debug" abgerufen werden. Dabei handelt es sich um Systeminformationen,
sowie Taskeinstellungen und Statusmeldugen. Diese Informationen werden
gelegentlich in Kontakt mit unserem Support benötigt.

-----

\*\*Das Gateway in den AIO CREATOR NEO integrieren \*\*

Wie Sie AIO GATEWAYs in den AIO CREATOR NEO integrieren, erfahren Sie im
Bereich [AIO Gateway
integrieren](/de/creator/ui-menu-devicemanager-aiogateway) der
umfassenden [Dokumentation zum AIO CREATOR NEO](/de/creator/start).

/\*![index](index)\*/

![tag\> "GATEWAY" "ConfigTool" "Inbetriebnahme Gateway"
"V6"](tag\>%20"GATEWAY"%20"ConfigTool"%20"Inbetriebnahme%20Gateway"%20"V6")
