# claude-apps-prompts

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)
[![Claude](https://img.shields.io/badge/Claude-Install_as_app-d97757)](https://support.claude.com/it/articles/18516354-installa-un-artefatto-come-app)
[![Piattaforme](https://img.shields.io/badge/macOS_%7C_Windows-desktop-555555)](https://support.claude.com/it/articles/10065433-installa-claude-desktop)

**claude-apps-prompts** è una raccolta di quattro prompt che ti permette di costruire in Claude altrettante app desktop, installabili su Mac e Windows con la funzione «Installa come app». Ogni prompt descrive l'app completa, dalle funzioni principali a quelle da app installata, ed è pronto da incollare in una chat.

---

## Le quattro app

**📂 [Chiedi al Team](./prompts/chiedi-al-team.md)** — interroga in linguaggio naturale i documenti del team su Google Drive e risponde citando sempre il documento di origine.

**⏱️ [Focus Guard](./prompts/focus-guard.md)** — timer Pomodoro che, durante le sessioni di lavoro, chiude le schede di Instagram e degli altri siti scelti.

**✍️ [Riscrivi](./prompts/riscrivi.md)** — legge un testo dagli appunti e ne propone sei varianti di tono e formato, da copiare con un clic.

**✅ [Cattura](./prompts/cattura.md)** — cattura una frase libera con una scorciatoia globale e la trasforma in un task con scadenza, priorità e progetto.

---

## Prerequisiti

**Claude Desktop** — l'app per Mac o Windows, versione 6.28899.0 o successiva. La funzione è disponibile solo nell'app desktop: le scorciatoie «Aggiungi al Dock» o «Aggiungi alla schermata Home» del browser non offrono le stesse funzionalità.

**Piano Claude** — la funzione è in beta sui piani Free, Pro, Max, Ultra, Team ed Enterprise. Sui piani Team ed Enterprise deve essere attivata da un owner dell'organizzazione.

**Connettori** — Chiedi al Team usa il connettore Google Drive; Cattura usa un connettore calendario, se presente. Entrambi si collegano dalle impostazioni del tuo account Claude.

---

## Utilizzo

1. Apri il file del prompt in `prompts/` e copia il blocco di testo.
2. Incollalo in una nuova chat di Claude Desktop e invialo. Per Focus Guard sostituisci prima i segnaposto del sistema operativo e del browser.
3. Quando l'artefatto è pronto, aprilo nella finestra principale di Claude Desktop e seleziona «Installa come app» dal suo menu, poi conferma.
4. Apri l'app dalla cartella **Claude Apps**: su macOS si trova nella cartella Applicazioni della tua home, su Windows nel menu Start.

Verifica: l'app si apre in una finestra propria, con la sua icona nel Dock o nella barra delle applicazioni.

Se «Installa come app» non compare, aggiorna Claude Desktop: su macOS da **Claude > Controlla aggiornamenti**, su Windows dal menu (☰) **Guida > Controlla aggiornamenti**.

Per disinstallare un'app: in Claude Desktop apri **File > App**, seleziona l'app e scegli «Disinstalla». L'artefatto resta nella chat e si può reinstallare.

Riferimento: [Installa un artefatto come app](https://support.claude.com/it/articles/18516354-installa-un-artefatto-come-app), guida ufficiale Anthropic.

---

Designed by **[Dario Fontanel, PhD](https://dariofontanel.com/)**

*Aiuto PMI italiane ad integrare l'intelligenza artificiale per automatizzare i lavori ripetitivi, abbattere i costi e guadagnare tempo per crescere.*

[![Sito](https://img.shields.io/badge/Sito-dariofontanel.com-4285F4?style=flat&logo=googlechrome&logoColor=white)](https://dariofontanel.com/)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=flat&logo=youtube&logoColor=white)](https://www.youtube.com/@dariofontanel)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat&logo=instagram&logoColor=white)](https://www.instagram.com/dariofontanel.ai/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2MtMS4xNDQgMC0yLjA2My0uOTI2LTIuMDYzLTIuMDY1IDAtMS4xMzguOTItMi4wNjMgMi4wNjMtMi4wNjMgMS4xNCAwIDIuMDY0LjkyNSAyLjA2NCAyLjA2MyAwIDEuMTM5LS45MjUgMi4wNjUtMi4wNjQgMi4wNjV6bTEuNzgyIDEzLjAxOUgzLjU1NVY5aDMuNTY0djExLjQ1MnpNMjIuMjI1IDBIMS43NzFDLjc5MiAwIDAgLjc3NCAwIDEuNzI5djIwLjU0MkMwIDIzLjIyNy43OTIgMjQgMS43NzEgMjRoMjAuNDUxQzIzLjIgMjQgMjQgMjMuMjI3IDI0IDIyLjI3MVYxLjcyOUMyNCAuNzc0IDIzLjIgMCAyMi4yMjUgMHoiLz48L3N2Zz4%3D)](https://www.linkedin.com/in/dario-fontanel/)
[![TikTok](https://img.shields.io/badge/TikTok-000000?style=flat&logo=tiktok&logoColor=white)](https://www.tiktok.com/@dario.fontanel)
[![AI Academy](https://img.shields.io/badge/AI_Academy-E7514F?style=flat&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMiAzIDEgOWwxMSA2IDktNC45MVYxN2gyVjlMMTIgM3pNNSAxMy4xOFYxN2MwIDEuNjYgMy4xMyAzIDcgM3M3LTEuMzQgNy0zdi0zLjgybC03IDMuODItNy0zLjgyeiIvPjwvc3ZnPg%3D%3D)](https://www.skool.com/ai-academy-2306)

Licenza [MIT](./LICENSE).
