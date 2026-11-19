# Vivi Hatchimal Control 💜🐣

Eigenständiges Webprojekt zur späteren Steuerung eines umgebauten Hatchimals. Die bestehende Vivi-Website wird nicht verändert.

## Stand V0.1
- Chatoberfläche mit lokal gespeicherten Nachrichten
- Demo-Modus und optionale Puter-Online-KI (Internet, ggf. Anmeldung)
- Handy-Mikrofon über Browser-Spracherkennung, soweit unterstützt
- Vorbereitete WebSocket-Schnittstelle für einen späteren Mikrocontroller
- Vorbereitete Steuerelemente für Flügel, Augen und Bewegung
- **Keine Sprachausgabe über das Smartphone**; Hatchimal-Audio ist noch nicht implementiert

## Wichtige Grenzen
Es ist **keine vollständige Kopie** der alten Vivi-KI. Die frühere lokale Modell- und Stimmtechnik sowie das bestehende Gedächtnis wurden nicht übernommen. Das originale Hatchimal unterstützt WebSocket oder frei übertragbare Sprache nicht automatisch. Die zweite Mikrofonquelle und die tatsächliche Lautsprecherausgabe benötigen erst passende, sicher geprüfte Hardware und Firmware. Es werden keine Motoren gesteuert, solange kein Controller verbunden ist. Eine Controller-Verbindung allein bestätigt keine sichere Motorhardware.

## Website
GitHub Pages: Repository → Settings → Pages → Deploy from a branch → main / (root) → Save. Danach ist die Website unter `https://gromaj2007-stack.github.io/vivi-hatchimal-control/` erreichbar, sofern Pages erfolgreich aktiviert wurde.

Die Webseite enthält keine geheimen API-Schlüssel. Kein Zugangscode darf in öffentliches Frontend-JavaScript eingetragen werden.
