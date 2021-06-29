---
title: Anwendungsbeispiel
author: Eltako Gmbh
categories: [MiniSafe2, Alarm]
tags: [Alarm]
math: true
mermaid: true
image:
src:
---


#### Anwendungsbeispiel

Eine dreiköpfige Familie nutzt den Alarm als Einbruchsschutz ihres
Einfamilienhaus. Dazu ist vorhanden:

Alle Fenster sowie die Haustür sind mit Fenstersensoren ausgestattet.
Jedes Familienmitglied hat eine Handfernbedienung zum
Aktivieren/Deaktivieren des Alarms. Als akustischer Signalgeber ist ein
Sonos Play vorhanden.

#### Vorbereitungen

Alle Familienmitglieder müssen die App IQONTROL NEO installiert und die
Konfiguration des Hauses geladen haben. In den Einstellungen jedes
Mobilgerätes wird das jeweilige Gerät als Push Gerät gespeichert, damit
es Push Nachrichten empfangen kann.

Ein Sonos Play ist im System angelegt und kann über das Gateway
gesteuert werden.

Handsender und Fenstersensoren sind am Gateway angelernt.

#### Alarm Nachrichten anlegen

Jedes Familienmitgleid soll eine Push Nachricht bekommen, wenn der Alarm
aktiviert bzw. deaktiviert oder Alarm ausgelöst wurde.

Folgende Nachrichten müssen angelegt werden:

1.  Für jedes Push Gerät eine Nachricht mit dem Text: Alarm wurde
    aktiviert
2.  Für jedes Push Gerät eine Nachricht mit dem Text: Alarm wurde
    deaktiviert
3.  Für jedes Push Gerät eine Nachricht mit dem Text: Alarm wurde
    ausgelöst

#### Alarmkonfiguration

Alle Fenster/Türsensoren des Hauses werden im Hüllschutz in der
Alarmkonfiguration als Auslöser angelegt.

Als Aktionen werden angelegt:

1.  Typ: Audio: Alarm Sound abspielen mit dem Sound und einer von 5
    auswählbaren Alarm MP3s
2.  Push Nachrichten "Alarm ausgelöst" werden für jedes Gerät eingefügt.

Event Aktionen "Bei Aktivierung":

1.  Push Nachrichten "Alarm aktiviert" werden für jedes Gerät eingefügt.
2.  Gateway LED Farbe auf rot (Alarm ist aktiv)

Event Aktionen "Bei Deaktivierung":

1.  Push Nachrichten "Alarm deaktiviert" werden für jedes Gerät
    eingefügt.
2.  Gateway LED Farbe auf grün (Alarm ist inaktiv)

#### Haustür definieren

Im Hüllschutz wird der Haustür-Sensor als Haustür definiert und eine
Verzögerung von 45 Sekunden und der Sound alert1.mp3 mit einer
Spieldauer von 3 Sekunden eingestellt.

#### Alarmkeys anlegen

Im Hüllschutz werden die Alarmkeys angelegt mit den Einstellungen:

  - Aktivieren: Taste 1 kurz
  - Deaktivieren: Taste 2 kurz

#### Akustische Bestätigung

Als akustische Bestätigung wird festgelegt:

  - Geräte: Sonos Play
  - Aktivieren: activation1.mp3
  - Deaktivieren: deactivation1.mp3
  - Fehler: error1.mp3

#### Szenario:

  - Jedes Familienmitglied kann über die Handfernbedienung den Alarm
    aktivieren/deaktivieren.
  - Wird der Alarm aktiviert bekommt jedes Familienmitglied eine Push
    Nachricht, dass der Alarm aktiv ist. Dasselbe passiert bei
    Deaktivierung. 
  - Bei Aktivierung/Deaktivierung wird ein akustisches Signal
    abgespielt.
  - Wird einmal aus Versehen die Tür mit aktiviertem Alarm geöffnet,
    bleiben 45 Sekunden Zeit, das Handy herauszuholen und den Alarm zu
    deaktivieren, bevor der Alarm ausgelöst wird.
  - Wird der Alarm mit einem Alarm Key aktiviert und ein Fenster ist
    geöffnet, ertönt der festgelegte Fehlerton. Welches Fenster
    geöffnet ist, kann über die App eingesehen werden.
  - Anhand der LED Farbe am Gateway ist zu erkennen, ob der Alarm aktiv
    oder inaktiv ist.
  - Wird der Alarm ausgelöst, wird ein Alarmton abgespielt und alle
    Familienmitglieder bekommen eine Push Nachricht.
