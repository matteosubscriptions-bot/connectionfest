# MICELIO · Ricerca sul panorama e decisioni per il sito

Data: 19 novembre 2026. Fonti: ricerche web (snippet dei motori di ricerca). **Limite dichiarato:** le pagine dei concorrenti non erano raggiungibili dalla sessione (dominio bloccato), quindi l'analisi dei siti è basata sugli estratti dei risultati di ricerca, non sulla lettura delle pagine. Posizionamento, struttura delle landing, tono e form dei concorrenti sono **non verificati**. I dati marcati con (anno ?) provengono da pagine senza data certa.

## 1. Cosa esiste (FATTI dagli estratti)

| Tipo | Esempio | Formato | Prezzo osservato |
|---|---|---|---|
| Forest bathing, formazione guide | CSEN, Oasi Zegna (Alpi) | 2 giorni, escursioni, pasti inclusi, diploma | 195 € (anno ?) |
| Forest bathing, formazione professionisti | Chiusa Pesio (CN), 2026 | 16 h in natura + 16 h online | non trovato |
| Forest bathing, esperienza | Trentino, Val di Fassa | 2-3 h | da 15 € |
| Bushcraft / sopravvivenza | Freedome, Appennino tosco-romagnolo, La Spezia | weekend 2 giorni, bivacco | non trovato |
| Ecopsicologia | Ecopsiché (Osnago), Panta Rei (Trasimeno) | laboratori, formazione annuale; seminario | 74 € (seminario, 2017) |
| Permacultura | PDC residenziale 72 h (Pavia, Alta Langa, Roma) | 12-13 giorni | 450-600 € (anno ?) |
| Rewilding / riconnessione | "Re-Forestoration", Varese | weekend 2 giorni | non trovato |
| Natura + ecologia, estero | Dartington (ex Schumacher), "Soulful Connection with Trees" | weekend | 290 £ / 410 £ con alloggio (2024) |
| Benessere in natura, estero | Field Studies Council "Wellbeing in Nature weekend" | weekend | 265-350 £ (2027) |
| Nature connection, estero | Wilderness Awareness School (USA) | weekend con Jon Young | 295 $; percorso annuale 14.950 $ (2024-25) |
| Rituali di riconnessione | Work That Reconnects (Macy), Council of All Beings (Seed, Macy, 1985-86) | workshop | variabile |

Non trovati in Italia: corsi che usano il nome "Micelio" come corso esperienziale; formatori italiani di Coyote Mentoring / 8 Shields; offerte residenziali a più weekend con un percorso strutturato per adulti non professionisti.

## 2. Spazio libero (INFERENZA, da validare)

Le offerte italiane trovate si dividono in: (a) avventura/bushcraft, (b) esperienze brevi di forest bathing, (c) formazioni per professionisti, (d) ecopsicologia datata. Un **arco in due tempi con sperimentazione intermedia, rivolto a adulti curiosi senza prerequisiti, che mette al centro le relazioni ecologiche**, non compare negli estratti. È un'ipotesi: la ricerca era superficiale e le offerte locali spesso non sono indicizzate.

Benchmark prezzo per weekend (solo orientativo, non una raccomandazione): 195 € (CSEN), 290-410 £ (Dartington), 265-350 £ (FSC), 295 $ (WAS). Il costo per MICELIO va deciso a partire dai costi reali; il sito oggi lo dichiara "in definizione".

## 3. Evidenza scientifica rilevante

- **A favore del formato in due tempi:** una meta-analisi sugli adulti (Sheffield, Butler, Richardson 2022) trova un effetto medio degli interventi sulla connessione alla natura. Un lavoro citato (Barragan-Jason et al.) riporta che solo gli interventi più lunghi producono guadagni a due settimane o più. Le pratiche regolari e ripetute sono quelle seguite da misure di follow-up. Questo sostiene il periodo di sperimentazione tra i due weekend.
- **Limiti:** gli estratti non mostrano evidenza che questi interventi cambino i comportamenti a lungo termine; il legame connessione→comportamento è per lo più correlazionale. Gran parte delle fonti viene dallo stesso gruppo di ricerca (Derby). Per questo il sito **non promette trasformazione** e mantiene la frase del copy originale ("non possiamo promettere...", qui resa come "piccoli gesti").
- **Rischio sul "micelio":** la revisione di Karst, Jones e Hoeksema (Nature Ecology & Evolution, 2023) sostiene che le affermazioni più popolari sulla "wood wide web" sono in gran parte slegate dalle prove; Simard contesta. Il copy usa il micelio come "immagine" dell'interconnessione, formulazione difendibile. **Evitare** sul sito e dal vivo frasi come "gli alberi si parlano / si scambiano nutrienti per aiutarsi".

## 4. Decisioni di progetto che ne derivano

1. **Identità**: riconnessione e appartenenza (come nel copy); niente tono da corso di sopravvivenza, né da ritiro spirituale.
2. **Un solo obiettivo della pagina**: raccogliere manifestazioni di interesse. Il pulsante ripete lo stesso invito in alto, nell'apertura, sulla barra fissa mobile e nel modulo.
3. **Trasparenza su ciò che manca**: luogo e costo sono "da definire" e visibili, per ridurre il sospetto tipico di un pre-lancio.
4. **Modulo a basso attrito**: obbligatori solo nome, email e consenso; le tre domande di mercato sono facoltative. Le risposte servono a decidere formato, pernottamento e pagamento.
5. **Contenuto visivo**: nessuna foto disponibile, quindi illustrazione vettoriale (luce nel bosco, rete di fili). Gli slot per le foto indicate nel brief (bosco, sottobosco, attività, persone) vanno riempiti con immagini reali.

## 5. Da fare prima di pubblicare (decisioni di Matteo)

- Impostare `CONFIG.endpoint` in `index.html` (Formspree, Netlify Forms, Google Apps Script o altro). Finché è vuoto il modulo dichiara onestamente che l'invio non è attivo.
- Informativa privacy e titolare del trattamento (GDPR): il consenso nel modulo è presente, il testo no.
- Verificare disponibilità del nome "MICELIO" (dominio, marchio, social). Non è un controllo legale: nessun corso omonimo trovato, ma la ricerca è superficiale.
- Sostituire l'illustrazione con fotografie reali, o mantenerla.
