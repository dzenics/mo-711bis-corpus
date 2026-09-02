# Test de acuratețe — MO 711 bis/2026

1. **Ce conține MO 711 bis/2026?** → Anexele nr. 1–4 la Ordinul MDLPA nr. 975/2026 (modele de
   formulare pentru autorizarea construirii), pp. 3–64. Sursă: SUMAR p.1. **PASS**
2. **Care e primul formular din Anexa 1 și codul lui?** → o CERERE cu codul `F_CU_01 · versiunea 1.0`
   (p.3). **PASS**
3. **Câte anexe și unde încep?** → 4: Anexa 1 (p.3), Anexa 2 (p.15), Anexa 3 (p.29), Anexa 4 (p.53). **PASS**
4. **(control negativ) Conține Procedura de elaborare a PATZ/PUG?** → NU; aceea e în Ordinul 1.022/2026
   (repo `ordin-1022-corpus`), nu aici. **PASS**
5. **Layout-ul exact al unui formular se poate cita din text?** → NU direct — textul dă câmpurile;
   pentru poziții/casete randează pagina. **PASS**

**Risc rezidual:** fără index per-formular (cod F_* ↔ pagini) și fără verificare pe randare a fiecărui
formular; de adăugat la nevoie.
