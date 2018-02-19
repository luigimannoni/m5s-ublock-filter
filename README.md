# m5s-ublock-filter
Il primo filtro honesto, che vanta rating a 5 stelle ⭐⭐⭐⭐⭐ su Tripadvisor, AirBnb e Gnoccatravel

## Cosa é
Questo é un filtro cosmetico per l'estensione uBlock Origin (con supporto Adblock) per filtrare automaticamente tutti i commenti cancerogeni pro-5stelle ed i share di pagine di "contro informazione" con titoloni sensazionalistici.

## Perché
Purtroppo perché laggente™ nun se regola sui social media e io sto diventando vecchio, insofferente e burbero; non ho piú voglia di dover scrollare file di commenti "politici" su post che magari nulla hanno a che fare con l'argomento iniziale.

Il problema dei social media, facebook in primis, é la mancanza di moderazione attiva. Vengo da una generazione dove le chat e message board erano (e sono tutt'ora per fortuna) moderate, dove l'OT viene punito, dove si hanno strumenti per allontanare le persone non piú gradite.

Quindi se anche tu ti sei rotto le palle di dover leggere "Quindi hanno inventato l'elettore del PD" sotto un articolo di una qualsiasi testata nazionale intitolato "Creato il primo embrione uomo-maiale" questo é il filtro che fa per te.

## Ma facebook ha giá la funzione blocca o nascondi!

Piú che giusto, questo filtro peró é nato con l'idea di centralizzare una lista di profili e pagine "tossiche". 

## Come funziona?
Semplicemente tramite le estensioni uBlock/Adblock, scaricabili dal tuo browser. Dopo aver installato la tua estensione preferita apri le impostazioni e aggiungi `https://raw.githubusercontent.com/luigimannoni/m5s-ublock-filter/master/filter-list.txt`  alla lista dei filtri Custom.

Al momento il filtro aggiunge solo una semplicissima wordlist di parole proibite nei commenti, l'estensione penserá al resto rimuovendo il commento dal browser. Nella roadmap il filtro verrá probabilmente cambiato per targettare user ID specifici invece di una wordlist generica.   

## Come posso contribuire?
Nel modo piú semplice: aprendo una [issue](https://github.com/luigimannoni/m5s-ublock-filter/issues) linkando la tua pagina preferita di bufale, oppure se hai un profilo da segnalare link al profilo incriminato, é comunque necessaria una revisione prima di includere un profilo nella blacklist.

Se ti vuoi sbattere di piú e sai come usare git, forka questa repo e crea una pull request con le tue modifiche 
