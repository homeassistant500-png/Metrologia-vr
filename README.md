# Laboratorio di Metrologia – Meccatronica

Materiale didattico sugli strumenti di misura dell'officina meccanica: **calibro a nonio**, **micrometro per esterni** e **comparatore**.
Il repository contiene:
- un'**officina virtuale** per visore **Meta Quest 2**, utilizzabile anche su PC e LIM;
- tre **dispense interattive**, una per strumento, da usare su PC, LIM, tablet e smartphone.

| Contenuto | Apri |
|---|---|
| **Officina virtuale VR** – le tre postazioni di misura in 3D | [▶ Apri il laboratorio VR](https://homeassistant500-png.github.io/Metrologia-vr/) |
| **Dispensa interattiva – Calibro a nonio** | [▶ Apri](https://homeassistant500-png.github.io/Metrologia-vr/calibro-nonio.html) |
| **Dispensa interattiva – Micrometro per esterni** | [▶ Apri](https://homeassistant500-png.github.io/Metrologia-vr/micrometro-arco.html) |
| **Dispensa interattiva – Comparatore** | [▶ Apri](https://homeassistant500-png.github.io/Metrologia-vr/comparatore.html) |

---

## Dispense interattive

Ogni dispensa è organizzata in quattro sezioni:

| Sezione | Contenuto |
|---|---|
| **Lo strumento** | Disegno con le parti numerate e descritte, caratteristiche tecniche, buone pratiche di misura |
| **Il principio** | Funzionamento dello strumento con animazioni, formule, tabelle ed esempio di lettura guidato |
| **Simulatore** | Strumento da muovere con pulsanti, cursore, trascinamento o tastiera, per la spiegazione alla LIM |
| **Esercitazione** | Misure casuali su pezzi meccanici, verifica della risposta, soluzione passo per passo e tipo di errore |

### Calibro a nonio – `calibro-nonio.html`
- Nonio **1/10, 1/20, 1/50**, semplice e doppio; lente di ingrandimento regolabile.
- Principio del nonio passo per passo, formule (r = p/n, L = (γ·n − 1)·p, M = I + k·r) e tabella dei noni.
- Esercitazione su livelli Base, Intermedio, Avanzato e Personalizzato.
- Misure esterne, interne e di profondità su dado, perno, cuscinetto, alberino, vite, rondella, boccola e blocchetto con foro cieco.

### Micrometro per esterni – `micrometro-arco.html`
- Campi **0–25, 25–50, 50–75 mm**; centesimale (**0,01 mm**) e millesimale con nonio (**0,001 mm**).
- Vite micrometrica e nonio millesimale animati; dettaglio di bussola, tamburo e nonio.
- Esercitazione con diagnosi degli errori tipici: mezzo millimetro dimenticato, inizio del campo dimenticato, tamburo o nonio letti male.

### Comparatore – `comparatore.html`
- Analogico **0,01 mm** e **0,001 mm** (quadrante 0–100–0), digitale **0,01 / 0,001 mm**.
- Meccanismo a cremagliera e ingranaggi animato, azzeramento della ghiera, indici di tolleranza.
- Esercitazione con lettura diretta e misura per confronto con blocchetti di riscontro (H = Q + Δ) e verifica di conformità.

Tutte le dispense hanno il pulsante **☾ Scuro / ☀ Chiaro** e funzionano anche senza connessione, se aperte dal file scaricato.

---

## Officina virtuale VR – `index.html`

Officina meccanica in 3D con tornio, trapano a colonna, banco di aggiustaggio e tre postazioni di misura.
In ogni postazione ci sono:
- una **tavola** con il disegno ingrandito dello strumento;
- una **lente** sulla zona di lettura;
- una **console** con i comandi;
- un **leggio** con lettura, spiegazione e soluzione.

Ogni postazione ha la modalità **Simulatore** e la modalità **Esercitazione**, con la risposta inserita da tastierino e la verifica.

### Con il Meta Quest 2
1. Apri il **Browser Meta Quest** e vai all'indirizzo del laboratorio VR.
2. Premi **Entra in VR**.

| Comando | Azione |
|---|---|
| Grilletto puntando un pannello | Premi il pulsante |
| Grilletto puntando il pavimento | Teletrasporto |
| Levetta sinistra | Cammina |
| Levetta destra | Ruota a scatti di 30° |

All'ingresso il pannello di benvenuto porta direttamente alle tre postazioni. Dalla console di ogni postazione si passa alla successiva o si torna all'ingresso.

### Sul PC o sulla LIM
Apri l'indirizzo con Chrome o Edge e premi **Esplora sul PC**.

| Comando | Azione |
|---|---|
| Trascina con il mouse | Guarda intorno |
| W A S D o frecce | Muoviti |
| Clic | Premi i pulsanti |
| Pulsante **Menu** | Torna alla pagina iniziale |

---

## Requisiti
- **Dispense:** un browser aggiornato (Chrome, Edge, Firefox, Safari) su PC, LIM, tablet o smartphone.
- **Officina VR:** Meta Quest 2 (o altro visore compatibile WebXR) con il Browser Meta Quest, oppure un PC con Chrome o Edge. Serve la connessione a internet, perché la libreria 3D si carica all'avvio.

## Struttura del repository

| File | Contenuto |
|---|---|
| `index.html` | Officina virtuale VR con le tre postazioni |
| `calibro-nonio.html` | Dispensa interattiva sul calibro a nonio |
| `micrometro-arco.html` | Dispensa interattiva sul micrometro per esterni |
| `comparatore.html` | Dispensa interattiva sul comparatore |
| `README.md` | Questa descrizione |

## Crediti
- Progetto didattico del **Prof. Giuseppe Fumuso** – Meccatronica.
- Grafica 3D dell'officina realizzata con [three.js](https://threejs.org) (licenza MIT), caricata da CDN.

## Diritti d'uso
© 2026 Giuseppe Fumuso. Le condizioni d'uso sono indicate nel file `LICENSE`; se il file non è presente, tutti i diritti sono riservati.
Il logo personale dell'autore non può essere riutilizzato.
