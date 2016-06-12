# mv (Move)

## Lesson Content

Viene usato per spostare e rinominare i file. È estremamente simile al comando cp in quanto a flag e funzionalità.

Puoi rinominare un file in questo modo:

<pre>$ mv vecchiofile nuovofile</pre>

Oppure puoi effettivamete spostarlo in una cartella differente:

<pre>$ mv file2 /home/pete/Documenti</pre>

E muovere più di un file per volta:

<pre>$ mv file_1 file_2 /unadirectory</pre>

Puoi usarlo anche per rinominare le directory:

<pre>$ mv directory1 directory2</pre>

Come per cp, se sposti o rinomini un file o una directory sovrascriverai ciò che si trova nella stessa directory con lo stesso nome. Puoi sempre usare il flag -i per ricevere un avviso prima di sovrascrivere qualsiasi cosa.

<pre>mv -i directory1 directory2</pre>

Diciamo che vuoi fare mv su un file per sovrascrivere il precedente. Puoi anche scegliere di creare un backup del vecchio file rinominandolo in automatico con il prefisso ~.

<pre>$ mv -b directory1 directory2</pre>

## Exercise

Rinomina un file, poi spostalo in una directory diversa da quella attuale.

## Quiz Question

Come rinomini un file di nome gatto in cane?

## Quiz Answer

mv gatto cane
