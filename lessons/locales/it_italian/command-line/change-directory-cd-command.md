# cd (Change Directory)

## Lesson Content

Ora che sai capire dove ti trovi, vediamo come muoverci un po' per il filesystem. Ricorda che navigheremo sempre utilizzando i path. Abbiamo due metodi per specificare un path, path assoluti e path relativi.

<ul>
<li>Path assoluto: è il percorso dalla cartella di root. La root è cartella principale. La directory di root è sempre indicata dal simbolo slash ”/”. Ogni volta che il tuo path comincia con / significa che stai iniziando con la cartella di root. Per esempio, /home/pete/Desktop.</li>

<li>Path relativo: è il percorso rispetto al punto del filesystem in cui ti trovi ora. Se, per esempio, mi trovassi nella cartella /home/pete/Documenti e volessi portarmi nella directory tasse/ che si trova all'interno di Documenti, non dovrei specificare tutto il percorso dalla cartella di root scrivendo /home/pete/Documenti/tasse, ma potrei indicare soltanto tasse/.</li>
</ul>

Adesso che hai capito come funzionano i percorsi, ci manca soltanto qualcosa che ci aiuti ad andare nella la cartella che vogliamo. Per fortuna, il comando cd ”cambia directory” è qui con noi.

<pre>$ cd /home/pete/Immagini</pre>

Con questo ho cambiato la cartella in cui mi trovo in /home/pete/Immagini.

All'interno di questa cartella ne ho un'altra che si chiama Hawaii, posso navigarci dentro con:

<pre>$ cd Hawaii</pre>

Hai notato che ho utilizzato soltanto il nome della cartella? Questo perché mi trovavo già all'interno di /home/pete/Immagini.

Può diventare stancante navigare soltanto tramite path relativi e assoluti, fortunatamente esistono alcuni shortcut in grado di aiutarci.

<ul>
<li>. (directory corrente). Rappresenta la directory in cui ti trovi. </li>
<li>.. (directory superiore). Ti porta nella directory di livello superiore a quella corrente.</li>
<li>~ (directory home). Contiene sempre per default la tua ”directory home.” Nel mio caso /home/pete.</li>
<li>- (directory precedente). Ti porterà nella directory precedente a quella in cui ti trovi adesso.</li>
</ul>

<pre>$ cd .
$ cd ..
$ cd ~
$ cd -
</pre>
Prova a usarli!

## Exercise

<ol>
<li>Lancia il comando cd senza nessun argomento, dove ti trovi ora?</li>
</ol>

## Quiz Question

Se ti trovi in /home/pete/Immagini e volessi andare in /home/pete, quale shortcut dovresti usare?

## Quiz Answer

cd ..
