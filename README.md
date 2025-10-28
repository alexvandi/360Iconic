💍 360Iconic – Misuratore Digitale di Dita per E-Commerce di Anelli
360Iconic è un progetto commissionato da un cliente che aiuta i siti di e-commerce di gioielli a offrire ai propri utenti un modo semplice e preciso per misurare la dimensione delle dita direttamente online, prima di acquistare un anello.
Il sistema utilizza una visualizzazione interattiva a 360° e un’interfaccia intuitiva che guida l’utente passo-passo nella misurazione, migliorando l’esperienza d’acquisto e riducendo i resi dovuti a taglie errate.

⚙️ Funzionalità principali
📏 Misurazione precisa della circonferenza del dito tramite comparazione visiva o parametri noti
💍 Simulazione 3D dell’anello con vista a 360° sul dito
🖐️ Interfaccia interattiva che permette all’utente di ruotare, zoomare e regolare le proporzioni
🛍️ Facile integrazione nei siti e-commerce tramite iframe o modulo JavaScript
📱 Compatibilità mobile per consentire la misurazione anche da smartphone
🌐 Desig personalizzabile con colori, logo e font del brand del cliente

🔧 Installazione
Clona il repository:
git clone https://github.com/alexvandi/360Iconic.git
cd 360Iconic

Apri i file nel tuo editor o IDE preferito (es. VSCode)
Avvia un server locale per testare la demo:
python -m http.server 8000

Vai su http://localhost:8000 per aprire il progetto.

🚀 Utilizzo

Apri il file index.html
Segui le istruzioni a schermo per simulare la misurazione del dito
Inserisci la larghezza del dito (in mm) o confronta con un cerchio visuale interattivo
Il sistema calcola la taglia anello ideale in base alle tabelle internazionali (EU, US, UK)
Esempio di output:
Diametro: 18.5 mm  
Circonferenza: 58.1 mm  
Taglia EU: 18  
Taglia US: 8.25  

🧩 Architettura

Frontend: HTML5, CSS3, JavaScript (eventualmente Three.js per rotazione 3D)

Core Engine: Algoritmi di conversione mm ↔ taglia anello

UI: Comandi intuitivi per regolare e confrontare la misura

Configurazione Cliente: File JSON per personalizzare brand, colori, testi e tabelle taglie

🧪 Testing & Deployment

Testato su browser: Chrome, Edge, Safari, Firefox

Mobile responsive (iOS e Android)

Per il deploy basta caricare i file su un web host o integrare il modulo JS nel sito e-commerce

Facile embedding tramite:

<iframe src="https://tuosito.com/360Iconic" width="400" height="600"></iframe>

📄 Licenza

Questo progetto è rilasciato sotto licenza.
È consentito l’uso ma non è possibile modificarlo.
