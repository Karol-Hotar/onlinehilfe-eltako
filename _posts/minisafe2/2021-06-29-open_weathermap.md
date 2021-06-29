## OpenWeathermap als Auslöser

### OpenWeathermap als Gerät integrieren

Um OpenWeathermap als Auslöser im Taskmanager verwenden zu können,
müssen Sie den Online-Dienst zunächst als Cloud-Verbindung einrichten.

-----

### Eine Cloudverbindung zu Open Weathermap einrichten

![](/de/iqontrol_neo/iqneo_cloudaccess.jpg) Zunächst müssen Sie die den
Cloud Access auf Ihrem AIO Gateway aktivieren. Dazu gehen Sie unter
*Einstellungen*--\> *Gateway* auf Ihr AIO Gateway und aktivieren den
Cloud Access.  
  
  
  
![](/de/iqontrol_neo/iqneo_cloudverbindung.jpg) Um Geräte über die Cloud
zu verbinden, müssen Sie im nächsten Schritt die Cloud-Verbindung zu dem
jeweilgen Gerät herstellen. Dafür werden die kostenpflichtigen mediola
Cloud-Services benötigt. Diese können für 12 oder 24 Monate erworben
werden. Unter // Account //--\> *Cloud Services* können Sie diese
entweder direkt in der App erwerben oder Ihren anderweitig erworbenen
Freischaltcode für die Cloud-Services eingeben. Haben Sie die
Cloud-Services erworben, können Sie hier einsehen, wie lange Ihre Cloud
Services noch gültig sind.

Haben Sie gültige Cloud Services, können Sie anschließend die
Cloud-Verbindung einrichten. Dafür tippen Sie unter *Account* auf *Cloud
Verbindungen*.

![](/de/iqontrol_neo/iqneo_cloudverbindung_anlegen.jpg) Legen Sie nun
eine neue Cloud-Verbindung an, indem Sie auf das Plus-Symbol tippen und
anschließend OpenWeathermap aus den verfügbaren Cloud-Verbindungen
wählen.  
  
  
![](/de/iqontrol_neo/iqneo_weather_auth1.jpg) Anschließend müssen Sie
bei OpenWeathermap einen API-Schlüssel beantragen und diesen im nächsten
Schritt eingeben. Bitte beachten Sie, dass das freischalten des
API-Schlüssel von Seiten OpenWeathermaps einen Moment dauern kann.  
  
  
![](/de/iqontrol_neo/iqneo_standort.jpg) Legen Sie anschließend Ihren
Standort fest, für den Sie Wetterdaten empfangen möchten.

Im Anschluss können Sie OpenWeathermap als Gerät integrieren.

  
  
  
![](/de/iqontrol_neo/iqneo_weather_geraet2.png) Wählen Sie dazu unter
*Gerät hinzufügen* den Gerätetyp *Wetterstation*.  
  
  
![](/de/iqontrol_neo/iqneo_statndort_waehlen.jpg) Tippen Sie im
Anschluss auf *OpenWeathermap* und wählen dann den angelegten Standort.
Dieser Standort wird nun als Gerät importiert und kann als Auslöser in
Tasks gewählt werden.

-----

## OpenWeathermap in einen Task einfügen

![](/de/iqontrol_neo/iqneo_task_weathermap.jpg) Haben Sie OpenWeathermap
als Gerät hinzugefügt, kann im Taskmanager der gewählte Standort unter
*Gerätestatus* im **WENN-Auslöser** gewählt werden. Als mögliche
Auslöser stehen hier *Temperatur*, *Luftfeuchtigkeit*,
*Windgeschwindigkeit* und *Windrichtung* zur Verfügung.
