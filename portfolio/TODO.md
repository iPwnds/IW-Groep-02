# Tegen tussentijdse deadlines

- Updaten zoekcriteria
- Updaten referenties
- Nagaan of tex-bestand compileerbaar
    ```bash
    # optie 1
    pdflatex artikel.tex
    bibtex artikel

    # optie 2
    latexmk -pdf artikel.tex

    # optie 3
    # LaTeX Workshop VSCode Plugin
    ```



# Tegen finale deadline

- Toevoegen beschrijving van Rami in beschrijving/groepsleden
- Nagaan of verslagen in orde (notulist, projectleider, datum, uur)
- Controleren of geen overbodige referenties in referentielijst (naar
elke referentie moet verwezen worden in tekst)
- Nagaan of tex-bestand compileerbaar
    ```bash
    # optie 1
    pdflatex artikel.tex
    bibtex artikel

    # optie 2
    latexmk -pdf artikel.tex

    # optie 3
    # LaTeX Workshop VSCode Plugin
    ```
- Aantal woorden nagaan via `texcount`-commando
    ```bash
    # zorg ervoor dat texlive-extra-utils-package is geinstalleerd
    texcount -inc artikel.tex
    # kijk naar getal bij 'Words in text'
    ```
- Aantal referenties nagaan: 7 à 15 goede en diverse, 5 wetenschappelijk
- Indien taal probleem lijkt, voor correcties door met
  [ILT Schrijfhulp](https://ilt.kuleuven.be/schrijfhulp/)
- Verduidelijken gebruik GAI in appendix.

