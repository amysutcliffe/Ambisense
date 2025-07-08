# Ambisense
Ambisense Project von Amy Sutcliffe
Erstellt im Sommersemester 2025



**Was ist Ambisense?**

In einer zunehmend rationalisierten und technisierten Welt drohen Körperbewusstsein, Selbstwahrnehmung und zwischenmenschliche Verbundenheit zu verblassen. Besonders in funktionalen Fitnessumgebungen bleibt wenig Raum für emotionale Resonanz oder gemeinsames Erleben. Dieses Projekt setzt an diesem Punkt an: Es verbindet Bewegung, Raum und Klang zu einer interaktiven, klangbasierten Umgebung, die auf die Prinzipien von Ambient Intelligence aufbaut und das körperliche Erleben im Training transformiert.

Ziel ist es, ein System zu gestalten, das das propriozeptive Empfinden, also das Spüren des eigenen Körpers im Raum, subtil unterstützt, ohne zu dominieren oder zu belehren. Dabei wird Klang nicht als Musik im herkömmlichen Sinn genutzt, sondern als räumliches, dramaturgisch strukturiertes Feedbacksystem, das Bewegungen atmosphärisch begleitet. Harmonie entsteht bei korrekter Ausführung, Disharmonie bei Abweichungen, eingebettet in eine narrative Klangreise, die sich an der Struktur der Heldenreise orientiert.

Die Trainingsumgebung reagiert kontextsensitiv auf individuelle und kollektive Bewegungsmuster. Durch subtile klangliche Veränderungen entsteht ein gemeinsames Klangfeld, das soziale Achtsamkeit stärkt und Isolation entgegenwirkt, ohne Einzelpersonen zu markieren. Die Interaktion erfolgt dabei rein körperlich ganz ohne Wearables oder Bildschirme.

Ein funktionaler Prototyp wurde in einem realen Raum mit Sensorik und Raumklangsystem umgesetzt. Erste Tests zeigen, wie Bewegung, Klang und Raum zu einem immersiven Ganzen verschmelzen können, das sowohl individuelle Körperwahrnehmung als auch kollektive Präsenz fördert. Das Projekt versteht sich als Impuls für eine neue Art von Trainingskultur: sinnlich, verbunden, unsichtbar gestaltet.

**Was ist das hier?**

In diesem Repository finden Sie sowohl die Touchdesigner- als auch die Ableton-Datei für die technische Umsertzung des Ambisense-Projekts. Für die Anleitung siehe unten:

**Betriebssanleitung**

Anforderungen: 


Welche Geräte und Schnittstellen werden benötigt?:

•	Computer mit TouchDesigner und Ableton Live
Leistungsfähig genug für Echtzeit-Video- und Audioverarbeitung, TouchDesigner und Ableton Live fähig

•	Kinect-Sensor (Am Besten Kinect v2)
Für Körper- bzw. Gelenk-Tracking 

•	Ableton Link oder TDAbleton (TouchDesigner-Ableton-Schnittstelle)
Für die Kommunikation zwischen TouchDesigner und Ableton

•	Audio Interface oder integrierte Soundkarte
Zum Ausspielen des Sounds  (z. B. über Lautsprecher oder Kopfhörer)

•	Touchdesigner Ambisense Datei 
Befindet sich auf CD und auf Github (Ambisense Final.toe)

•	Ableton Ambisense Datei
Befindet sich auf CD (Ambisense Song Versions.als)

Welches Betriebssystem muss installiert sein?

Betriebssystem:
Windows 10 oder Windows 11 (64-Bit) (Für TouchDesigner und Kinect erforderlich)
Welche sonstige Software in welcher Version muss auf den Geräten installiert sein / Link zur Software

•	TouchDesigner (mind. Version 2022.33910 oder neuer)
Für die visuelle Logik, Sensorverarbeitung und Audioansteuerung
Download: https://derivative.ca/download

•	Ableton Live (mind. Version 11 oder neuer)
Für Musiksteuerung und Audiowiedergabe
Download: https://www.ableton.com/de/trial/

•	TDAbleton
Ermöglicht die Verbindung zwischen TouchDesigner und Ableton Live, kann über das tdAbletonPackage aus dem TouchDesigner-Palette-Browser eingebunden werden
Anleitung: https://docs.derivative.ca/TDAbleton

•	Kinect SDK
Für Kinect v2:
Kinect for Windows SDK 2.0
Download: https://www.microsoft.com/en-us/download/details.aspx?id=44561

(Für eine genaue Anleitung s. TDAbleton-Doku)

Mit welchen Geräten lief das Produkt am besten?
 
Ich habe für die Umsetzung ein MSI-Notebook mit Windows 11 verwendet, und das System lief einwandfrei.

Weitere wichtige Informationen?

•	Gute Lichtverhältnisse sind wichtig (gleichmäßige Beleuchtung ohne starkes Gegenlicht verbessert die Körpererkennung)

•	Ausreichend Bewegungsfreiraum notwendig (Mindestens 2 x 2 Meter freier Platz vor der Kinect-Kamera empfohlen)

•	Die Kinect erkennt Bewegungen aus ihrer eigenen Perspektive

•	Das System ist so eingerichtet, dass es die linke Körperseite aus Sicht der Kinect auswertet, Nutzer sollten also seitlich zur Kamera stehen (linke Seite zur Kamera)

•	Kamera muss so montiert sein, dass das gesamte Körper der Nutzer erkannt werden kann (ca. 1,5–2 m Abstand zur Trainingsfläche)


