# ls (List Directories)

## Lesson Content

Adesso che sappiamo come muoverci nel sistema, come facciamo a capire cosa c'è a disposizione? Ora come ora è come navigare al buio. Possiamo usare il fantastico comando ls per elencare i contenuti di una cartella. Il comando ls elencherà directory e file nella directory corrente come default, ma puoi specificare per quale percorso vuoi elencare le directory.

<pre>$ ls
$ ls /home/pete</pre>

ls è uno strumento parecchio utile, può mostrare anche delle informazioni di dettaglio dei file e delle directory che stai osservando.

Nota anche che non tutti i file sono visibili. I file che cominciano con . vengono nascosti, ma puoi visualizzarli comunque tramite il comando ls aggiungendoci il flag -a (a sta per all, ossia tutti).

<pre>$ ls -a</pre>

C'è anche un'altro utilissimo flag di ls, -l per lungo, che mostra una lista dettagliata di file e directory in formato esteso. Con l'opzione puoi vedere informazioni dettagliate, iniziando da sinistra: file o directory, permessi del file, numero di link, nome del proprietario, gruppo di appartenenza, dimensione del file, orario e data dell'ultima modifica (timestamp), nome del file o della directory.

<pre>$ ls -l</pre>

<pre>pete@icebox:~$ ls -l
total 80
drwxr-x--- 7 pete penguingroup   4096 Nov 20 16:37 Desktop
drwxr-x--- 2 pete penguingroup   4096 Ott 19 10:46 Documenti
drwxr-x--- 4 pete penguingroup   4096 Nov 20 09:30 Downloads
drwxr-x--- 2 pete penguingroup   4096 Ott  7 13:13 Musica
drwxr-x--- 2 pete penguingroup   4096 Set 21 14:02 Immagini
drwxr-x--- 2 pete penguingroup   4096 Lug 27 12:41 Public
drwxr-x--- 2 pete penguingroup   4096 Lug 27 12:41 Templates
drwxr-x--- 2 pete penguingroup   4096 Lug 27 12:41 Filmati</pre>

I comandi usano delle cose chiamate flag (note anche come argomenti o opzioni, come preferisci chiamarle) per aggiungere più funzionalità. Guarda come ho aggiunto -a e -l, puoi anche aggiungerle assieme come -la. L'ordine dei flag determina come le funzioni devono essere applicate. Nella maggior parte dei casi l'ordine non modifica il risulatto e perciò puoi scrivere -al ottenendo lo stesso effetto.

<pre>$ ls -la</pre>

## Exercise

Lancia ls con flag diversi per vederne l'effetto a video.

## Quiz Question

Che comando usi per vedere i file nascosti?

## Quiz Answer

ls -a
