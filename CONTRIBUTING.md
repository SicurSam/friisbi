# Contributing to Friisbi Reader

Grazie per il tuo interesse nel contribuire a Friisbi Reader! 🎉

## Come Contribuire

### 1. Fork e Clone

```bash
# Fork il repository su GitHub, poi clona
git clone https://github.com/TUO_USERNAME/friisbi.git
cd friisbi
```

### 2. Crea un Branch

```bash
# Crea un branch per la tua feature o fix
git checkout -b feature/nome-feature
# oppure
git checkout -b fix/nome-fix
```

### 3. Sviluppo

- Scrivi codice pulito e commentato
- Segui le convenzioni di Frappe Framework
- Testa le tue modifiche su Frappe v16
- Assicurati che le API esistenti continuino a funzionare

### 4. Commit

```bash
# Aggiungi i file modificati
git add .

# Commit con messaggio descrittivo
git commit -m "feat: descrizione della feature"
# oppure
git commit -m "fix: descrizione del fix"
```

**Convenzioni per i messaggi di commit:**
- `feat:` - Nuova feature
- `fix:` - Bug fix
- `docs:` - Modifiche alla documentazione
- `style:` - Formattazione, punto e virgola mancanti, etc
- `refactor:` - Refactoring del codice
- `test:` - Aggiunta di test
- `chore:` - Aggiornamenti di build, package manager, etc

### 5. Push e Pull Request

```bash
# Push del branch
git push origin feature/nome-feature
```

Poi su GitHub:
1. Vai al repository originale
2. Clicca "New Pull Request"
3. Seleziona il tuo branch
4. Descrivi le modifiche
5. Invia la PR

## Linee Guida

### Codice

- **Python**: Segui PEP 8
- **JavaScript**: Usa ES6+ quando possibile
- **Indentazione**: Tab per Python (Frappe standard), 2 spazi per JS
- **Nomi**: Usa `snake_case` per Python, `camelCase` per JavaScript

### Documentazione

- Commenta funzioni complesse
- Aggiorna il README se aggiungi feature
- Aggiungi docstrings alle funzioni API
- Documenta i nuovi parametri

### Testing

Prima di inviare una PR:

1. **Testa su Frappe v16**: Assicurati che funzioni su una installazione pulita
2. **Verifica le API**: Testa tutti gli endpoint API modificati
3. **Controlla i log**: Nessun errore nel console.log o Error Log
4. **Prova la UI**: Verifica che l'interfaccia funzioni correttamente

### Cosa Cerchiamo

Siamo interessati a:

- ✅ Bug fixes
- ✅ Nuove feature utili
- ✅ Miglioramenti performance
- ✅ Miglioramenti UX/UI
- ✅ Documentazione migliore
- ✅ Supporto per più tipi di feed
- ✅ Internazionalizzazione (i18n)

## Struttura del Progetto

```
friisbi/
├── friisbi/
│   ├── __init__.py           # Versione app
│   ├── hooks.py              # Hook Frappe e scheduler
│   ├── api.py                # API per RSS sync
│   ├── config/               # Config desk
│   └── public/               # CSS, JS, immagini
├── setup.py                  # Setup package
├── requirements.txt          # Dipendenze Python
└── README.md                 # Documentazione
```

## DocTypes

I principali DocTypes sono:

1. **Friisbi Feed** - Feed RSS/Atom
2. **Friisbi Post** - Post singoli dai feed
3. **Friisbi Subscription** - Iscrizioni utente ai feed
4. **Friisbi Magazine** - Magazine (collezioni di feed)
5. **Friisbi Settings** - Impostazioni globali

## API Principali

- `sync_feed(feed_name)` - Sincronizza un feed
- `sync_all_feeds()` - Sincronizza tutti i feed
- `get_feed_preview(url)` - Anteprima feed prima di aggiungerlo

## Domande?

Apri una [issue](https://github.com/SicurSam/friisbi/issues) o contattaci!

## Codice di Condotta

- Sii rispettoso e professionale
- Collabora in modo costruttivo
- Accetta feedback in modo positivo
- Aiuta altri contributori

## Licenza

Contribuendo, accetti che il tuo codice sia distribuito sotto licenza MIT.

---

Grazie per contribuire a Friisbi Reader! 🚀
