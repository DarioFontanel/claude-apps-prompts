# 📂 Chiedi al Team

App per interrogare in linguaggio naturale i documenti di un team (PDF, fogli, documenti) e ottenere risposte con la fonte citata.

**Requisito** — il connettore Google Drive collegato al tuo account Claude, oppure una cartella locale a cui l'app ha accesso.

```text
Costruiscimi un artifact che voglio installare come app desktop con "Install as app". Si chiama "Chiedi al Team".

A cosa serve: in un piccolo team le informazioni sono sparse tra documenti, PDF e fogli. Voglio un'app dove si fa una domanda in linguaggio naturale e si ottiene una risposta presa dai nostri documenti, con la fonte.

Cosa deve fare:
- Fonte dei documenti: una cartella condivisa tramite il mio connettore Google Drive (o, in alternativa, una cartella locale sul computer se l'app ha l'accesso). Fammi scegliere la cartella all'inizio.
- Campo di domanda tipo chat, es. "che prezzo abbiamo fatto a Rossi Srl l'anno scorso?" o "qual è la procedura per i rimborsi spese?".
- Claude cerca nei documenti e risponde in modo breve, citando SEMPRE il documento (nome file + link o percorso) e il passaggio da cui ha preso l'informazione.
- Se la risposta non è nei documenti, lo dice chiaramente invece di inventare.
- Cronologia delle domande recenti e una sezione "Domande frequenti" dove posso fissare le risposte più utili per il team.
```
