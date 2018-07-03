# Setgid

## Lektionsindhold

I lighed med den indstillede bruger ID-tilladelsesbit er der et sæt gruppe-ID (SGID) tilladelsesbit. Denne bit tillader et program at køre som om det var medlem af gruppen.

Lad os se på et eksempel:

<pre>$ ls -l /usr/bin/wall
-rwxr-sr-x 1 root tty 19024 Dec 14 11:45 /usr/bin/wall
</pre>

Vi kan nu se, at tilladelsesbiten er i gruppens tilladelsessæt.

<b>Ændring af SGID</b>

<pre>$ sudo chmod g+s myfile
$ sudo chmod 2555 myfile
</pre>

Den numeriske repræsentation for SGID er 2.

## Øvelse

Ingen øvelser til denne lektion.

## Quiz Spørgsmål

Hvilket tal repræsenterer SGID?

## Quiz Svar

2
