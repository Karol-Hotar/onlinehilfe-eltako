## Direktverknüpfungen und Verknüpfungen zwischen Geräten erstellen

### Direktverknüpfungen und Verknüpfungen

Bei Geräte-Verknüpfungen unterscheiden wir zwischen Direktverknüpfungen,
bei denen die Geräte ohne Gateway-Beteiligung direkt miteinander
kommunizieren und zwischen Verknüpfungen, bei denen die Gerätesteuerung
über das Gateway läuft. Mit Verknüpfungen oder Direktverknüpfungen
können Geräte untereinander verbunden werden, sodass zum Beispiel mit
einem Wandthermostat direkt ein Heizkörperthermostat gesteuert werden
kann, ohne dass dafür ein Task angelegt werden muss.

### Homematic IP Direktverknüpfungen

Homematic IP Direktverknüpfungen können nur für Homematic IP Geräte
untereinander erstellt werden und hier auch nur für heizungsbasierte
Geräte wie Fenstersensoren und Heizkörperthermostate / Wandthermostate.
Die Geräte kommunizieren nach der Direktverknüpfung autark untereinande
, das Gateway wird für die Kommunikation der Geräte miteinander nicht
benötigt. Direktverknüpfung können direkt nach dem Anlernen erstellt
werden, können aber auch noch zu einem späteren Zeitpunkt in den
Geräteeinstellungen (unter Räume  Bearbeiten Gerät wählen) erneut
verknüpft werden.

#### Direktverknüpfungen zwischen HMIP-Geräten

Diese Funktion steht nur für Homematic IP-Komponenten und aktuell nur
für heizungsbasierte Verknüpfungen zur Verfügung.

Gehen Sie im Hauptmenü auf *Einstellungen* und dort unter *Räume*.
Wählen Sie hier das Gerät, mit welchem Sie eine Direktverknüpfung zu
einem anderen Gerät erstellen möchten.

![](/de/iqontrol_neo/direktverknuepfung3.jpg) Tippen Sie nun auf den
Button *Direktverknüpfungen*.  
  
![](/de/iqontrol_neo/direktverknuepfung1.jpg) Anschließend bekommen Sie
die Komponenten angezeigt, die Sie nun mit diesem Gerät verknüpfen
können. Wählen Sie das entsprechende Gerät durch antippen aus. Es wird
dann automatisch eine Direktverknüpfung angelegt.

### Verknüpfungen

Verknüpfungen mit Wandthermostaten, Heizkörperthermostaten, Dimmern
sowie Dimmertastern und Tastern, die über zwei Buttons verfügen,
möglich, sofern diese von Eltako oder Homematic IP sind. Geräte, die
mit Tastern verknüpft sind, müssen über einen toggl-Befehl verfügen.

Die Geräte kommunizieren nach einer Verknüpfung über das Gateway
miteinander, ohne dass ein Task angelegt werden muss. Verknüpfung können
direkt nach dem Anlernen erstellt werden, können aber auch noch zu einem
späteren Zeitpunkt in den Geräteeinstellungen (unter Räume --\>
Bearbeiten--\> Gerät wählen) erneut verknüpft werden. Dabei muss die
Verknüpfung immer vom Steuergerät (Wandthermostat, Taster) aus mit einem
zu steuernden Gerät verknüpft werden.

![](/de/iqontrol_neo/direktverknuepfung_nach_anlernen2.png)

![](/de/iqontrol_neo/direktverknuepfung_nach_anlernen3.png)

Hinweis: Je nach Verknüpften Geräten, kann die Ansteuerung ein paar
Sekunden benötigen. Warten sie daher bitte einen Moment, wenn das
anzusteuernde Gerät nicht unmittelbar reagiert.
