# NoteMobile

Sistema di note personali veloce, accessibile ovunque e sincronizzato tramite GitHub.

## Come funziona

1. **Prendi note ovunque** - Apri Claude (app mobile, desktop o web) e scrivi la tua nota
2. **Sincronizzazione automatica** - Le note vengono salvate su GitHub automaticamente
3. **Accedi dal computer** - Fai `git pull` per avere tutte le note aggiornate sul tuo PC

## Struttura

```
notemobile/
├── note/                    # Tutte le note
│   ├── 2026-04-01_esempio.md
│   └── ...
├── CLAUDE.md                # Istruzioni per Claude
└── README.md
```

## Uso rapido

Apri Claude e scrivi semplicemente:
- *"Nota: comprare il latte e la frutta"*
- *"Appunto: idea per il progetto X..."*
- *"Ricordami di chiamare Mario domani"*
- *"Cerca nelle mie note..."*

## Sincronizzazione sul PC

```bash
git clone https://github.com/emmanuel-m/notemobile.git
# Per aggiornare:
git pull
```
