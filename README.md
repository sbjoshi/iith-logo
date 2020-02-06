# iith-logo
IITH Logo and Letterhead in LaTeX

Use the following command to compile if you want logo to appear with "Indian Institute of Technology" in Hindi and English in appropriate fonts below the logo image:

    xelatex iith-lh.tex
    xelatex iith-lh-everypage.tex


Use the following command to compile if you just want the logo image, without the text below:

    latex iith-lh.tex
    latex iith-lh-everypage.tex
  
Requires the following fonts:

* Liberation Sans
* Nakula

Requires the following LaTeX packages:

* fontenc (works only with XeLaTeX)
* geometry
* array
* fontspec (works only with XeLaTeX)
* setspace
* tikz
* xcolor
