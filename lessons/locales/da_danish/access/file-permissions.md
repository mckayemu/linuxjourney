# Filtilladelser

## Lektionsindhold

Som vi tidligere har lært, har filer forskellige tilladelser eller filtilstande. Lad os se på et eksempel:

<pre> $ ls -l Desktop/
drwxr-xr-x 2 pete pingviner 4096 dec 1 11:45.
</pre>

Der er fire dele til en fils tilladelser. Den første del er filetypen, som betegnes af det første tegn i tilladelserne, da vi ser på en mappe, vises der <b>d</ b> for filetypen. Mest almindeligt ser du en <b>-</ b> for en almindelig fil.

De næste tre dele af filtilstanden er de faktiske tilladelser. Tilladelserne er grupperet i 3 bits hver. De første 3 bits er brugerrettigheder, derefter gruppetilladelser og derefter andre tilladelser. Jeg har tilføjet røret for at gøre det lettere at differentiere.

<pre>d | rwx | r-x | r-x </pre>

Hvert tegn repræsenterer en forskellig tilladelse:
<ul>
<li>r: læsbar</li>
<li>w: skrivbar</li>
<li>x: eksekverbar (stort set et eksekverbart program)</ li>
<li>-: tom</li>
</ul>

Så i ovenstående eksempel ser vi, at brugeren pete har læs, skriv og eksekver tilladelser på filen. Gruppen penguins har læs og eksekver tilladelser. Og til sidst har de andre brugere (alle andre) læs og eksekver tilladelser.

## Øvelse

Brug kommandoen ls -l på flere filer og recitér deres tilladelser, bruger og gruppe.

## Quiz Spørgsmål

Hvilken tilladelsesbit bruges til eksekverbar?

## Quiz Svar

x
