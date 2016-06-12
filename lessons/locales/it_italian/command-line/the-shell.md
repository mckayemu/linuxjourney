# The Shell

## Lesson Content

Il mondo è nelle tue mani, o quantomeno per le mani ora hai una shell. Cos'è una shell? La shell è essenzialmente un programma che riceve i tuoi comandi da tastiere e li invia al sistema operativo per l'esecuzione. Se hai mai utilizzato un'interfaccia grafica, probabilmente avrai anche avuto l'occasione di vedere programmi come “Terminale”, “Console” o “Prompt dei comandi,” che non sono altro che programmi che lanciano una shell per te. Durante tutto questo corso impareremo le meraviglie della shell.

Durante il corso useremo il programma shell bash (Bourn Again shell), in pratica tutte le distribuzioni Linux usano la shell bash come shell predefinita. Esistono altre shell come la ksh, zsh, tsch, ma non le vedremo durante il corso.

Tuffiamoci! A seconda della distribuzione che usi il prompt della tua shell potrebbe cambiare, ma per la maggior parte dovrebbe aderire a questo formato:
<pre>username@hostname:cartella_corrente $
pete@icebox:/home/pete $</pre>

Hai notato il carattere dollaro “$” alla fine del prompt? Shell diverse avranno prompt diversi, nel tuo caso il $ indica un utente comune che utilizza Bash, Bourne or Korn shell. Non serve aggiungere il simbolo di prompt quando digiti il comando, sappi però che è sempre presente.

Cominciamo con un comando semplice, echo. Il comando echo stampa a video gli argomenti testuali inseriti a destra del comando.

<pre>$ echo Hello World</pre>

## Exercise

Prova a usare altri comandi Linux e guarda che cosa stampano:

<ol>
<li>$ date</li>
<li>$ whoami</li>
</ol>

## Quiz Question

Cosa viene stampato a video quando digiti echo Hello World?

## Quiz Answer

Hello World
