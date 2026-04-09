# CLAUDE.md

# Generátor Hlášek

## Co to dělá
Jednoduchá webová aplikace, která zobrazuje náhodné vtipné české hlášky. Uživatel kliknutím na tlačítko generuje vždy novou hlášku ze seznamu.

## Pro koho
Interní projekt pro testování vývojového workflow a práce s Claude Code.

## Funkce (MVP)
- Zobrazení jedné hlášky
- Tlačítko pro generování další hlášky
- Náhodný výběr ze seznamu hlášek

## Pravidla
- Docker deploy na Dokploy
- Žádné hardcoded klíče — vše v .env
- Udržuj projekt strukturovaný a čitelný
- Český jazyk v celém uživatelském rozhraní (kopí, názvy tlačítek, chyby).
- Po každé změně aktualizuj dokumentaci
- Známé bugy zapiš do KNOWN_ISSUES.md
- Po každé iteraci aktualizuj CHANGELOG.md a README.md s tím, co se změnilo

## Omezení pro tuto fázi (DŮLEŽITÉ)
- Udrž implementaci maximálně jednoduchou (jedna stránka, minima markupu a logiky).
- Použij pouze HTML, CSS a JavaScript (bez frameworků, bez backendu).
- Nepřidávej další technologie (např. React, Vue, Node API) ani přidání dalších stránek.

