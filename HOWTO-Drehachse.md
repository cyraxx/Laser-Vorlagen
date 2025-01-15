# HOWTO: Drehachse verwenden

Bei Verwendung der Drehachse wird die Y-Achse deaktiviert und durch die Rotation ersetzt.

Die Einrichtung in der korrekten Reihenfolge ist aber etwas knifflig und manchmal läuft es auch erst nach einem zusätzlichen Reboot.
Mit dieser Anleitung solltest du zum Erfolg kommen.

Die Drehachse wird mit ihren zwei Anschlusskabeln im Inneren des Lasers angeschlossen. Zusätzlich benötigst du noch den Achsenumschalter, das ist an der Seite vom Laser der zweite schwarze Schalter von rechts: unten = normale Y-Achse, oben = Y-Achse ist Rotation.

1. Z-Achse nach unten fahren, um Platz für die Drehachse zu haben
2. Laser ausschalten (Hauptschalter)
3. Drehachse einbauen und anschließen, Achsenumschalter noch unten lassen
4. Laser anschalten (Hauptschalter + Knopf) und Reset abwarten
5. Laser an passende Position fahren (vor allem die Y-Achse)
6. Achsenumschalter nach oben schalten
7. In Lightburn: Menü Laserwerkzeuge > Rotationseinrichtung
   1. "Einstellungen lesen" drücken
   2. Objektdurchmesser (grob) einstellen
   3. "Rotation aktivieren" sowie "Ausgabe auf Rotation spiegeln" anschalten
   4. Test-Button ignorieren, der funktioniert meistens nicht (Bug in Lightburn)
   5. OK drücken
8. Theoretisch fertig! Die Y-Knöpfe am Laser sollten jetzt die Drehachse drehen, eine Rahmenfahrt in Lightburn ebenfalls
9. Falls die Achse nicht dreht oder unrund läuft:
   1. Laser wieder ausschalten
   2. Achsenumschalter wieder nach unten
   3. Ab Schritt 4 noch einmal probieren
