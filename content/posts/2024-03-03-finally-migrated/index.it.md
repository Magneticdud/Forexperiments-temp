+++
title = "Finalmente ho finito la migrazione"
date = 2024-03-03
author = "Magnetic_dud"
tags = [ "Sito"]
+++

Finalmente sono riuscito a terminare la migrazione da WordPress anche sul sito internazionale. Ho [impiegato più di un anno](/2023-02-14-new-platform) perché il vecchio host non supportava CloudFlare e quindi sono rimasto bloccato con WordPress 😅

Ora che tutto è statico e non c'è un posto dove fare il login, i bot possono continuare a divertirsi a fare il bruteforcing di /wp-admin con nomi utente inesistenti.

Inoltre, il mio server non ha più bisogno di rigenerare la stessa pagina più e più volte per ogni singolo utente che visita. Una volta pubblicato, non viene più ricalcolato niente, finito 😎.

Ma... ho notato che nell'ultimo anno lo sviluppatore del mio tema ha apportato alcune modifiche sostanziali, quindi potrei dover controllare attentamente cosa sta succedendo prima di approvare l'ultimo aggiornamento della versione. In particolare, le immagini con collegamenti ipertestuali non sono più supportate... spero di non averle mai usate in questo blog...