•	System benötigt kurze Kalibrierungszeit. Bitte beim Start etwa 3–5 Sekunden ruhig stehen, damit die Kinect den Körper korrekt erkennt

•	Die Bewegungsrückmeldung erfolgt rein akustisch über Sound aus Ableton

•	Audio-Wiedergabe sollte laut und klar hörbar sein
Schritte zur Installation und Inbetriebnahme: 

Schritt 1: Software herunterladen und installieren

1.	Laden Sie TouchDesigner herunter

•	Starten Sie TouchDesigner nach der Installation einmal
•	Erstellen oder verwenden Sie einen kostenlosen Account und melden Sie sich an

2.   Laden Sie Ableton Live herunter

•	Installieren Sie Ableton Live
•	Starten Sie Ableton Live nach der Installation 
•	Testen Sie, ob die Audioausgabe funktioniert (z. B. durch Abspielen eines Sounds)

Schritt 2: Verbindung zwischen TouchDesigner und Ableton einrichten (TDAbleton)

1.   Öffnen Sie TouchDesigner
•	Klicken Sie oben rechts auf das Palette-Symbol
•	Suchen Sie in der Palette nach dem Ordner TDAbleton
•	Rechtsklick auf TDAbleton und Install Package wählen
•	Starten Sie Ableton Live neu (Dadurch wird das TDAbleton-Steuerungsskript automatisch installiert)


2. Öffnen Sie in Ableton die Voreinstellungen
•	 Gehen Sie zu Optionen > Voreinstellungen > Link/MIDI
•	 Wählen Sie bei Control Surface den Eintrag TDAbleton
•	 Setzen Sie die Ein- und Ausgänge auf Ihr MIDI-Gerät oder lassen Sie sie auf "None"

Schritt 3: Kinect-Treiber installieren 

•	 Laden Sie den Kinect for Windows SDK 2.0 herunter 
•	 Installieren Sie das SDK auf Ihrem Rechner

Schritt 4: Geräte anschließen und vorbereiten

•	Schließen Sie die Kinect-Kamera per USB an den Computer an
•	Sorgen Sie für ausreichend Platz vor der Kamera

Schritt 5: Programme starten

1.   Starten Sie Ableton Live
•	Öffnen Sie die Ableton Datei (Sie werden einen harmonischen und einen disharmonischen Track sehen)

2. Starten Sie TouchDesigner
•	Öffnen Sie die Touchdesigner Datei 
•	Stellen Sie sicher, dass die TDAbleton-Komponenten geladen sind 
•	Überprüfen Sie anhand von den Trail-CHOPs, ob das Kinect Tracking funktioniert (Ob Hüfte und Knie erkannt werden). Falls nicht, überprüfen Sie die Verbindung in der Kinect SDK Programm
•	Überprüfen Sie außerdem, ob bei der tdAbletonPackage der Ableton-Live-Set erkannt wird (hier soll „1 connected“ zu sehen sein).


Schritt 6: Ableton Live Set starten in Touchdesigner
•	Klicken Sie auf den abletonSong CHOP, dieser befindet sich ganz links im Netzwerkbereich
•	Das Parameter-Fenster sollte sich rechts öffnen (drücken Sie die Taste P oder klicken Sie oben rechts auf „Parameter“, falls das Fenster nicht sichtbar ist)
•	Gehen Sie im Parameterfenster zum Tab „Ableton Song“
•	Klicken Sie bei Play auf das Pulse, um das Set zu starten
•	Jetzt sollte Ableton Live anfangen zu spielen 

Schritt 7: Ins Schwitzen kommen!

1.   Stellen Sie sich vor die Kinect-Kamera
•	Achten Sie darauf, dass Ihr gesamter Körper im Bild ist
•	Um das visuell zu überprüfen: Klicken Sie auf den kinect CHOP ganz links im Netzwerk -> Klicken Sie auf das Stern-Symbol unten rechts am Node („Viewer Active“) ->
Nun erscheint das Kamerabild im Hintergrund der Node und Sie sollten sich vollständig sehen

2.   Richten Sie sich korrekt zur Kamera aus
•	  Die linke Körperseite zeigt zur Kinect-Kamera

3. Beginnen Sie mit Kniebeugen (Squats)
•	Achten Sie auf eine saubere Ausführung
•	Anleitung zur richtigen Technik: https://www.fitnessfirst.de/magazin/training/muskelaufbau/kniebeuge



4. Hören Sie genau hin
•	Klingt der abgespielte Klang eher harmonisch oder dissonant? Dissonanz bedeutet: Ihre Kniebeuge war nicht tief genug (Hüfte über Kniehöhe) 
Harmonie bedeutet: Ihre Kniebeuge war korrekt tief      (Hüfte auf oder unter Kniehöhe)
•	Lassen Sie sich vom Klang leiten. Spüren Sie, wie der Klang Ihre Aufmerksamkeit zurück zu Ihrem Körper im Raum lenkt
•	Korrigieren Sie Ihre Bewegung nicht durch Denken, sondern durch Hören und Spüren

Schritt 8: Abschluss

•	Klicken Sie erneut auf den abletonSong CHOP
•	Das Parameter-Fenster sollte sich rechts öffnen
•	Wechseln Sie zum Tab „Ableton Song“
•	Stoppen Sie das Live-Set indem Sie bei „Stop“ auf Pulse klicken
•	Ableton sollte nun anhalten und der Klang verstummen
