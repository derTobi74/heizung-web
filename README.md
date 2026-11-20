# Heizung – Webapp

Bedienoberfläche für eine Blynk-Heizungssteuerung im Stil der Wand-Displays (Heizung oben/unten, Licht, Außen, Wetter).

- Enthält **keine Zugangsdaten**. Die Blynk-Tokens werden auf jedem Gerät selbst unter ⚙ eingetragen
  (oder per QR-Code übertragen) und bleiben nur im Browser dieses Geräts gespeichert.
- Ohne Tokens läuft die Seite im Demo-Modus.
- Die Seite spricht per Content-Security-Policy nur mit `*.blynk.cloud`, `api.open-meteo.com` und `api.zippopotam.us`.
- `qrcode.js`: QR Code Generator for JavaScript, © Kazuhiko Arase, MIT-Lizenz.
