# VerCrypt

- [VerCrypt](#vercrypt)
  - [weiterführende Links](#weiterführende-links)
  - [Herunterladen](#herunterladen)
  - [Installieren](#installieren)
  - [Container(-datei) erstellen (einmalig!)](#container-datei-erstellen-einmalig)
  - [Container(-datei) einbinden](#container-datei-einbinden)
  - [Mit Container(-datei) mit wichtigen Dingen füllen](#mit-container-datei-mit-wichtigen-dingen-füllen)
  - [Container(-datei) trennen](#container-datei-trennen)

VeraCrypt ist eine Software zur Datenverschlüsselung, insbesondere zur
vollständigen oder partiellen Verschlüsselung von Festplatten und
Wechseldatenträgern. VeraCrypt ist Freie Software.

Achtung es gibt anders als bei BitLockler keinen Wiederherstellungsschlüssel.
Wenn Passwort verlorgen oder vergessen, dann sind die Daten futsch.

Vorteil: VeraCrypt ist flexibel einsetzbar unter Windows / Linux / MacOS.

Besonderheit: Container(-datei) als virtuelles Laufwerk!


## weiterführende Links
- https://www.veracrypt.fr/
- https://www.heise.de/select/ct/2020/17/2017718561505911688
- https://www.heise.de/tipps-tricks/VeraCrypt-Alles-verschluesselt-4308944.html

## Herunterladen

![download](img/download.png)

## Installieren

Den Installationsanweisungen folgen!

## Container(-datei) erstellen (einmalig!)

VeraCrypt öffnen und ein Volumen erstellen.

![schritt01](img/schritt01.png)

Eine verschlüsselte Containerdatei erstellen.

![schritt02](img/schritt02.png)

Volume-Typ `Standard VeraCrypt-Volume` auswählen.

![schritt03](img/schritt03.png)

Speicherort für die Container(-datei) angeben.

![schritt04](img/schritt04.png)

![schritt05](img/schritt05.png)

![schritt06](img/schritt06.png)

Verschlüsselungseinstellungen auswählen. **Tipp: Standardvorgaben beibehalten!**
![schritt07](img/schritt07.png)

Volumen-Größe angeben. **Tipp: Zu Anfang erstmal klein beginnen.** Denn je größer desto länger dauert der Erstellungsprozeß!

![schritt08](img/schritt08.png)

Volume-Passwort erstellen.

![schritt09](img/schritt09.png)

Volume-Format einstellen. **Tipp: Vorgaben beibehalten. Und die Maus solange bewegen bis der Balken grün ist.**

![schritt10](img/schritt10.png)

![schritt11](img/schritt11.png)

![schritt12](img/schritt12.png)


## Container(-datei) einbinden

Nachdem die Container(-datei) erstellt wurde. Muss diese explizit geöffnet und eingebunden werden. Erst dann können in dem Container die zu schützenden Dateien abgelegt werden!

![einbinden01](img/einbinden01.png)

Das Passwort eingeben, damit der Container geöffnet und eingebunden werden kann.

![einbinden02](img/einbinden02.png)

![einbinden03](img/einbinden03.png)

Die Container(-datei) sollte nun unter `Laufwerk A:` geöffnet und eingebunden sein.

**Tipp: Das Programm VeraCrypt kann nun beendet werden! Ein Arbeiten mit Laufwerk A: ist trotzdem weiterhin möglich.**

![einbinden04](img/einbinden04.png)

## Mit Container(-datei) mit wichtigen Dingen füllen

![einbinden05](img/einbinden05.png)

![einbinden06](img/einbinden06.png)

**Wichtig: Nach dem Ablegen oder dem Bearbeiten der zu schützenden Dateien muss die Container(-datei) wieder getrennt werden, damit die Daten in dem Container geschützt sind!** 

## Container(-datei) trennen

Das Programm VeraCrypt öffnen.

![trennen01](img/trennen01.png)

Nach dem Trennen sollte die Laufwerksübersicht leer sein!

![trennen02](img/trennen02.png)

Und das `Laufwerk A:`im Datei-Explorer ist nicht mehr vorhanden. Erst dann sind die Dateien im Container sicher verschlüsselt.

![trennen03](img/trennen03.png)

Viel Erfolg beim Verschlüsseln!