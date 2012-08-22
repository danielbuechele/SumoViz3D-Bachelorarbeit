# Webbasierte 3D Postvisualisierung von Fußgängersimulationsergebnissen

1. Einführung und Grundlagen
	1. Moderne Webtechnologien
		1. der HTML5-Standard
			1. DOM und JavaScript APIs 
			2. Das canvas-Element
	2. Grundlagen der dreidimensionalen Computergrafik
		1. Historische Entwicklung der 3D-Technologie im Web
		2. Deklarative und imperative 3D-Darstellung in Browsern
	3. WebGL
		1. Technik und Funktionsumfang
			1. Die WebGL-Rendering-Pipeline
		2. Verbreitung und Implementierung in den verschiedenen Browsern
			1. Vergleich der WebGL-Fähigkeiten ausgewählter Browser
			2. Marktanteile der Webbrowser
			3. Mobile Verfügbarkeit von WebGL
		3. Sicherheit in WebGL
			1. Denial-of-Service-Attacken
			2. Zugriff auf den Frame-Buffer
			3. Cross-Domain-Texturen
		4. WebGL-Bibliotheken
			1. die THREE.js Bibliothek
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
