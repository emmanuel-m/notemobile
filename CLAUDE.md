# NoteMobile - Istruzioni per Claude

Sistema di note personali: l'utente le cattura in mobilità (telefono, voce, qualsiasi dispositivo) tramite GitHub, e le ritrova e gestisce qui tramite Claude Code.

---

## Struttura cartelle

```
note/
  idee/        → idee, spunti creativi, intuizioni
  todo/         → cose da fare, promemoria, task
  appunti/      → appunti su argomenti specifici, studio, ricerca
  progetti/     → note legate a un progetto specifico
  varie/        → tutto ciò che non rientra nelle categorie sopra
```

Se la categoria non è chiara dal contesto, usa `varie/`.

---

## Creare una nota

1. **Scegli la sottocartella** in base al contenuto
2. **Nome file:** `YYYY-MM-DD_titolo-breve.md`
   - Se esiste già una nota con lo stesso titolo nello stesso giorno, aggiungi `_2`, `_3`, ecc.
3. **Formato del file:**
   ```markdown
   # Titolo della nota

   **Data:** YYYY-MM-DD HH:MM
   **Tag:** #tag1 #tag2
   **Categoria:** idee | todo | appunti | progetti | varie

   Contenuto...
   ```
4. **Commit e push** dopo ogni nota con messaggio: `Nota: <titolo breve>`

---

## Aggiornare da mobile

Quando l'utente dice "aggiorna" o "sincronizza":
1. `git pull origin main`
2. Elenca le note nuove o modificate dall'ultimo pull
3. Se ci sono note appena arrivate dal mobile, mostra un breve riassunto del contenuto

---

## Cercare e consultare le note

- **Ricerca per parola:** cerca nei file in `note/` con grep
- **Ricerca per tag:** cerca il tag `#tag` nei file
- **Ricerca per data:** guarda il nome dei file (formato `YYYY-MM-DD`)
- **Ricerca per categoria:** guarda nella sottocartella corrispondente
- **Riepilogo generale:** leggi tutti i file recenti e fornisci un riassunto organizzato per categoria

---

## Regole generali

- Pusha sempre su `main`, salvo indicazione contraria
- Scrivi le note nella lingua usata dall'utente in quel momento
- Sii conciso nel contenuto, mai ridondante
- I tag devono riflettere il contenuto per facilitare la ricerca futura
- Non creare sottocartelle oltre quelle definite sopra senza chiedere
- Se l'utente manda una nota grezza (testo disorganizzato), riformattala nel formato standard prima di salvarla
