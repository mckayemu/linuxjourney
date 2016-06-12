# pwd (Print Working Directory)

## Lesson Content

Ogni cosa su Linux è un file, e avventurandoti più in profondità nel mondo di Linux capirai meglio cosa intendo, per ora cerca solo di tenerlo bene a mente. Ogni file viene catalogato all'interno un albero gerarchico fatto di cartelle, anche dette directory. La prima directory del filesystem è ovviamente chiamata la directory di root (root = radice). La directory di root ha molte sottocartelle e file che a loro volta contengono file e sottocartelle, e così via. Ecco un esempio di come potrebbe apparire un albero delle directory:

<pre>/
|-- bin
|   |-- file1
|   |-- file2
|-- etc
|   |-- file3
|   `-- cartella1
|       |-- file4
|       `-- file5
|-- home
|-- var
</pre>

La posizione dei file e delle directory nel filesystem si chiama path. Se hai una cartella di nome home che contiene una cartella di nome pete, e la cartella di nome pete contiene a sua volta una cartella di nome Filmati, il path per raggiungere la cartella Filmati sarà: /home/pete/Filmati, semplice no?

Per navigare nel filesystem, come navigare nella vita reale, richiede di sapere dove ti trovi e dove stai andando. Per vedere dove sei ora puoi usare il comando pwd, il comando è l'abbreviazione della frase “print working directory” (stampa la cartella corrente) e mostra in quale directory ti trovi, nota come il path mostrato si origini dalla cartella di root.

<pre>$ pwd</pre>

Dove sei tu? Io dove mi trovo? Fai delle prove.

## Exercise

Niente esercizi per questa lezione.

## Quiz Question

Come faccio a sapere in quale directory mi trovo?

## Quiz Answer

pwd
