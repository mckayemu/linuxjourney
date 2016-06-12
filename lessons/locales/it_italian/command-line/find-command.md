# find

## Lesson Content

Con tutti i file che abbiamo sul sistema trovarne uno specifico diventa un'impresa. Abbiamo però un comando che ci aiuta, find!

<pre>$ find /home -name gattini.jpg</pre>

Con find devi specificare la directory in cui eseguire la ricerca e cosa stai cercando, in questo caso stiamo cercando nella cartella /home un file di nome gattini.jpg.

Puoi anche aggiungere il tipo di file che stai provando a cercare.

<pre>$ find /home -type d -name UnaCartella</pre>

Noterai che ho impostato il tipo di file che voglio cercare come (d) per ricercare una directory e sto cercando tutte le cartelle con nome UnaCartella.

Una delle cose fantastiche è che find non si ferma alla directory che hai indicato, cercherà all'interno di tutte le sottodirectory che la directory di base contiene e nelle loro sottodirectory.

## Exercise

<ol>
<li>Cerca un file il cui nome contiene la parola net partendo dalla directory di root.</li>
</ol>

## Quiz Question

Che opzione devi usare per esplicitare che vuoi una ricerca per nome?

## Quiz Answer

-name
