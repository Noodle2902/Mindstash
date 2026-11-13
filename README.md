# Mindstash – persönlicher PWA-MVP

Dies ist der erste lauffähige Prototyp von Mindstash. Er ist für eine private Nutzung auf dem iPhone ausgelegt.

## Enthalten
- Mobile-first Oberfläche mit Home, Discover, Library, Journal und Profil
- Ein Beispiel-Wissensimpuls
- Favoriten, Lernstatus, Tagesaufgabe und Reflexion
- Speicherung lokal im Browser (`localStorage`)
- PWA-Manifest und Service Worker für Offline-Caching

## Lokal testen
Öffne `index.html` im Browser. Für Service Worker und Installation muss die App über HTTPS oder `localhost` bereitgestellt werden.

## Kostenlos auf GitHub Pages veröffentlichen
1. Erstelle ein kostenloses GitHub-Konto und ein neues öffentliches Repository namens `mindstash`.
2. Lade alle Dateien aus diesem Ordner in das Repository hoch.
3. Öffne **Settings → Pages**.
4. Wähle **Deploy from a branch**, Branch `main`, Ordner `/ (root)`, dann Save.
5. Nach der Veröffentlichung öffne die angezeigte HTTPS-Adresse auf deinem iPhone in Safari.
6. Tippe auf **Teilen → Zum Home-Bildschirm**.

## Wichtige Grenzen dieses MVP
- Daten bleiben im Browser auf diesem Gerät. Browserdaten löschen kann gespeicherte Einträge entfernen.
- Es gibt noch keine Anmeldung, Cloud-Synchronisierung oder automatische KI-Generierung.
- Push-Mitteilungen und native iOS-Funktionen sind noch nicht implementiert.
- Inhalte sind ein Startbestand und müssen für den produktiven Einsatz redaktionell geprüft und mit Quellen ergänzt werden.

## Nächste Entwicklungsschritte
1. Inhalte als strukturierte Daten verwalten und vollständige Impulsbibliothek aufbauen.
2. Feedback (Mehr davon / Bereits bekannt / Nicht interessant) speichern.
3. Quiz und Wiederholungslogik ergänzen.
4. Export und Backup der lokalen Daten einbauen.
5. Erst danach optional KI-API und Synchronisierung ergänzen.


## Design-Update 0.2
Das visuelle Update ergänzt die Premium-Farbwelt aus Waldgrün, Cremeweiß und Gold sowie verfeinerte Karten, Navigation, Typografie und Bedienelemente. Beim erneuten Aufruf wird durch den aktualisierten Cache-Namen die neue Version geladen.
\n\nVersion 0.5: 16 Wissensimpulse, vier strukturierte Lernpfade, Aufgaben pro Einheit und dynamische Quellenangaben.\n\nVersion 0.6: Wissenscheck pro Lerneinheit mit Antwortauswertung und lokal gespeichertem Ergebnis.\n