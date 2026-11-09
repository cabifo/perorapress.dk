# perorapress.dk

Dansk adresse for Perora Press. Viser den samme »Kommer snart«-side som [perora.dk](https://perora.dk)
(projektet [cabifo/perora.dk](https://github.com/cabifo/perora.dk)). Siden peger på perora.dk som den
primære danske adresse (`<link rel="canonical">`), så søgemaskiner ikke ser to ens sider.

Den engelske side ligger i projektet [cabifo/perorapress.com](https://github.com/cabifo/perorapress.com).
GitHub kan kun knytte ét domæne til hvert projekt, derfor er der et projekt pr. domæne.

Siden kører på GitHub Pages fra grenen `main` (mappen `/`). Domænet står i filen `CNAME`.
DNS hos simply.com: A- og AAAA-poster for `@` til GitHub Pages og en CNAME-post `www` → `cabifo.github.io`.

## Ændre teksten

Teksten står i `index.html` og `404.html` — ret den samme tekst i projektet perora.dk, så de to danske
adresser viser det samme.
