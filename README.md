# RD Autoservis

Jednostránkový web RD Autoservis v češtině. Statické HTML, CSS a obrázky jsou ve složce `dist/`. Nevyžaduje sestavení, server ani databázi.

## Nasazení

Workflow `.github/workflows/pages.yml` publikuje obsah `dist/` na GitHub Pages při každé změně větve `main`. Lze jej spustit také ručně v Actions.

V nastavení repozitáře musí být v **Settings → Pages → Build and deployment → Source** vybráno **GitHub Actions**.

## Úpravy

- `dist/index.html`: texty, přehled služeb a kontakty.
- `dist/styles.css`: responzivní černobílý vzhled.
- `dist/assets/rd-logo.png`: původní logo.
- `dist/assets/workshop.webp`: generovaná ilustrační fotografie, nikoli skutečná provozovna.

Kontakt: Robert Dumka, +420 777 537 037, rober.dumka@seznam.cz. Nabídka zahrnuje také karosářské práce. Adresa a otevírací doba čekají na doplnění od provozovatele. Ostatní nabídka služeb a texty o přístupu vycházejí z dosavadního návrhu.
