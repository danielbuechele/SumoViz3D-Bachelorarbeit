# Webbasierte 3D Postvisualisierung von Fußgängersimulationsergebnissen

[Download PDF](https://github.com/downloads/danielbuechele/SumoViz3D-Bachelorarbeit/thesis.pdf)

Die Arbeit beschreibt die Erweiterung einer bestehenden Webapplikation zur Fußgängerdatenvisualisierung. Mittels HTML5 und WebGL wird eine hardwarebeschleunigte dreidimensionale Darstellung der Simulation implementiert. Damit können in Echtzeit die Simulationsergebnisse betrachtet und modifiziert werden. Es wird der aktuelle Stand der 3D-Grafik im Browser beschrieben und die Nutzbarkeit für Fußgängersimulationen analysiert.

## Web-based 3D Postvisualistion of pedestrian simulation data

This thesis describes enhancements to an existing web-application for pedestrian-data visualization. Using HTML5 and WebGL a hardware-accelerated three-dimensional rendering of the simulation is implemented. Simulation results can be viewed and modified in realtime. The work describes the current state of 3D-graphic in the browser and the opportunities of pedestrian-simulation.

--------

## Inhalt
1. Einleitung
2. Moderne Webtechnologien
	1. Der HTML5-Standard
		1. DOM und JavaScript APIs
		2. Das canvas-Element
3. Dreidimensionale Computergrafik im Browser
	1. Historische Entwicklungder 3D-Technologie im Web
	2. Deklarative und imperative 3D-Darstellung in Browsern
4. WebGL
	1. Technik und Funktionsumfang
		1. Die WebGL-Rendering-Pipeline
	2. Verbreitung und Implementierung in den verschiedenen Browsern
		1. Vergleich der WebGL-Fähigkeiten ausgewählter Browser
		2. Marktanteile der Webbrowser
		3. Mobile Verfügbarkeit von WebGL
	3. Sicherheit in WebGL
		1. Denial-of-Service-Attacken
		2. Zugriff auf den Frame-Buffer
		3. Cross-Domain Texturen
	4. WebGL-Bibliotheken
		1. die THREE.js-Bibliothek
5. Fußgängersimulation und Visualisierung
	1. SumoViz
	2. SumoViz3D
6. Serverkomponenten: CouchDB und node.js
    1. Importieren der Simulationsdaten
        1. Import der Fußgängerdaten
        2. Import der Geometrie
        3. Import der Gruppendaten
    2. Ausgabe der Simulationsdaten
        1. Ausgabe der Fußgängerdaten
        2. Ausgabe der Geometrie- und Gruppendaten
7. Clientseitige Entwicklung von SumoViz3D
    1. Das Interface von SumoViz3D
    2. Darstellung der Geometrie
        1. SkalierungderGeometrie
        2. Darstellung der Grundebene und des Gitternetzes 
        3. Darstellung von Objekten des Typ “obstacle”
        4. Darstellung von Objekten des Typ “wall”
        5. Darstellung anderer Objekte
        6. Veränderung während der Laufzeit
    3. Animationen in JavaScript
    4. Steuerung der Kamera
    5. Darstellung der Fußgängerdaten
        1. Fußgänger als 3D-Objekte
        2. Fußgänger als Partikelsystem 
        3. Einfärbung der Fußgängerobjekte
8. Analyse und Zusammenfassung
    1. Leistungsanalyse von SumoViz3D
        1. Analyse mit bis zu 10000 Fußgängern
    2. Mögliche Erweiterungen für SumoViz3D
    3. Zusammenfassung