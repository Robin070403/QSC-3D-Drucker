# 3D-Drucker im QSC
Hier werden jegliche Informationen, sowie Anleitungen und Backups zu den einzelnen Druckern im QSC festgehalten.

Vor dem Arbeiten mit den Druckern wird daher empfohlen sich diese Dokumente anschauen und sich bewusst zu machen, da es ansonsten zu Komplikationen kommen kann, die es in der Vergangenheit schon mehr als genug gab. **Daher bitte nicht einfach ignorieren!**

1. Erreichbarkeit der Drucker
2. Anmeldedaten
3. Konfiguration via SSH
4. Dokumentation
5. Offene Fragen

## 1 Erreichbarkeit der Drucker
Aktuell haben die Drucker von links nach rechts folgende Namen und sind über folgende Links im lokalen Netz erreichbar:

- ALPHA => [Hier geht's zu Alpha](http://alpha)
- BETA  => [Hier geht's zu Beta](http://beta)
- GAMMA => [Hier geht's zu Gamma](http://gamma)

## 2 Anmeldedaten
Jeder Drucker hat die selben Anmeldedaten. Diese lauten:

**Benutzername:** admin

**Passwort:** 7.zwerge

## 3 Konfiguration via SSH
Falls Zugriff auf die Konsole der Raspberry Pi's benötigt wird, können diese über SSH erreicht werden. Bei jedem ist dieses Protokoll standardmäßig aktiviert.

Folgender Befehl kann je nach Drucker angepasst werden. Auch hier gilt bei der Eingabe des Passworts dasselbe zu nutzen, welches auch für die Anmeldung auf der Weboberfläche genutzt wird:

`ssh root@alpha`

## 4 Dokumenation
Damit sich jeder ohne Einweisung auch selber mit den Druckerns auseinandersetzen kann, habe ich vor längerer Zeit eine umfassende Dokumentation erstellt. Diese sollte bitte bei jeglichen Problemen oder Anpassungen als Unerfahrener zur Hilfe gezogen werden, damit keine Gefahr besteht, dass entweder der Anwender oder der Drucker Schaden nehmen.

## 5 Offene Fragen
Sollte es trotz allem noch Fragen geben, die auch in der Doku nicht beantwortet wurden, so kann man mich natürlich auch erreichen.
