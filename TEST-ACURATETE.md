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

## Adăugat la deep pass (index per-formular, verificat pe randare)
6. **Ce solicită formularul F_CU_01?** → emiterea Certificatului de urbanism de informare; formular
   cu secțiunile 1. CĂTRE, 2. SOLICITANTUL, 3. IMOBILUL, 4. COMUNICAREA RĂSPUNSULUI, 5. DATA ȘI
   SEMNĂTURA; citează Legea 169/2026. Verificat pe randare, p.3. **PASS**
7. **Ce coduri au formularele de notificare și unde sunt?** → F_NOT_01…F_NOT_07, Anexa nr. 3,
   pp. 45–52. **PASS**
8. **Ce conține Anexa nr. 4?** → procese-verbale (pp. 55, 58) + o cerere (p.61), pp. 53–64;
   fără cod `F_`. **PASS**
9. **(control negativ) Există în acest document un formular pentru PATZ (amenajarea teritoriului zonal)?**
   → NU; formularele de aici sunt pentru autorizarea construirii (CU/autorizații/notificări). PATZ e
   tratat în Ordinul 1.022/2026 (repo `ordin-1022-corpus`). **PASS**
