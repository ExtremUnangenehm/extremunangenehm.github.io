# extremunangenehm.github.io

GitHub-Pages-Site (öffentlich zwingend — Pages auf dem Free-Plan erfordert ein public Repo).
Enthält nur ohnehin öffentliche Inhalte: Rechtstexte und App-Landing-Seiten.

## Struktur

- `index.html` — Übersicht
- `mamaneo/` — MamaNeo-App: Landing, Datenschutzerklärung, Impressum
  (Play-Store-Datenschutz-URL: `https://extremunangenehm.github.io/mamaneo/datenschutz`)
- Künftig: `app-ads.txt` an der Root (AdMob-Verifizierung — muss an der Domain-Wurzel liegen,
  deshalb ist dies das User-Pages-Repo und kein Projekt-Repo)

## Workflow

Kein Gitflow: Pages deployt direkt aus `main`, Inhalte sind statische Rechtstexte
(bewusste Abweichung vom Standard-Repo-Setup). Änderungen klein halten, CI prüft
HTML-Wohlgeformtheit.
