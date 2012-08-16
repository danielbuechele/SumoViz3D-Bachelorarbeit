# Webbasierte 3D Postvisualisierung von Fußgängersimulationsergebnissen

1. Einführung und Grundlagen
	1. Entwicklung aktueller Webtechnologien
	2. der HTML5 Standard
		1. canvas-Element
		2. JavaScript und DOM-APIs
	3. Grundlagen der dreidimensionalen Computergrafik
		1. Historie von 3D-Technologie im Web
	4. WebGL
		1. Technik und Funktionsumfang
		2. Verbreitung und Implementierung in den verschiedenen Browsern
		3. die THREE.js Bibliothek
2. Entwicklung von SumoViz3D
	1. Anforderungen und grundlegende Funktionsweise
		1. Ausgangsdaten und deren Aufbereitung
		2. Bestehende SumoViz-Anwendung
		3. Erweiterung von SumoViz
	2. 3D-Darstellung im Browser
		1. Renderer und Kamera
		2. die requestAnimationFrame()-Methode
	3. Navigation innerhalb der Simulation
		1. verschiedene Modelle der Navigation im virtuellen dreidimensionalen Raum
		2. Implementierung der Steuerung bei SumoViz3D
	4. Darstellung der baulichen Geometrie
		1. Wände und Gebäude
			1. Verwendung von Texturen
		2. source, target und andere Felder
		3. Bäume und Pflanzen: Laden von externen 3D-Modellen
	5. Darstellung der Fußgängersimulationsdaten
		1. Anpassung des CouchDB-Datenformats
		2. Einfärbung der Fußgängermodelle
	6. Laufzeitanalyse der Anwendung
		1. Messungen und Ergebnisse mit verschiedenen Datenmengen
		2. Performancesteigernde Maßnahmen
3. Ausblick
	1. Weiterentwicklungsmöglichkeiten für SumoViz3D
	2. weitere Anwendungsbeispiele von WebGL
	3. Zukunft der webbasierten 3D-Technologie
