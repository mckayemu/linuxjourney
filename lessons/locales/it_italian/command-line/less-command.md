# less

## Lesson Content

Se stai cercando di visualizzare un file più grande delle righe del tuo monitor, come dicono gli inglesi, less is more. (Ironicamente, esiste un comando chiamato more che si comporta in modo simile.) Usando il comando less il testo viene impaginato e potrai navigarlo pagina dopo pagina.

Prova a guardare i contenuti di un file usando less. Una volta lanciato il comando, puoi usare degli altri comandi da tastiera per navigare il file.

<pre>$ less /home/pete/Documenti/testo1</pre>

I comandi che seguono servono a navigare un file con less:

<ul>
<li>q - Si usa per uscire dalla modalità di visualizzazione e ritornare alla shell.</li>
<li>Page up, Page down, Su e Giù - Naviga usando le frecce di direzione e i tasti page.</li>
<li>g - Spostati all'inizio del file.</li>
<li>G - Spostati alla fine del file.</li>
<li>/search - Puoi ricercare un frammento di testo all'interno del documento prefissando ogni termine che intendi cercare con il carattere /</li>
<li>h - Se hai bisogno di un po' di aiuto su come usare less mentre sei all'interno di less, usa help.</li>
</ul>

## Exercise

Lancia less su un file, poi prova a usare page up e page down per scorrerlo. Prova a ricercare una certa parola. Naviga rapidamente all'inizio e alla fine del file.

## Quiz Question

Come fai a chiudere l'esecuzione del comando less?

## Quiz Answer

q
