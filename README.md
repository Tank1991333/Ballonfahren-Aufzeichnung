Ballonflugbuch Web-App
Eine statische, installierbare Web-App für GitHub Pages oder Vercel. Kein Build-Prozess nötig.
Funktionen
Live-GPS mit Geschwindigkeit, Höhe, Richtung und Genauigkeit
Start/Stopp der Aufzeichnung, Strecke, Dauer, Steig- und Sinkrate
Karte mit Live-Position und Flugroute
Höhenprofil
Landungs- und freie Markierungen
Lokales Flugbuch mit Statistik
GPX- und JSON-Export
Wetter am Standort über Open-Meteo
PWA-Manifest und Offline-Grundgerüst
Responsive Bedienung für Smartphone, Tablet und Desktop
GitHub Pages
Alle Dateien in das Hauptverzeichnis eines neuen GitHub-Repositories laden.
In GitHub unter Settings → Pages als Quelle Deploy from a branch auswählen.
Branch main und Ordner / (root) wählen.
GitHub zeigt danach die öffentliche HTTPS-Adresse an.
Vercel
Repository importieren. Framework Preset Other, Build Command leer lassen, Output Directory `.` verwenden.
Wichtig
GPS im Browser funktioniert nur über HTTPS oder lokal über `localhost`. Auf dem Smartphone muss die Standortfreigabe erlaubt werden. Kartendaten und Wetter benötigen Internet. Flugdaten werden nur im Browser per Local Storage gespeichert.
Diese App ist kein zertifiziertes Navigationsinstrument und ersetzt keine vorgeschriebenen Instrumente oder Verfahren.
