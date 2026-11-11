# Podcast Plus Website

Website für Podcast Plus: Podcast-Studio in Feuerthalen mit drei Paketen (Aufnahme, Produktion, Rundum).

## Aufbau

- `index.html`: die komplette Seite (HTML, CSS und JavaScript in einer Datei)
- `media/hero.mp4`: Hero-Video (36 Sekunden, ohne Ton)
- `media/hero-poster.jpg`: Standbild, bis das Video geladen ist
- `media/studio-1.jpg` bis `studio-6.jpg`: Fotos aus dem Studio
- `fonts/`: Schriften Plus Jakarta Sans und JetBrains Mono (lokal, damit keine Daten an Google gehen; beide unter SIL Open Font License)
- `favicon.svg`: Symbol für den Browser-Tab

## Lokal ansehen

`index.html` im Browser öffnen.

## Formular

Anfragen gehen über [FormSubmit](https://formsubmit.co) direkt an die Adresse in `MAIL` (index.html). Beim allerersten Absenden schickt FormSubmit eine Bestätigungs-Mail an diese Adresse; erst nach dem Klick auf den Link darin kommen Anfragen an. Wird die Adresse geändert, muss sie erneut bestätigt werden. Klappt das Senden nicht, öffnet sich als Ausweichweg das E-Mail-Programm.

## Noch offen

- Impressum und Datenschutzerklärung ergänzen
- Sobald die Domain feststeht: Vorschaubild (`og:image`) als vollständige Adresse eintragen
