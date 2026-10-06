# notholt lighting design · Website-Entwurf

Statische Seite, eine Datei (`index.html`), kein Build nötig.

## Inhalt

| Datei | Zweck |
|---|---|
| `index.html` | Die komplette Website (HTML, CSS, JS in einer Datei) |
| `.nojekyll` | Sorgt dafür, dass GitHub Pages die Dateien unverändert ausliefert |
| `img/` | Alle 75 Bilder, kommen aus `notholt-img.zip` |

## Auf GitHub Pages veröffentlichen

1. Auf github.com ein neues Repository anlegen, z. B. `notholt-website`.
2. "uploading an existing file" wählen und den **Inhalt** dieses Ordners hochladen (`index.html`, `.nojekyll`, `README.md`, `img/`). Versteckte Dateien wie `.nojekyll` im Finder mit `Cmd + Shift + .` einblenden.
3. Commit.
4. Settings → Pages → Source: "Deploy from a branch", Branch `main`, Ordner `/ (root)` → Save.
5. Nach ca. 1 Minute ist die Seite unter `https://<benutzername>.github.io/notholt-website/` erreichbar.

## Bilder

Alle Bildpfade zeigen auf `img/`. Die Bilder liegen in `notholt-img.zip` (im Download-Ordner). Entpacken, der Ordner `img/` kommt direkt neben die `index.html`.

## Schrift

Gotham wird genutzt, wenn sie auf dem Rechner installiert ist. Online fällt die Seite auf Montserrat (Google Fonts) zurück. Für den Livegang Gotham als Webfont lizenzieren und einbinden.

## Hinweis

Entwurf, nicht öffentlich verlinken. Bilder und Texte stammen von notholt.de.
