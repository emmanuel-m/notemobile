# NoteMobile - Istruzioni per Claude

Questo è un sistema di note personali sincronizzato tramite GitHub.

## Come gestire le note

Quando l'utente chiede di prendere una nota:

1. **Crea un file markdown** nella cartella `note/` con il formato nome: `YYYY-MM-DD_titolo-breve.md`
   - Se esistono già note per lo stesso giorno con lo stesso tema, aggiungi un suffisso numerico (es. `_2`)
2. **Formato del file nota:**
   ```markdown
   # Titolo della nota

   **Data:** YYYY-MM-DD HH:MM
   **Tag:** #tag1 #tag2

   Contenuto della nota...
   ```
3. **Commit e push** dopo ogni nota, con messaggio: `Nota: <titolo breve>`
4. **Se l'utente chiede di cercare o consultare note**, cerca nei file esistenti in `note/`
5. **Se l'utente chiede di modificare una nota**, aggiorna il file esistente
6. **Se l'utente chiede un riepilogo**, leggi le note e fornisci un riassunto

## Regole

- Usa sempre il branch `main` per le note
- Scrivi le note nella lingua usata dall'utente
- Sii conciso ma completo nel contenuto
- I tag devono riflettere il contenuto della nota per facilitare la ricerca
