# alias

## Lesson Content

Ci sono volte in cui digitare comandi diventa monotono, o magari hai bisogno di digitare un lungo comando tante volte, e allora la cosa migliore è creare un alias. Per creare l'alias di un comando specifica semplicemente il nome dell'alias e impostalo con il comando che vuoi utilizzare.

<pre>$ alias foobar='ls -la'</pre>

D'ora in poi invece di digitare ls -la, puoi digitare foobar per eseguire quel comando, semplice. Tieni sempre bene a mente che questo comando terrà in memoria i tuoi alias fino riavvio del pc, mentre per creare un alias permanente devi aggiungerlo al file:

<pre>~/.bashrc</pre>

o file simili se vuoi persisterli dopo il riavvio.

Puoi rimuovere gli alias con il comando unalias:

<pre>$ unalias foobar</pre>

## Exercise

Crea un paio di alias e poi cancellali.

## Quiz Question

Che comando si usa per creare un alias?

## Quiz Answer

alias
