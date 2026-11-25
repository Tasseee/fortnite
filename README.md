# Island Rush

Ein kleines 3D-Browser-Spiel auf einer eigenen Insel – gebaut mit Three.js.

## Lokal starten
Öffne `index.html` über einen lokalen Webserver. Zum Beispiel mit der VS-Code-Erweiterung **Live Server**.

## Online mit GitHub Pages veröffentlichen
1. Öffne die Repository-Einstellungen (**Settings**).
2. Gehe zu **Pages**.
3. Unter **Build and deployment** wähle **Deploy from a branch**.
4. Wähle den Branch `main` und den Ordner `/(root)`, dann **Save**.
5. Nach dem Veröffentlichen zeigt GitHub Pages dort die Spiel-URL an.

## Steuerung
- **WASD**: bewegen
- **Maus**: Kamera drehen
- **Linksklick**: Energie-Puls
- **Leertaste**: springen
- **E**: Loot-Kiste öffnen
- **C**: im Busch verstecken / Versteck verlassen
- **B**: Bau-Modus
- **1 / 2 / 3**: Wand / Rampe / Plattform auswählen
- **Linksklick im Bau-Modus**: Bauteil platzieren
- **ESC**: Maus freigeben

Das Spiel lädt Three.js über ein CDN und benötigt daher beim Start eine Internetverbindung.
