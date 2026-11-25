# ✅ Cattura

Finestra di cattura rapida, richiamabile con una scorciatoia globale, che trasforma una frase libera in un task strutturato con scadenza, priorità e progetto.

**Opzionale** — un connettore calendario collegato, per tenere conto delle riunioni nella pianificazione della giornata.

```text
Costruiscimi un artifact che voglio installare come app desktop con "Install as app". Si chiama "Cattura".

Cosa deve fare:
- Una finestrella minimale che si apre con una scorciatoia globale (es. Cmd/Ctrl+Shift+Spazio) sopra qualsiasi app, come Spotlight.
- Scrivo una frase libera, es. "chiamare Marco per il preventivo entro venerdì, urgente". Premo Invio e si chiude.
- Claude la trasforma in un task strutturato: titolo pulito, scadenza (calcolata dalla data di oggi), priorità (alta/media/bassa), progetto/categoria dedotto, eventuale persona coinvolta.
- Vista principale: lista dei task raggruppati per "Oggi", "Questa settimana", "Più avanti", "Senza data". Spunta per completare, modifica inline, trascina per riordinare.
- I task devono restare salvati tra un'apertura e l'altra.
- Ogni giorno alle 18:00 una notifica con il riepilogo: cosa ho completato, cosa resta aperto, e un suggerimento di Claude sulle 3 cose da fare domattina per prime.
- Bottone "Pianifica la mia giornata": Claude guarda i task aperti e propone un ordine con stima dei tempi.

Funzioni da app installata:
- Scorciatoia globale per la cattura rapida.
- Icona nella barra dei menu / tray con il numero di task di oggi.
- Finestra di cattura sempre in primo piano quando aperta.
- Notifiche.

Extra opzionale: se ho un connettore calendario collegato, nel "Pianifica la mia giornata" tieni conto delle riunioni già fissate.

Design: veloce e leggero, stile app nativa, tema chiaro e scuro, testi grandi e ben leggibili.
```
