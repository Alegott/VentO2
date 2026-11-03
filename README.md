<div align="center">

# 🌬️ VentO₂

### Il Veneto che respiri. Il futuro che scegli.

**Esplora il territorio, scopri il suo stato ambientale e immagina come potrebbe cambiare.**

[![React](https://img.shields.io/badge/React-19-149ECA?logo=react&logoColor=white)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-7-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-8-646CFF?logo=vite&logoColor=white)](https://vite.dev/)
[![Three.js](https://img.shields.io/badge/Three.js-3D-222222?logo=threedotjs&logoColor=white)](https://threejs.org/)
[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-2E7D32)](LICENSE)

*Un progetto nato durante un hackathon, con un punto di partenza concreto: la provincia di Vicenza.*

[Scopri il progetto](#-cosè-vento₂) · [Funzionalità](#-cosa-puoi-fare) · [Avvia in locale](#-come-avviare-il-progetto) · [Dati e trasparenza](#-dati-e-trasparenza)

</div>

---

## 🌱 Cos'è VentO₂?

**VentO₂** è una web app interattiva che rende la sostenibilità più facile da **vedere, capire e immaginare**.

Per molti di noi, la qualità dell'aria è soltanto un numero in una tabella. Ma cosa significa davvero per il luogo in cui viviamo? E quanto potrebbero contare scelte come installare pannelli fotovoltaici, migliorare l'isolamento di casa o creare nuovi spazi verdi?

Con VentO₂, i dati diventano un'esperienza visiva: puoi esplorare la **provincia di Vicenza**, osservare gli indicatori ambientali dei comuni e provare scenari ipotetici per confrontare possibili cambiamenti.

> **La nostra idea:** trasformare dati difficili da interpretare in un territorio da esplorare, per aiutare le persone a porsi domande migliori sul proprio futuro.

## ✨ Cosa puoi fare

| Funzione | In parole semplici |
| --- | --- |
| 🗺️ **Esplorare il territorio** | Naviga tra i **114 comuni della provincia di Vicenza** e confronta i loro indicatori ambientali. |
| 🌳 **Osservare il paesaggio** | Una rappresentazione visiva in 3D aiuta a interpretare le condizioni ambientali attraverso colori e caratteristiche del paesaggio. |
| 🏠 **Valutare la tua casa** | Inserisci informazioni sulle dotazioni energetiche, come fotovoltaico, riscaldamento e isolamento, per ottenere un punteggio indicativo. |
| 🔧 **Simulare cambiamenti** | Esplora cosa succederebbe, secondo il modello dell'app, modificando infrastrutture o caratteristiche energetiche delle abitazioni. |
| 📊 **Confrontare scenari** | Osserva come cambiano gli indicatori nella simulazione, distinguendo la situazione di partenza da quella ipotetica. |

### 🧭 Un esempio concreto

Immagina di voler scoprire come potrebbe cambiare un comune con **più parchi e più piste ciclabili**.

1. Selezioni il comune dalla mappa.
2. Osservi il suo indicatore ambientale di partenza.
3. Passi alla modalità di simulazione e provi ad aggiungere nuove infrastrutture.
4. Confronti il risultato ipotetico con la situazione iniziale.

**Importante:** il risultato è una *simulazione dimostrativa*, non una previsione scientifica di quanto cambierà realmente l'inquinamento.

## 💚 Perché abbiamo creato VentO₂

I dati ambientali sono spesso disponibili, ma non sempre sono immediati da comprendere. Anche l'impatto delle scelte quotidiane può risultare astratto.

VentO₂ nasce per avvicinare **cittadini, studenti e curiosi** a questi temi attraverso tre idee:

- **Rendere visibile** lo stato del territorio con un'interfaccia esplorabile.
- **Rendere comprensibili** indicatori e concetti ambientali senza richiedere conoscenze tecniche.
- **Rendere immaginabile** il cambiamento, permettendo di sperimentare scenari alternativi.

Non vogliamo sostituire strumenti scientifici o valutazioni professionali: vogliamo rendere più accessibili le domande sulla sostenibilità.

## 🧪 Come funziona

VentO₂ combina informazioni territoriali e un **modello semplificato di valutazione ambientale**.

```text
Dati territoriali e ambientali
             │
             ▼
    Elaborazione degli indici
             │
             ▼
  Mappa e visualizzazione 3D
             │
       ┌─────┴─────┐
       ▼           ▼
  Esplorazione  Simulazione
       │           │
       └─────┬─────┘
             ▼
  Confronto degli scenari
```

L'**indice ambientale** è espresso su una scala da **0 a 100**: serve a rappresentare in modo sintetico le condizioni considerate dal modello. Il punteggio delle abitazioni è separato e dipende dalle dotazioni inserite.

Le modifiche nella modalità Scenario applicano regole e pesi dimostrativi, utili per esplorare ipotesi ma **non equivalenti a misurazioni reali**.

## 🛠️ Tecnologie utilizzate

| Tecnologia | A cosa serve |
| --- | --- |
| **React** | Costruire l'interfaccia dell'applicazione. |
| **TypeScript** | Rendere il codice più strutturato e controllabile. |
| **Vite** | Avviare e compilare il progetto. |
| **Three.js + React Three Fiber + Drei** | Creare e gestire la visualizzazione 3D. |
| **MapLibre GL** | Supportare la visualizzazione cartografica. |
| **Zustand** | Gestire lo stato dell'interfaccia. |
| **Vitest** | Eseguire i test automatici. |

## 🚀 Come avviare il progetto

### Requisiti

- **Node.js** e **npm** installati sul computer (preferibilmente una versione recente e compatibile con Vite 8).
- **Git** per clonare la repository.

### 1. Scarica il codice

```bash
git clone https://github.com/Alegott/hackathon.git
cd hackathon
```

### 2. Installa le dipendenze

```bash
npm install
```

### 3. Avvia l'app

```bash
npm run dev
```

Apri nel browser l'indirizzo mostrato nel terminale (di norma `http://localhost:5173`).

### Comandi utili

| Comando | Descrizione |
| --- | --- |
| `npm run dev` | Avvia l'ambiente di sviluppo. |
| `npm run build` | Controlla i tipi e prepara la versione di produzione. |
| `npm run preview` | Mostra in locale la versione compilata. |
| `npm run test` | Esegue i test automatici. |
| `npm run typecheck` | Controlla i tipi TypeScript. |

## 📁 Com'è organizzata la repository

```text
hackathon/
├── src/                 # Codice dell'applicazione
├── public/              # Risorse pubbliche
├── data/                # Materiale e dati di input
├── scripts/             # Script di supporto
├── docs/                # Documentazione aggiuntiva
├── dataset.json         # Dataset usato dal progetto
├── SPEC.md              # Specifica e obiettivi dell'MVP
├── TASKS.md             # Attività di sviluppo
├── package.json         # Dipendenze e comandi npm
└── README.md            # Questa guida
```

## 🔍 Dati e trasparenza

La trasparenza è importante, soprattutto quando si parla di ambiente.

- **Area di riferimento:** i comuni della provincia di Vicenza.
- **Informazioni territoriali:** il progetto prevede l'uso di confini comunali e infrastrutture derivate da fonti come ISTAT e OpenStreetMap.
- **Qualità dell'aria:** il modello descritto nella specifica considera dati e stime ambientali; disponibilità, copertura e periodo dipendono dal dataset effettivamente utilizzato.
- **Abitazioni dimostrative:** eventuali profili di esempio non devono essere interpretati come dati certificati di case reali.
- **Punteggi e scenari:** gli indici sono **indicativi**. Non sono certificazioni energetiche, misure ufficiali della qualità dell'aria o previsioni fisiche.
- **Aggiornamento dei dati:** non è garantito in tempo reale; i dati possono rappresentare una fotografia di un periodo precedente.

Per approfondire le ipotesi, i pesi e i limiti del modello, consulta [SPEC.md](SPEC.md).

## 🛣️ Evoluzione del progetto

VentO₂ nasce come **prototipo per hackathon**. La specifica del progetto distingue l'esperienza dimostrativa da idee per evoluzioni successive, tra cui:

- Esperienze social per condividere consigli e confrontarsi con altre persone.
- Missioni e riconoscimenti per incentivare comportamenti sostenibili.
- Possibili ampliamenti territoriali e miglioramenti nella qualità dei dati.

Queste sono **direzioni future**, non funzioni da considerare già disponibili.

## 🤝 Contribuire

Hai individuato un problema o hai un'idea per migliorare VentO₂? Puoi aprire una [issue](https://github.com/Alegott/hackathon/issues) oppure proporre una pull request.

Ogni suggerimento che renda le informazioni più **chiare, accessibili e corrette** è prezioso.

## 📄 Licenza

Il codice è distribuito sotto licenza [Apache 2.0](LICENSE). Per condizioni e dettagli, consulta il file `LICENSE` della repository.

---

<div align="center">

### 🌬️ VentO₂

**Il Veneto che respiri. Il futuro che scegli.**

*Perché il futuro del territorio comincia dal modo in cui impariamo a guardarlo.*

[⬆ Torna all'inizio](#️-vento₂)

</div>
