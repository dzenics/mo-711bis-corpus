# MANIFEST — MO 711 bis/2026 (Anexe 1–4, Ordinul MDLPA 975/2026)

Modele de formulare pentru **autorizarea construirii**. Fiecare formular are un **cod** (`F_…`) și
`versiunea 1.0`. Formularele **citează Legea nr. 169/2026** (Codul) — vezi repo `mo-661-corpus`.
Sunt structuri 2D (casete): textul ancorat redă câmpurile în ordine, dar pentru **layout exact
randează pagina** (`pdftoppm -r 130 "MO-711bis-partea-I.pdf" -f <p> -l <p>`).

## Index per-formular (cod → pagini → tip)

### Anexa nr. 1 — Certificat de urbanism (`F_CU_*`), pp. 3–14
| Cod | Pagini | Tip / conținut |
|---|---|---|
| F_CU_01 | 3 | CERERE — emitere certificat de urbanism de informare (verificat pe randare, p.3) |
| F_CU_02 | 4 | CERERE |
| F_CU_03 | 5 | CERERE |
| F_CU_04 | 6–7 | CERERE |
| F_CU_05 | 8 | CERTIFICAT (de urbanism) |
| F_CU_06 | 9–10 | CERTIFICAT |
| F_CU_07 (_0/_01) | 11–12 | CERTIFICAT |
| F_CU_07_1 | 13–14 | ANEXĂ DE COMPLETARE |

### Anexa nr. 2 — Autorizații (`F_A_*`, `F_AM_*`, `F_AR_*`), pp. 15–44
| Cod | Pagini | Tip / conținut |
|---|---|---|
| F_A_01 | 15–20 | Cerere / Referat + ANEXA IMOBILE (p.17) + ANEXA TEHNICĂ (p.18) |
| F_A_02 | 21 | CERERE |
| F_A_03 | 22–23 | DECLARAȚIE / cerere |
| F_A_04 | 24, 26 | AUTORIZAȚIE |
| F_A_05 | 27 | CERERE |
| F_A_06 | 28 | Cerere |
| F_A_07 | 25, 29–30 | Autorizație / ANEXĂ la autorizație |
| F_A_08 | 31 | Cerere |
| F_A_09 | 32–33 | Cerere / Formular |
| F_A_10 | 34 | Cerere |
| F_A_11 | 35–36 | Cerere / autorizație |
| F_AM_01 | 37–38 | CERERE / Referat |
| F_AM_02 | 39–40 | AUTORIZAȚIE |
| F_AR_01 | 41–42 | CERERE |
| F_AR_02 | 43–44 | AUTORIZAȚIE |

### Anexa nr. 3 — Notificări (`F_NOT_*`), pp. 45–52
| Cod | Pagini | Tip |
|---|---|---|
| F_NOT_01 | 45–46 | Notificare |
| F_NOT_02 | 47 | Notificare |
| F_NOT_03 | 48 | Notificare |
| F_NOT_04 | 49 | Notificare |
| F_NOT_05 | 50 | Notificare |
| F_NOT_06 | 51 | Notificare |
| F_NOT_07 | 52 | Cerere |

### Anexa nr. 4 — Procese-verbale, pp. 53–64 (fără cod `F_`)
| Pagini | Tip |
|---|---|
| 53 | ANEXA NR. 4 (deschidere) |
| 55, 58 | PROCES-VERBAL |
| 61 | CERERE |

## Constatări specifice
- Codurile de formular sunt identificatorul canonic de citare (ex. „F_CU_01, p.3").
- Ordinea codurilor pe pagini poate fi **întrețesută** (ex. F_A_04 pe p.24/26 și F_A_07 pe p.25/29–30,
  două formulare pe pagini alăturate) — confirmă pe pagină.
- Layout exact (casete/coloane de formular) doar din randare, nu din textul brut.
