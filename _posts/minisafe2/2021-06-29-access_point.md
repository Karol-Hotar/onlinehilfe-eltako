---
title: Access Point
author: Eltako Gmbh
categories: [MiniSafe2, Access Point]
tags: [Access Point]
math: true
mermaid: true
image:
src: 
---

## Den Homematic IP Access Point und Homematic IP Geräte integrieren

### Den Access Point anbinden

1\. Zunächst müssen Sie den Access Point über die Cloud verbinden. Im
ersten Schritt, müssen Sie dafür die Cloud-Anbindung lizensieren. Dies
geschieht über einen Freischaltcode für die mediola Cloud Services. Dazu
gehen Sie unter zunächst *Account –\> Cloud Dienste* und geben Ihren
Freischaltcode für die mediola Cloud Services ein.

2\. Wenn Sie IQONTROL NEO mit einem AIO Gateway verwenden, müssen Sie
unter Einstellung-\>Gateway den Cloud Access über Ihr mediola Gateway
aktivieren.Wenn Sie IP QONTROL verwenden entfällt dieser Schritt.

3\. Im nächsten Schritt verbinden Sie nun den Access Point über die
Cloud. Dafür gehen Sie unter Account-\> Cloud Verbindungen und fügen
über das Plus-Symbol eine neue Cloud-Verbindung hinzu. Wählen Sie hier
die Homematic IP-Cloud und folgen den Anweisungen zum Verbinden des
Access Points. Kehren Sie nach erfolgreichem Verbinden zum Hauptmenü
zurück.

#### Die Geräte und Gruppen vom Access Point importieren

Sie haben den Access Point verknüpft. Nun müssen Sie die Geräte des
Access Points über diese Verbindung noch importieren. Da in IQONTROL NEO
/ IP QONTROL Geräte immer in entsprechenden Räumen angelegt werden
müssen, legen Sie zunächst unter *Raum hinzufügen* alle Ihre Räume an,
die Sie auch im Access Point angelegt haben. Anschließen wählen Sie
*Gerät hinzufügen*, wählen den Raum, in den das Gerät hinzugefügt
werden soll und anschließend den Gerätetyp z.B. Licht. Wählen Sie als
Hersteller Homematic IP Cloud. Nun bekommen Sie eine Reihe von Geräten
und Gerätegruppen angezeigt, welche Sie anklicken und in der App
speichern und so anlegen können.

![](/de/iqontrol_neo/ipq-hmip-gruppen1.png)

Die **Einzelgeräte** ermöglichen die genaue Steuerung bzw. Statusanzeige
des entsprechenden Gerätes. Mit einer Ausnahme: Für
Heizkörperthermostate können nur Einzelstatus ausgegeben werden. Eine
Steuerung der Heizkörperthermostate erfolgt über die Gerätegruppe und
betrifft dann immer alle Heizkörper eines Raumes.  
  
In den **Geräte-Gruppen** pro Raum können mehrere Einzel-Komponenten
innerhalb eines Raumes als Gerät-Gruppe zusammengefasst importiert
werden und dann als gesamte Gruppe gesteuert werden. Beispiel:
Schlafzimmer (heater) → steuert alle Geräte des Types Heizung im Raum
Schlafzimmer gleichzeitig. Ob es sich bei dem Importierten Gerät um ein
Einzelgerät oder eine Gerätegruppe handelt, erkennen Sie am Aufbau des
Namens. ![](/de/iqontrol_neo/ipq-hmip-gruppen2.png)

Ein Einzelgerät besteht aus dem Namen, den Sie diesem Gerät in der
originalen Homeatic IP App gegeben haben und dem in der originalen
Homematic IP App zugeordneten Raum. In unserem Bespiel also „Dimmer
Decke - Wohnzimmer“. Eine Gruppe trägt den Namen des Raumes, indem sich
die Gruppe befindet und dahinter in Klammern die Bezeichnung des
Gerätetyps. Dahinter erneut der zugeordnete Raum mit der Kennzeichnung
\[Gruppe\] . In unserem Beispiel also „Küche (Dimmer) – Küche
\[Gruppe\]“. Wir empfehlen die Namen der Geräte und Gruppen nach dem
Import so umzubenennen, dass diese für Sie schlüssig erkennbar sind.
Unter den Räumen können Sie Ihre Geräte umbenennen.

#### Ihre Geräte steuern

Ihre Geräte können Sie anschließend über *Räume* (alle Geräte und
Gruppen sortiert nach Raum) oder über *Geräte* (alle Geräte und Gruppen
sortiert nach Gerätetyp) steuern. Um Gerätestatus abzufragen, muss die
Seite in IQONTROL NEO manuell aktualisiert werden. Swipen Sie dafür mit
einem Finger von oben nach unten.

#### Das Gerät „Home“ und die Access Point-Räume

Unter „Sonstige“ können Sie ein Gerät mit Namen „Home“ importieren. Hier
finden Sie Alarmeinstellungen und Wetterdetails Ihres Access Points.

Zusätzlich finden Sie unter „Sonstige“ noch die Räume Ihres Access
Points. In diesen werden gesammelte Warn-Status (z.B. Batteriestatus)
aller Geräte dieses Raumes angezeigt, sofern eine Warnung vorliegt.
