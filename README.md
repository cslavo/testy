# Testy

Zbierka testovacích HTML súborov pre rôzne účely. Projekt slúži na zhromažďovanie HTML súborov, ktoré sa publikujú priamo z repozitára.

## Štruktúra

```
testy/
├── index.html          # Dynamická hlavná stránka
├── forms/              # Testovanie formulárov
├── tables/             # Ukážky tabuliek
└── animations/         # CSS animácie
```

## Ako to funguje

Index.html dynamicky načítava obsah repozitára cez GitHub API:
- Automaticky zobrazuje všetky adresáre
- Po kliknutí na adresár zobrazí zoznam HTML súborov
- Pri pridaní nových súborov/adresárov sa zmeny prejavia automaticky

## Použitie

Stránky je možné prehliadať cez GitHub Pages. Pre lokálne testovanie je potrebný HTTP server (kvôli CORS).
