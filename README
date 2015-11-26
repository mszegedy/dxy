A tiny bash script for getting definitions of words in a particular language,
using Wiktionary's brief .TSVs. I wrote this after I discovered that it's
possible to download the entirety of Wiktionary onto your computer, and that
it's not even a big file. It relies on a file named `<language>.tsv' existing in
the directory `/usr/share/dxy/', which you can create easily using Wiktionary's
abbreviated-form .TSVs and a simple `grep' command. Unfortunately, you have no
hope of getting this to work on your own computer, because the server with the
brief .TSV on it has been down for at least a year, and I deleted the original
master .TSV to save space. The contents of my `/usr/share/dxy' are in
`dxy-data/'. I later wrote a script to reconstruct the brief .TSV from the
unabridged source of Wiktionary, but it was so slow-going that I never let it
run to completion. Anyway, usage:

    dxy <language> <word>

It's case-sensitive and diacritic-preserving, so be careful. The name of the
language should be in lower-case (unless you rename the contents of
`/usr/share/dxy').
