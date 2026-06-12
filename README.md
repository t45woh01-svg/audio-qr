# Audio-QR

QR-Codes, die beim Scannen sofort eine Audiodatei abspielen — kostenlos gehostet über GitHub Pages.

## So funktioniert es

Du brauchst nur **eine** Player-Datei (`play.html`). Welche Audiodatei abgespielt wird,
steht in der URL:

```
https://DEINNAME.github.io/audio-qr/play.html?a=audio1.mp3
```

Pro QR-Code änderst du nur den Teil hinter `?a=`. Du musst also keine HTML-Datei
pro Audio anlegen — nur die MP3s hochladen.

## Einrichtung (einmalig)

1. **Repository anlegen:** Auf GitHub ein neues, *öffentliches* Repo erstellen,
   z. B. `audio-qr`.
2. **Dateien hochladen:** Diese Dateien (`play.html`, `index.html`) und deine
   MP3-Dateien per Drag & Drop in das Repo ziehen und committen.
3. **GitHub Pages aktivieren:** Im Repo auf **Settings → Pages**.
   Unter „Branch" `main` wählen, Ordner `/ (root)`, **Save**.
   Nach ein bis zwei Minuten ist die Seite live.

## Audio hinzufügen

1. MP3 ins Repo hochladen, z. B. `glocke.mp3`.
2. Die zugehörige URL lautet dann:
   `https://DEINNAME.github.io/audio-qr/play.html?a=glocke.mp3`
3. Diese URL in einen QR-Code umwandeln (siehe unten).

> Liegt eine Datei in einem Unterordner, den Pfad mit angeben:
> `?a=sounds/glocke.mp3`

## QR-Code erzeugen

Die fertige URL in einen beliebigen kostenlosen QR-Generator einfügen
(im Web nach „QR Code Generator" suchen), als PNG herunterladen und ausdrucken.

## Tipps

- **Format:** MP3 verwenden — wird auf allen Geräten unterstützt.
- **Autoplay:** Handys blockieren automatischen Ton. Die Seite versucht Autoplay
  und zeigt sonst einen großen Play-Button (ein Tipp genügt). Das ist technisch
  nicht umgehbar und bei allen Lösungen gleich.
- **Dateigröße:** Kleine Dateien laden über Mobilfunk schneller. Für kurze Clips
  reicht 128 kbit/s locker.
- **Test:** `audio1.mp3` ist ein kurzer Beispielton zum Ausprobieren.
