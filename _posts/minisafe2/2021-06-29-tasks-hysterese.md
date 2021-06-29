## Taskmanager: Hysterese-Wert

Wenn Sie einen Task auslösen wollen, sobald ein bestimmter Zahlen-Wert
überschritten wird, z.B. sobald der CO2-Wert 800 überschreitet, haben
sie das Problem, dass der task nicht nur bei 800 ausgelöst wird, sondern
auch bei 801, 802, 803 usw. Ihr Task wird also ständig ausgeführt,
solange der Wert ansteigt.

Die Lösung bietet hier der sogenannte Hysterese-Wert. Dieser legt fest,
dass der Task erst ein weiteres Mal ausgeführt wird, wenn der angegebene
Hysterese-Wert unterschritten wird. Im Beispiel mit dem C02 wert von 800
bedeutet das, dass der Task beim ersten überschreiten der 800-Marke
einmalig ausgelöst und dann erst wieder, nachdem der Wert unter 700
(eingestellter Hysterese-Wert) gefallen ist.

![](/de/iqontrol_neo/hysterese.png)

Bei allen Geräten, bei denen auf Werte hin ausgelöst wird, wird daher im
Bereich Tasks immer eine Hysterese angeboten. Diese setzt sich
automatisch, sobald Sie einen Wert als Auslöser angeben auf den
niedrigst möglichen Hysteresewert. Sie können die Hysterese beliebig
anpassen.

Bitte beachten Sie, dass Sie der Hysterese-Wert immer entgegengesetzt zu
dem eingestellten Wert angelegt werden muss. Möchten Sie also auf einen
Wert größer/gleich 800 auslösen, muss die Hysterese kleiner/gleich 800
oder niedriger sein. In den IQONTROL NEO Tasks können Sie die Werte
nicht entgegen dieser Logik anpassen.
