## [Introduzione](accent://)  

Benvenuto nella mia guida su come effettuare il sideload su dispositivi Apple!  
Alcuni dei vantaggi di utilizzare questo metodo:  

- Gratis!  

- Senza PC!  

- Facile da usare!  

- Nessun limite alle app!  

- Firma direttamente sul dispositivo!  

- Nessuna preoccupazione per la privacy!  

- Configurazione in soli 5 minuti!  

- Le app rimangono per un massimo di 1 anno!  

- Compatibile con Scarlet/Feather/ESign/GBox  

Se hai problemi, richieste o idee, crea una segnalazione su GitHub o Discord.  

### [How does this method work?](accent://)  

Utilizzando certificati aziendali trapelati, possiamo firmare app usando le loro credenziali, il che significa che Apple ci consente di installare le app senza difficoltà. Tuttavia, dopo un po’ di tempo, Apple revoca il certificato, ma ciò può essere facilmente aggirato utilizzando questo metodo.  

### [Before we start](accent://)  

- Questo potrebbe non funzionare per te se hai utilizzato altri sideloaders aziendali, poiché i certificati potrebbero essere già revocati sul tuo dispositivo!  

- Se sei revocato, dovrai seguire la guida per i certificati revocati!  

- Questo metodo funzionerà fintanto che leggerai e seguirai tutti i passaggi correttamente!  

### [Compatibility](accent://)  

Questo metodo dovrebbe funzionare su tutti i dispositivi iOS e iPadOS con le ultime versioni di iOS. Non funziona per iOS 15 e versioni precedenti. La guida è compatibile con altri servizi di sideloading, a condizione che si basino su certificati aziendali per l'installazione.  

### [Privacy](accent://)  

Se hai dubbi sulla privacy riguardo al madNS Config Profile, crea una segnalazione su GitHub con la tua email, e ti invierò un invito per visualizzare le impostazioni. I log sono sempre disabilitati.  

Assicurati di menzionare esattamente il nome del profilo madNS:  

esempio:  

madNS Config Profile + Update Blocker  

Il WSF Config Profile non è un DNS, poiché reindirizza semplicemente i server Apple a https://localhost.direct, ovvero la tua rete locale. Nessuna preoccupazione per la privacy, puoi controllarlo tu stesso aprendo il profilo su un PC.  


### [FAQ](accent://)  

--  

Q - Posso usare un VPN?  

A - Sì, se utilizzi il madNS Config Profile. Assicurati di aver seguito la guida VPN.  

--  

Q - Un riavvio bypasserà tutto e revocherà le mie app?  

A - Alcuni utenti hanno notato che su dispositivi più vecchi, le app potrebbero essere revocate. Disattiva il WiFi e abilita la modalità Aereo quando riavvii o spegni il dispositivo.  

--  

Q - Servizi come AltStore, Sideloadly e Sidestore influenzeranno questa guida?  

A - No, i servizi elencati utilizzano la firma degli sviluppatori invece della firma aziendale, quindi puoi usarli tranquillamente! Tuttavia, per configurare SideStore sarà necessario utilizzare WireGuard. Assicurati di seguire la guida VPN.  

--  