# Ændring af Tilladelser

## Lektionsindhold

Ændring af tilladelser kan nemt gøres med kommandoen <b>chmod</b>.

Først skal du vælge hvilken tilladelse du vil ændre, bruger, gruppe eller andre. Du kan tilføje eller fjerne tilladelser med et <b>+</b> eller <b>-</b>, lad os se på nogle eksempler.

<b>Tilføjelse af tilladelsesbit på en fil</b>
<pre>$ chmod u+x myfile</pre>

Kommandoen ovenfor læses som dette: Skift tilladelse til myfile ved at tilføje eksekverbar tilladelsesbit på brugersættet. Så nu har brugeren eksekverbar tilladelse til denne fil!

<b>Fjernelse af tilladelsesbit på en fil</b>
<pre>$ chmod u-x myfile</pre>

<b>Tilføjelse af flere tilladelsesbits på en fil</b>
<pre> $ chmod ug + w </pre>

Der er en anden måde at ændre tilladelser ved hjælp af numerisk format. Denne metode giver dig mulighed for at ændre alle tilladelser på én gang. I stedet for at bruge r, w eller x til at repræsentere tilladelser, bruger du en numerisk repræsentation for et enkelt tilladelsessæt. Så det er ikke nødvendigt at angive gruppen med g eller brugeren med u.

De numeriske repræsentationer ses nedenfor:

<ul>
<li>4: læs tilladelse</li>
<li>2: skriv tilladelse</li>
<li>1: eksekver tilladelse</li>
</ul>

Lad os se på et eksempel:

<pre>$ chmod 755 myfile</pre>

Kan du gætte hvilke tilladelser vi giver denne fil? Lad os bryde det ned, så nu dækker 755 tilladelserne for alle sæt. Det første nummer (7) repræsenterer brugerrettigheder, det andet nummer (5) repræsenterer gruppetilladelser, og de sidste 5 repræsenterer andre tilladelser.

Vent et øjeblik, 7 og 5 var ikke nævnt ovenfor, hvorfra får vi disse tal? Husk at vi kombinerer alle tilladelserne til et nummer nu, så du bliver nødt til involvere lidt matematik.

7 = 4 + 2 + 1, så 7 er brugerrettighederne, og den har læs, skriv og eksekver tilladelser

5 = 4 + 1, gruppen har læs og eksekver tilladelser

5 = 4 +1, og alle andre brugere har læs og eksekver tilladelser

En ting at bemærke: Det er ikke en god idé at ændre tilladelser nilly willy, du kan potentielt udsætte en følsom fil for alle at ændre, men mange gange vil du legitimt ændre rettigheder, bare tag dine forholdsregler, når du bruger chmod-kommandoen.

## Øvelse

Skift nogle grundlæggende tekstfiltilladelser, og se bitene skifter, som du gør en ls -l.

## Quiz Spørgsmål

Hvilket tal repræsenterer læsetilladelsen, når du bruger numerisk format?

## Quiz Svar

4
