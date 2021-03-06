Braunstorming für das Pflichtenheft
Stand: 13.04.2011

# Zielbestimmung

## Musskriterien

* 3D-Visualisierung der Achterbahn

* 2D-Visualisierung der Beschleunigungen (oder Kräfte), die auf die Insassen des Achterbahnwaagen einwirken.

* Oberfläche für das Einlesen der Achterbahn-Spezfikationen

## Wunschkriterien

* Neben der Achterbahn wird auch die Umgebung mit Gebäuden, Vegetation, Himmel simululiert.

* Berücksichtigung der Bahnreibung

* Berücksichtigung der Luftreibung

Bei einer Berücksichtigung der Luftreibung reduziert sich die Gesamtenergie der simulierten Achterbahnwaagen mit der Zeit, und zwar quadratisch zur Geschwindigkeit und proportional zum Luftwiderstandsbeiwert des Waagens.

* Zusätzlicher Antrieb oder Bremsen

* Zeitraffer

* Aufnahmefunktion

## Abgrenzungskriterien

* Die statische Integrität des Achterbahngerüstes wird nicht simuliert.
* Die Einflüsse der Umgebung auf die Achterbahn (z.B. Wetter) bleiben unberücksichtigt.
* Eine Simulation des Regelbetriebs mit Passagierein- oder -ausstieg findet nicht statt.

# Produkteinsatz

Es handelt sich um eine Einzelplatzanwendung. Die Simulation soll dem technischen Entwickler der Achterbahnen als Visualisierungswerkzeug für die physikalischen Gegebenheiten dienen. Ein Einsatz zu Präsentationszwecken soll möglich sein.

# Produktübersicht

* Einlesen der Achterbahnspezifikation
* Starten/Stoppen der 3D Simulation
* Ein- und Ausblenden der Beschleunigungsdaten
* Ein- und Ausblenden ... 
* Wechseln der Kameraperspektive(?)

# Produktfunktionen

## F100

Geschäftsprozess: Einlesen Achterbahn-Spezifikationsdatei

Ziel: Eine Achterbahnspezifikation wird aus einer Datei geladen in den Arbeitsspeicher geladen.

Vorbedingung: 

Nachbedingung Erfolg:

Nachbedingung Fehlschlag: 

(Ergänzen)

# Produktdaten

Die Anwendung legt keine eigenen Dateien an. Die Spezifikationen für die Achterbahnen werden aus dem Dateisystem geladen.

# Stützstellen

Der Datensatz für eine Achterbahn besteht aus einer geordneten Liste von Stützpunkten. Für jeden Stützpunkt werden Position und Orientierung in einem dreidimensionalen Bezugssystem gespeichert. Die Orientierung erfolgt durch Angabe des jeweilige Giervektors.

Jede Achterbahn wird durch eine geordnete Liste von Stützstellen 

# Produktleistungen

Die Simulation der Achterbahn muss in Echtzeit möglich sein.

Die Energieerhaltung für den simulierten Wagen muss sichergestellt sein. Ohne Reibung und Luftwiderstand soll die Achterbahn unbeschränkt weiterfahren können.

# Qualitätsanforderungen

Bedienbarkeit: sehr gut
Zeitverhalten: sehr gut

# Benutzeroberfläche

(Entwurf Bildschirmaufteilung)
(Entwurf für Datei-Dialogfenster)
(Entwurf für die 2D-Daten)

# Nichtfunktionale Anforderungen

# Technische Produktumgebung

## Software
## Hardware

PC mit OpenGL-fähige Grafikkarte

# Produktschnittstellen

Die Übergabe der Achterbahn-Daten aus dem bestehenden Editor an den Simulator erfolgt als schematisierte XML-Datei. 

(Referenz auf Schema einfügen)

# Glossar

Gierachse: Im dreidimensionalen Raum kann ein lokales Koordinatensystem durch drei Vektoren festgelegt werden. Für die Achterbahn wählt man den Geschwindigkeitsvektor tangential zur Bahn (Rollachse), die Richtung der Querbalken (Nickachse) und deren Kreuzprodukt (Gierachse). Die Gierachse legt fest, welche Richtung von den Passagieren als aufrecht empfunden wird.




