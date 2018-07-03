# Ejerskabstilladelser

## Lektionsindhold

Ud over at ændre tilladelser på filer, kan du også ændre gruppen og bruger ejerskabet af filen.

<b>Rediger brugerejerskab</b>

<pre>$ sudo chown patty myfile</pre>

Denne kommando vil sætte ejeren af myfile til patty.

<b>Rediger gruppeejerskab</b>

<pre>$ sudo chgrp whales myfile</pre>

Denne kommando sætter gruppen for myfile til whales.

<b>Rediger både bruger og gruppe ejerskab på samme tid</b>
Hvis du tilføjer et kolon og gruppenavn efter brugeren, kan du indstille både brugeren og gruppen på samme tid.

<pre>$ sudo chown patty:whales myfile</pre>

## Øvelse

Rediger gruppen og brugeren af nogle testfiler. Bagefter tag et kig på tilladelserne med ls -l.

## Quiz Spørgsmål

Hvilken kommando bruger du til at ændre bruger ejerskab?

## Quiz Svar

chown
