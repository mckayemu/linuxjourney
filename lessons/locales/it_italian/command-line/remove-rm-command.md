# rm (Remove)

## Lesson Content

Credo che abbiamo creato troppi file, cancelliamone un po'. Per rimuovere dei file puoi usare il comand rm. Il comando rm (remove) viene usato per cancellare file e cartelle.

<pre>$ rm file1</pre>

Sii vigile quando usi rm, non c'è nessun magico cestino da cui ripescare i file rimossi. Una volta andati, sono andati per sempre, attento.

Fortunatamente abbiamo delle misure di sicurezza, in modo che il primo pinco pallo non possa cancellare per errore dei file importanti. I file protetti da scrittura chiederanno conferma prima di venire cancellati, e anche una directory protetta da scrittura non verrà rimossa così facilmente.

Se però non ti interessa nulla di tutto quello che ci siamo detti, puoi rimuovere definitivamente qualche file.

<pre>$ rm -f file1</pre>

-f o opzione “forza” dice a rm di cancellare tutti i file, che siano protetti da scrittura oppure no, senza chiedere nulla all'utente (a patto che abbiate sufficienti permessi sui file indicati).

<pre>$ rm -i file</pre>

Aggiungere il flag -i, come in molti altri comandi, vi notificherà sempre la scelta di cancellare oppure no i file o le directory selezionate.

<pre>$ rm -r directory</pre>

Il comando rm di base non vi consente di cancellare le cartelle, dovrete aggiungere il flag -r (ricorsivo) per rimuovere tutti i file e qualunque sottodirectory esso contenga.

Puoi rimuovere una directory con il comando rmdir.

<pre>$ rmdir directory</pre>

## Exercise

<ol>
<li>Crea un file chiamato -file (non scordare il trattino!).</li>
<li>Rimuovilo.</li>
</ol>

## Quiz Question

Come si cancella un file con nome myfile?

## Quiz Answer

rm myfile
