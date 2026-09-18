# Noia Zero 🎮

Mini-giochi rapidi da un dito, pensati per i momenti noiosi: fila alla posta, metro, sala d'attesa.
Tutto in un unico file HTML, **funziona offline** (PWA con service worker), nessun account, nessuna rete.

## Come si gioca
- **GIOCA** — sfida infinita: i 7 minigiochi arrivano a caso, sempre più veloci. Hai 3 vite.
- **ALLENAMENTO** — ti alleni su un singolo minigioco.
- Punti = 10 base + bonus velocità (fino a +20) + bonus combo. Record salvati sul telefono.

## I minigiochi
| | Minigioco | Cosa fare |
|---|---|---|
| 🎯 | Bersaglio | Tocca il cerchio, schiva le bombe |
| 🎨 | Colore | Tocca il **colore dell'inchiostro**, non la parola |
| ➗ | Calcolo | Risolvi l'operazione al volo |
| 🔢 | Conta | Quante emoji di quel tipo vedi? |
| 🧠 | Memoria | Ripeti la sequenza luminosa |
| 🔍 | Intruso | Trova l'emoji diversa nella griglia |
| 🚦 | Riflessi | Tocca **solo** quando diventa verde |

## Installazione sul telefono
Apri la pagina nel browser → menu → *Aggiungi alla schermata Home*.
Dopo la prima apertura funziona anche in modalità aereo.

## Sviluppo
File statici, nessuna dipendenza:
`python3 -m http.server 8000` e apri `http://localhost:8000/noia-zero/`.
