# Changelog

Tutte le modifiche importanti a Friisbi Reader saranno documentate in questo file.

Il formato è basato su [Keep a Changelog](https://keepachangelog.com/it/1.0.0/),
e questo progetto aderisce al [Semantic Versioning](https://semver.org/lang/it/).

## [Non rilasciato]

### In Sviluppo
- Nessuna modifica in corso

## [0.0.1] - 2025-11-14

### Aggiunto
- 🎉 **Release iniziale di Friisbi Reader**
- 📰 Parsing automatico di feed RSS/Atom
- 👥 Supporto multi-utente con iscrizioni personalizzate
- 🔄 Sincronizzazione automatica oraria dei feed
- 🎨 Interfaccia stile Flipboard con card moderne
- 🔐 Registrazione pubblica utenti con approvazione automatica
- 📱 Design responsive per desktop, tablet e mobile
- 🔖 Magazine (collezioni di feed)
- 💾 Salvataggio post preferiti
- 🔍 Anteprima feed prima dell'iscrizione
- ⚡ Caricamento infinito dei post
- 📊 API complete per gestione feed e sincronizzazione
- 📚 Documentazione completa in README.md
- 🛠️ Guida installazione per Frappe Bench
- 🎯 Supporto per Frappe v16+

### Caratteristiche Tecniche
- Parser RSS con feedparser 6.0.10+
- Scheduler Frappe per sync automatica
- API whitelisted per chiamate REST
- DocTypes: Feed, Post, Subscription, Magazine, Settings
- Client scripts per azioni interattive
- Server scripts per logica avanzata

### Documentazione
- README.md con guida completa
- INSTALLATION_GUIDE.md per setup dettagliato
- Esempi API con JSON di risposta
- Troubleshooting guide
- Istruzioni pubblicazione Marketplace

### File di Configurazione
- setup.py per installazione package
- requirements.txt con dipendenze
- hooks.py con configurazione Frappe
- MANIFEST.in per inclusione file

## [0.0.2] - TBD

### Pianificato
- [ ] Cache dei feed per migliorare performance
- [ ] Filtri e ricerca avanzata
- [ ] Export/import OPML per feed
- [ ] Notifiche per nuovi post
- [ ] Modalità scura
- [ ] PWA support per uso offline
- [ ] Statistiche lettura utente
- [ ] Condivisione social integrata
- [ ] Plugin per reader esterni

### Da Considerare
- [ ] Supporto podcast
- [ ] Integrazione con Pocket/Instapaper
- [ ] AI per raccomandazioni personalizzate
- [ ] Categorie automatiche con ML
- [ ] Mobile app nativa

---

## Tipi di Modifiche

- `Added` - Nuove feature
- `Changed` - Modifiche a funzionalità esistenti
- `Deprecated` - Feature che saranno rimosse
- `Removed` - Feature rimosse
- `Fixed` - Bug fix
- `Security` - Fix di sicurezza

## Come Leggere le Versioni

Versione formato: `MAJOR.MINOR.PATCH`

- **MAJOR**: Modifiche incompatibili con versioni precedenti
- **MINOR**: Nuove feature retrocompatibili
- **PATCH**: Bug fix retrocompatibili

---

[Non rilasciato]: https://github.com/SicurSam/friisbi/compare/v0.0.1...HEAD
[0.0.1]: https://github.com/SicurSam/friisbi/releases/tag/v0.0.1
