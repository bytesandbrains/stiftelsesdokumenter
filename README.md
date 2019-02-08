# Stiftelsesdokumenter
Open source stiftelsesdokumenter til opstart af ny IVS virksomhed i Danmark.

Projektet indeholder skabeloner til:
* Stiftelsesdokument
* Vedtægter
* Egenerklæring
* Beslutningsreferat for navneændring

# Opsætning og kørsel
Du skal opsætte latexmk https://mg.readthedocs.io/latexmk.html

Ubuntu:
apt install latexmk
Arch:
pacman install latexmk

MacOS og Windows:
Se https://mg.readthedocs.io/latexmk.html

For at kompilere et dokument, kør `latexmk --pdf sti-til-texfil.tex`. `latexmk` vil outputte en PDF i mappen.

# Anvendelse
Projektet bruges ved at indsætte/rette i `skabelon-stiftelse`, `skabelon-vedtaegter` eller `skabelon-egenerklaering`.
