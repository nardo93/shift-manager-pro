# Shift Manager Pro 🗓️

**Intelligent shift scheduling for multi-venue hospitality businesses**  
*Pianificazione turni intelligente per la ristorazione multi-locale*

---

## 🇬🇧 English

### What is this?

**Shift Manager Pro** is a free, open-source, single-file web application for scheduling employee shifts across multiple bars, restaurants, or hospitality venues. It runs entirely in the browser — no server, no installation, no subscription required.

It was built out of a real operational need: managing shift scheduling across multiple bar venues simultaneously, while respecting employee preferences, leave periods, contractual hour targets, and staffing requirements that vary by day and shift.

### Who is it for?

- Bar and restaurant owners managing 2–10 venues
- Hospitality managers handling shift scheduling manually (Excel, paper, WhatsApp)
- Small hospitality groups that can't afford enterprise workforce management software

### Features

- **Multi-venue support** — configure unlimited bars/restaurants, each with its own schedule
- **Flexible shift structure** — 1, 2 or 3 shifts per day, with customizable start/end times
- **Smart auto-generation** — AI-assisted scheduling algorithm that respects:
  - Employee availability preferences (preferred / unavailable / mandatory)
  - Fixed rest days and rest days per week
  - Monthly hour targets
  - Junior/apprentice pairing requirements (must work with a senior)
  - Venue preferences per employee
  - Holiday and leave periods
  - Partial closures by day and shift
  - Extraordinary closure periods
- **Manual override** — click any cell in the grid to manually adjust assignments
- **Validation engine** — automatic alerts for hour overruns and unmet pairing requirements
- **Monthly and weekly view** — toggle between planning horizons
- **Excel export** — full shift grid + hours summary per employee
- **Archive system** — save and revisit past schedules
- **Reports** — hours worked vs. target per employee, sortable
- **Roles** — Barman, Cameriere (Waiter), Manager, Cuoco (Chef)
- **Zero dependencies to install** — everything loads from CDN; just open the HTML file

### Tech Stack

| Technology | Purpose |
|---|---|
| React 18 (UMD) | UI components and state management |
| Tailwind CSS (CDN) | Styling |
| SheetJS (XLSX) | Excel export |
| Font Awesome | Icons |
| Babel Standalone | JSX transformation in-browser |
| localStorage | Persistent data storage |

### Getting Started

1. Download `GeneratoreTurni.html`
2. Open it in any modern browser (Chrome, Firefox, Edge, Safari)
3. That's it. No installation. No account. No internet required after first load (if assets are cached).

### Usage Flow

```
1. Locali (Venues)     → Add your bars/restaurants with opening hours and shift structure
2. Dipendenti          → Add employees with roles, hour targets, preferences and availability
3. Configurazione      → Set staffing requirements per venue per day
4. Turni & Griglia     → Select a month or week → Generate → Review → Adjust → Archive
5. Report / Archivio   → Review past schedules and hours summaries
```

### Roadmap / Ideas for Contribution

- [ ] Multi-language UI (currently Italian)
- [ ] PDF export for individual employee schedules
- [ ] Drag-and-drop shift reassignment
- [ ] Dark mode
- [ ] PWA / offline-first support
- [ ] Import employees from CSV
- [ ] Conflict resolution suggestions
- [ ] Time-off request workflow

### License

MIT License — free to use, modify and distribute.

### About the Author

This project was created by **Lorenzo**, an industrial engineer and hospitality entrepreneur managing multiple bars and restaurants in central Italy. It grew from the practical methods described in his book *[Ingegneria del bar](https://www.amazon.it/)* (Bar Engineering), which applies industrial engineering principles to bar management.

---

## 🇮🇹 Italiano

### Cos'è?

**Shift Manager Pro** è un'applicazione web gratuita e open-source — un singolo file HTML — per la pianificazione dei turni del personale in locali di ristorazione e bar. Funziona interamente nel browser, senza server, senza installazione, senza abbonamenti.

È nata da una necessità operativa reale: gestire i turni di più locali contemporaneamente, rispettando le preferenze dei dipendenti, le ferie, gli obiettivi contrattuali di ore mensili e i fabbisogni di personale variabili per giorno e turno.

### A chi serve?

- Titolari di bar e ristoranti con 2–10 locali
- Responsabili della ristorazione che gestiscono i turni manualmente (Excel, carta, WhatsApp)
- Piccoli gruppi di locali che non possono permettersi software enterprise per la gestione del personale

### Funzionalità

- **Multi-locale** — configura tutti i tuoi bar/ristoranti, ognuno con la propria struttura
- **Turni flessibili** — 1, 2 o 3 turni al giorno con orari personalizzabili
- **Generazione automatica intelligente** — l'algoritmo rispetta:
  - Preferenze di disponibilità del dipendente (preferito / non disponibile / obbligatorio)
  - Giorni di riposo fissi e riposi settimanali
  - Target di ore mensili
  - Affiancamento junior/apprendista (deve lavorare con un senior)
  - Preferenze di locale per dipendente
  - Ferie e assenze pianificate
  - Chiusure parziali per giorno e turno
  - Periodi di chiusura straordinaria
- **Modifica manuale** — clicca su qualsiasi cella per correggere le assegnazioni
- **Motore di validazione** — alert automatici per sforamenti ore e mancati affiancamenti
- **Vista mensile e settimanale**
- **Export Excel** — griglia turni completa + riepilogo ore per dipendente
- **Archivio storico** — salva e consulta i turni passati
- **Report** — ore lavorate vs. target per dipendente, ordinabili
- **Ruoli** — Barman, Cameriere, Manager, Cuoco
- **Zero dipendenze da installare** — tutto caricato da CDN; basta aprire il file HTML

### Come iniziare

1. Scarica `GeneratoreTurni.html`
2. Aprilo in qualsiasi browser moderno (Chrome, Firefox, Edge, Safari)
3. Fine. Nessuna installazione. Nessun account. Non serve internet dopo il primo caricamento.

### Flusso d'uso

```
1. Locali          → Aggiungi bar/ristoranti con orari e struttura turni
2. Dipendenti      → Inserisci dipendenti con ruoli, ore target, preferenze e disponibilità
3. Configurazione  → Imposta fabbisogno personale per locale e per giorno
4. Turni & Griglia → Scegli mese o settimana → Genera → Rivedi → Modifica → Archivia
5. Report/Archivio → Consulta turni passati e riepilogo ore
```

### Licenza

MIT License — libero di usare, modificare e distribuire.

### Sull'autore

Questo progetto è stato creato da **Lorenzo**, ingegnere gestionale e imprenditore nel settore della ristorazione, con esperienza diretta nella gestione di più bar in Italia centrale. Il progetto è nato dai metodi descritti nel suo libro *[Ingegneria del bar](https://www.amazon.it/)*, che applica i principi dell'ingegneria gestionale alla gestione dei bar.

---

## Screenshots

*Coming soon — contributions welcome*

---

## Contributing

Issues and pull requests are welcome. If you manage hospitality venues and have feature ideas based on real operational needs, open a discussion.
