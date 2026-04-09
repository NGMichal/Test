# Vtipný Hláškovník

Jednoduchá webová aplikace, která zobrazuje náhodné vtipné české hlášky. Kliknutím na tlačítko „Zlepši mi den" se vygeneruje nová hláška ze seznamu (105 hlášek + 10 speciálních). Každý 10. klik spustí shake animaci a zobrazí vtipně vulgární hlášku.

## Technologie

- HTML, CSS, JavaScript (žádné frameworky)
- Docker (nginx:alpine) pro deploy na Dokploy

## Spuštění lokálně

Otevři `index.html` v prohlížeči.

## Spuštění přes Docker

```bash
docker build -t generator-hlasek .
docker run -p 80:80 generator-hlasek
```

## Struktura projektu

| Soubor | Popis |
|---|---|
| `index.html` | Celá aplikace (HTML + CSS + JS) |
| `Dockerfile` | Docker image pro deploy |
| `.env.example` | Šablona konfiguračních proměnných |
| `CLAUDE.md` | Pravidla pro vývoj s Claude Code |
| `KNOWN_ISSUES.md` | Známé problémy |
| `CHANGELOG.md` | Historie změn |
