# Constatări — MO 711 bis/2026

- **2 coloane** → extragere cu `pdftotext` FĂRĂ `-layout` (raw = ordine corectă).
- **Decalaj paginare 0** (verificat).
- **Conținut = formulare (2D).** Textul brut redă câmpurile în ordine de citire, dar NU poziția/
  aspectul. Pentru layout exact (casete, coloane de formular), **randează pagina** (`pdftoppm -r 150`).
- **Coduri de formular** (ex. `F_CU_01`) — folosește-le ca identificatori la citare.
- Capcane general-valabile: `../denisa/CONSTATARI.md`.
