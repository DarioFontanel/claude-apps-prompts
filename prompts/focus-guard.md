# ⏱️ Focus Guard

Timer Pomodoro che durante le sessioni di lavoro chiude le schede di Instagram e degli altri siti scelti, con statistiche e riepilogo di fine giornata.

**Prima dell'invio** — sostituisci i segnaposto `[Mac / Windows]` e `[Chrome / Safari / Edge / Arc]` con il tuo sistema operativo e il tuo browser. Il prompt chiede a Claude di verificare la fattibilità e i permessi necessari prima di costruire l'app.

```text
Costruiscimi un artifact che voglio installare come app desktop con "Install as app". Si chiama "Focus Guard". È un timer Pomodoro che durante le sessioni di lavoro chiude automaticamente le schede di Instagram (e altri siti che sceglierò).

PRIMA DI COSTRUIRE: verifica e dimmi chiaramente se e come è fattibile sul mio sistema operativo con l'accesso completo al computer di "Install as app" (esecuzione di programmi/script). Il mio sistema è: [Mac / Windows] e uso il browser: [Chrome / Safari / Edge / Arc]. Spiegami quali permessi dovrò concedere (anche quelli del sistema operativo, es. Automazione su macOS) e i limiti. Se non è fattibile in modo affidabile, proponi il piano B migliore.

Timer Pomodoro:
- Sessioni lavoro 25 min / pausa 5 min / pausa lunga 15 min ogni 4 sessioni, tutte configurabili.
- Campo "Su cosa stai lavorando?" all'inizio di ogni sessione.
- Finestrella compatta sempre in primo piano con il conto alla rovescia, espandibile.
- Notifiche a inizio e fine sessione.
- Scorciatoia globale (es. Cmd/Ctrl+Shift+P) per avviare/mettere in pausa.
- Icona nella barra dei menu / tray con il tempo rimanente.

Blocco siti:
- Lista siti bloccati modificabile, di default: instagram.com, facebook.com, tiktok.com, youtube.com/shorts.
- SOLO durante le sessioni di lavoro (non nelle pause), ogni 2-3 secondi controlla la scheda attiva del browser; se è un sito bloccato, la chiude.
- Approccio preferito su Mac: AppleScript via osascript per leggere l'URL della scheda attiva e chiuderla. Su Windows: controllo del titolo della finestra attiva e chiusura della scheda con Ctrl+W, o l'alternativa più affidabile che conosci.
- Quando chiude una scheda mostra una notifica ironica e motivante (es. "Instagram può aspettare. Mancano 14 minuti.") e conta i tentativi.
- Interruttore "Blocco attivo" per disattivarlo.

Statistiche:
- Sessioni completate oggi e questa settimana, minuti di focus, numero di tentativi bloccati per sito.
- A fine giornata, un breve riepilogo scritto da Claude con un commento sulla giornata (tono simpatico, non giudicante).
- Dati salvati tra un'apertura e l'altra.

Design: pulito, colori calmi, conto alla rovescia grande e ben leggibile, tema chiaro e scuro.
```
