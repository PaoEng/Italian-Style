# Italian Style - Single Skill with 18 Regional Dialects

Una **singola skill postprocessore** che riscrive le risposte di Copilot in uno dei 18 dialetti italiani regionali. Se il dialetto non è specificato, **chiede all'utente quale scegliere**.

## 📍 Dialetti Supportati (18 Regioni)

| # | Dialetto | Regione | Stile |
|---|----------|---------|-------|
| 1 | Piemontese | Piemonte | Sobrio, preciso, musicale |
| 2 | Lombardo | Lombardia | Diretto, pragmatico, industrioso |
| 3 | Veneto | Veneto | Asciutto, concreto, preciso |
| 4 | Friulano | Friuli-V.G. | Conservatore, melodico, caratteristico |
| 5 | Ligure | Liguria | Cantalengo, musicale, marittimo |
| 6 | Emiliano-Romagnolo | Emilia-Romagna | Bonario, sonoro, accogliente |
| 7 | Toscano | Toscana | Colto, ritmico, elegante |
| 8 | Umbro | Umbria | Morbido, melodico, centrale |
| 9 | Marchigiano | Marche | Morbido, musicale, adriatico |
| 10 | Romanesco | Lazio | Diretto, colloquiale, ironico |
| 11 | Abruzzese | Abruzzo | Robusto, montano, marcato |
| 12 | Molisano | Molise | Simile all'abruzzese, montano, autentico |
| 13 | Napoletano | Campania | Espressivo, melodico, musicale |
| 14 | Lucano | Basilicata | Robusto, meridionale, caratteristico |
| 15 | Pugliese | Puglia | Sonoro, robusto, solare |
| 16 | Calabrese | Calabria | Forte, diretto, meridionale |
| 17 | Siciliano | Sicilia | Fluido, caldo, musicale |
| 18 | Sardegnolo | Sardegna | Solenne, ritmico, caratteristico |

## 📁 Struttura

```
Italian-Style/
├── SKILL.md                           # Skill principale unica
├── README.md                          # Questo file
├── dialects/                          # 18 file di configurazione
│   ├── piemontese.config
│   ├── lombardo.config
│   ├── veneto.config
│   ├── friulano.config
│   ├── ligure.config
│   ├── emiliano-romagnolo.config
│   ├── toscano.config
│   ├── umbro.config
│   ├── marchigiano.config
│   ├── romanesco.config
│   ├── abruzzese.config
│   ├── molisano.config
│   ├── napoletano.config
│   ├── lucano.config
│   ├── pugliese.config
│   ├── calabrese.config
│   ├── siciliano.config
│   └── sardegnolo.config
```

## 🎯 Funzionalità

### Selezione Dialetto

Se dialetto non è specificato:
1. **Chiede all'utente** quale dialetto desidera
2. **Mostra lista** di 18 dialetti
3. **Procede** con trasformazione


## Installazione / aggiornamento

```bash
npx skills add ./Italian-Style -a github-copilot -y -g
```

## 🔧 Utilizzo

```bash
# Selezione interattiva
/italian-style

# Con dialetto specifico
/italian-style dialetto:siciliano

# Con modalità mista
/italian-style dialetto:napoletano mode:mista
```

## 📚 Dettagli

- **Tipo**: postprocess
- **Versione**: 2.0.0
- **Configurazioni**: 18 file indipendenti
- **Modalità**: pura (default) / mista
- **Autenticità**: garantita per ogni dialetto

---

Autenticità linguistica regionale in ogni trasformazione.
