# Introduzione
Il presente bot Telegram nasce dall'esigenza di trovare in tempo reale ed istantaneamente la scuola più vicina alla nostra posizione. L'obiettivo è quello di fornire uno strumento facile ed efficace, utilizzabile dai cittadini, per ottenere un servizio veloce ed affidabile nella consultazione di archivi comunali per un servizio informativo migliore.
# Istruzioni per l'uso
Per usufruire del bot rechiamoci sull'app Telegram, dopo di che digitiamo nella barra di ricerca "Lab37100" e tra i risultati clicchiamo su "Scuole Verona".
Avviando il bot con il comando "/start" ci accoglie il messaggio di benvenuto che ci invita a inviare la nostra posizione. Inviandola riceveremo istantaneamente le informazioni sulla scuole, tra cui il nome, la distanza, l'indirizzo e il numero di telefono, seguiti dalla posizione geografica, utile per avviare il navigatore.
# Specifiche tecniche
Il codice sorgente è formato da due parti:  
1 - La prima parte si collega al database contenenti le informazioni sui parchi fornite dal Comune di Verona, e salva quest'ultime in locale su array. Questa scelta è stata
    effettuata al fine di evitare continue richieste al database ogni volta che un utente effettua una ricerca, rischiando di sovraccaricare il database di richieste. In questo
    modo invece viene svolto tutto in locale tramite array e funzioni, senza alcun coinvolgimento del database.  
2 - La seconda parte gestisce il bot vero e proprio. Infatti è configurato in modo da rispondere in base ai comandi inviati; in particolare inviando il comando "/start" ci dà il
    benvenuto nel bot, inviando la posizione ci restutuisce le informazioni sopra citate, e infine inviando un qualsiasi altro messaggio ci dirà che non è un comando valido.
# Crediti
Progetto sviluppato da Innovation Lab in collaborazione con Comune di Verona.
![WhatsApp Image 2021-07-30 at 15 20 14](https://user-images.githubusercontent.com/87977853/127863204-46d984eb-4025-479b-b6e6-4bd8f8e38c5c.jpeg)
