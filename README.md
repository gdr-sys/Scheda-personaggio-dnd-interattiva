# 🎲 Scheda Personaggio D&D 5e Interattiva

> Una scheda personaggio digitale completa per **Dungeons & Dragons 5ª edizione**, compatibile con i regolamenti 2014 e 2024. Pensata per il mobile, funziona interamente nel browser. Zero installazioni, zero server.
>
> A complete digital character sheet for **D&D 5th Edition** — works on mobile, runs entirely in the browser. No installation required.

![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![No Dependencies](https://img.shields.io/badge/dependencies-none-brightgreen)
![Single File](https://img.shields.io/badge/size-single%20HTML%20file-blue)
![Mobile First](https://img.shields.io/badge/mobile-optimized-blueviolet)
![Works Offline](https://img.shields.io/badge/works-offline-orange)
![D&D 5e](https://img.shields.io/badge/D%26D-5e%20SRD-red)
![i18n](https://img.shields.io/badge/language-IT-informational)

---

## 🔗 Links

| | |
|---|---|
| 🌐 **Live Demo** | [gdr-sys.github.io/Scheda-personaggio-dnd-interattiva](https://gdr-sys.github.io/Scheda-personaggio-dnd-interattiva/) |
| 📦 **Repository** | [github.com/gdr-sys/Scheda-personaggio-dnd-interattiva](https://github.com/gdr-sys/Scheda-personaggio-dnd-interattiva) |

---

## 🤔 Perché questo progetto

Gestire un personaggio D&D durante una sessione può essere caotico: schede cartacee che si rovinano, PDF poco pratici, app che richiedono connessione o abbonamenti.

Questa scheda risolve il problema:
- **Un solo file HTML** — nessuna installazione, funziona offline
- **Ottimizzata per mobile** — usala al tavolo dal telefono
- **Calcoli automatici** — bonus, slot, risorse di classe
- **Cloud sync opzionale** — salva su Supabase se vuoi, altrimenti resta tutto locale

---

## 🎯 Per chi è pensata

- **Giocatori D&D 5e** che vogliono una scheda digitale pratica al tavolo
- **Master** che devono gestire PNG complessi durante le sessioni
- **Giocatori multiclasse** che odiano calcolare manualmente bonus e risorse
- **Chi gioca dal vivo** con il telefono come supporto
- **Chi vuole il controllo totale** — nessun account obbligatorio, dati tuoi

---

## ✨ Funzionalità

### ⚔️ Combattimento

- **Popup di tiro integrati** per attacchi, incantesimi, tiri salvezza e abilità
- **Calcolo automatico** di bonus, critici, Attacco Furtivo (Ladro) e Divine Smite (Paladino)
- **Gestione concentrazione** — promemoria TS automatico quando subisci danno
- **Rottura concentrazione** automatica se fallisci il TS o vai a 0 PF
- **Supporto Ispirazione** — vantaggio (2014) o ritiro (2024)

### 🧙 Incantesimi & Magia

- **Slot incantesimo** con tracking visuale
- **Slot Patto (Warlock)** gestiti separatamente
- **Recupero automatico** su riposo breve/lungo
- **Flexible Casting** — conversione slot ↔ punti stregoneria per Stregone

### 🎭 Multiclasse

- **Gestione completa** di più classi contemporaneamente
- **Calcolo automatico** di livello totale, dadi vita, competenze
- **Risorse di classe automatiche**:
  - Ispirazione Bardica
  - Dadi Superiorità
  - Punti Stregoneria
  - Channel Divinity
  - Punti Ki/Disciplina
  - Second Wind
  - Action Surge
  - Furia
  - Lay on Hands
- Le risorse **si creano, scalano e si rimuovono** automaticamente con le classi

### 🐺 Companion & Forme

- **Forma Selvatica** — tracker usi dedicato per il Druido
- **Differenze 2014/2024** gestite automaticamente
- **Pagina Companion** per famigli, cavalcature, evocazioni

### 📚 Organizzazione

| Pagina | Contenuto |
|--------|-----------|
| Principale | Stats, PF, CA, velocità |
| Abilità | Tutte le skill con bonus calcolati |
| Combattimento | Attacchi, azioni, popup tiri |
| Incantesimi | Lista spell, slot, concentrazione |
| Privilegi | Tratti razziali e di classe |
| Combo | Combinazioni di abilità salvate |
| Inventario | Oggetti, peso, equipaggiamento |
| Personalità | Tratti, ideali, legami, difetti |
| Diario | Note di sessione |
| Mondo | Worldbuilding, PNG, luoghi |
| Homebrew | Regole personalizzate |
| Impostazioni | Toggle 2014/2024, cloud sync |

### ☁️ Salvataggio

- **Locale (IndexedDB/localStorage)** — sempre attivo, zero config
- **Cloud (Supabase)** — opzionale, sincronizza tra dispositivi
- **Multi-scheda** — gestisci più personaggi

### 🔄 Compatibilità Edizioni

Toggle nelle Impostazioni per adattare automaticamente:
- Formule che cambiano tra SRD 2014 e 2024
- Ispirazione Bardica
- Forma Selvatica
- E altre meccaniche

---

## 🛠️ Tech Stack

| Layer | Tecnologia |
|-------|------------|
| Core | Vanilla JavaScript (ES2022+) |
| UI | HTML5 + CSS3 (no frameworks) |
| Storage locale | IndexedDB, localStorage |
| Cloud sync | Supabase (opzionale) |
| Hosting | GitHub Pages |

**Zero dipendenze runtime** — tutto in un singolo file `index.html`.

---

## 📱 Mobile First

L'interfaccia è progettata per schermi di telefono:

- ✅ Testo leggibile senza zoom
- ✅ Campi numerici ampi e tap-friendly
- ✅ Popup sempre richiudibili
- ✅ Navigazione a tab per non perdere il filo
- ✅ Funziona offline dopo il primo caricamento

---

## 🚀 Come usare

**Nessuna installazione richiesta.**

### Online
👉 [Apri la demo live](https://gdr-sys.github.io/Scheda-personaggio-dnd-interattiva/)

### Offline
1. Scarica `index.html` dal repository
2. Aprilo nel browser
3. Fatto — funziona senza internet

```bash
# Oppure clona il repo
git clone https://github.com/gdr-sys/Scheda-personaggio-dnd-interattiva.git
cd Scheda-personaggio-dnd-interattiva
open index.html
```

---

## 🚀 Deploy

### GitHub Pages (consigliato)
1. Fai fork del repository
2. Vai in **Settings → Pages**
3. Seleziona source: `main` branch, `/ (root)`
4. La tua scheda è live su `https://<username>.github.io/Scheda-personaggio-dnd-interattiva/`

### Altri hosting
Carica `index.html` su qualsiasi servizio statico:
- Netlify (drag & drop)
- Vercel
- Cloudflare Pages
- Il tuo server

---

## 🗺️ Roadmap

- [x] Multiclasse completo
- [x] Risorse di classe automatiche
- [x] Compatibilità 2014/2024
- [x] Salvataggio cloud
- [x] Gestione concentrazione
- [ ] Altre lingue (EN, ES, FR)

---

## 🤝 Contribuire

Contributi benvenuti!

1. Fai fork del repository
2. Crea un branch (`git checkout -b feature/nuova-funzione`)
3. Committa le modifiche (`git commit -m 'Aggiunge nuova funzione'`)
4. Pusha il branch (`git push origin feature/nuova-funzione`)
5. Apri una Pull Request

> **Nota:** Essendo un progetto single-file, tutte le modifiche vanno in `index.html`.

### Segnalazioni

- 🐛 Bug? Apri una [Issue](https://github.com/gdr-sys/Scheda-personaggio-dnd-interattiva/issues)
- 💡 Idea? Proponila nelle Issues o nelle Discussions

---

## ⚠️ Stato del progetto

**In sviluppo attivo** — aggiornato regolarmente in base alle esigenze reali emerse al tavolo di gioco.

---

## 📜 Licenza

MIT License

Questo progetto utilizza contenuti tratti dal **System Reference Document (SRD)** di D&D 5e, rilasciato da Wizards of the Coast sotto la relativa licenza.

---

## 🙏 Crediti

- **Wizards of the Coast** per il SRD 5e
- La community D&D per feedback e suggerimenti

  <sub>Se ti è utile, lascia una ⭐ sul repository!</sub>
</p>
