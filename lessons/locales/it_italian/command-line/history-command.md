# history

## Lesson Content

Nella tua shell viene mantenuta la storia dei comandi che hai digitato in precedenza, puoi anche visualizzare quella lista. Si rivela utile quando vui cercare e lanciare un comando che hai usato prima senza doverl digitare di nuovo.

<pre>$ history</pre>

Se vuoi lanciare lo stesso comando cha hai lanciato poco fa, premi la freccia verso l'alto ⇧.

Vuoi lanciare lo stesso comando senza doverlo digitare di nuovo? Usa !!. Se hai lanciato cat file1 e vuoi eseguirlo di nuovo, puoi scrivere semplicemente !! ed eseguirai l'ultimo comando che avevo lanciato.

Un'altra scorciatoia da tastiera è ctrl-R, che rappresenta il comando di ricerca inversa. Se premi ctrl-R e inizi a digitare parti del comando che vorresti vedrai comparire dei risultati che potrai navigare premendo di nuovo ctrl-R. Una volta trovato il comando che volevi recuperare, premi il tasto invio ⏎.

Il nostro terminale ora è pieno di scritte no? Facciamo pulizia, usa il comando clear per pulire tutto quanto.

<pre>$ clear</pre>

Molto meglio, no?

Dato che il tema sono le funzioni utili, una tra le più utili per qualunque ambiente da linea di comando è il completamento automatico. Se stai digitando l'inizio di un comando, un file o una directory e premi il tasto Tab ⇥, la shell autocompleterà la parola basandosi su ciò che trova nella directory corrente a patto che non abbiate più file o directory che cominciano nello stesso modo. Per esempio se cerchi il comando chrome, puoi cominciare a digitare chr e premere Tab ⇥ per vederlo completarsi automaticamente nella parola chrome.

## Exercise

Naviga attraverso la storia dei comandi precedenti usando le frecce su e giù. Prova anche a cercare un comando usando la funzione di ricerca inversa ctrl-R. 

## Quiz Question

What is the command to clear the terminal?

## Quiz Answer

clear
