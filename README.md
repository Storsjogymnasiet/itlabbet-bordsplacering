# Bordsplacerare

En liten webbapp för att slumpa fram bordsplaceringar i IT-labbet. Allt körs i webbläsaren — ingen backend, ingen databas.

**Live:** https://storsjogymnasiet.github.io/itlabbet-bordsplacering/

## Funktioner

- Namnlista: välj en förvald klass eller klistra in en egen lista (ett namn per rad).
- Salens layout: rita upp rader av bordsgrupper, t.ex. `4, 2` ger en klunga på 4 bord och en klunga på 2. Rader kan spridas ut till kanterna eller klumpas ihop.
- Slumpa platser: fördelar namnlistan slumpmässigt över de uppritade platserna.
- Exportera som bild: sparar den aktuella placeringen som en PNG.
- Skriv ut schema: utskriftsvänlig vy av placeringen.

## Köra lokalt

Sidan är en enda statisk `index.html`-fil, så det räcker att öppna den i en webbläsare.

Vill du köra den bakom nginx via Docker:

```
docker compose up
```

Sidan blir då tillgänglig på http://localhost:8080.

## Deploy

Sidan publiceras som statisk sajt via GitHub Pages från `main`-branchen.
