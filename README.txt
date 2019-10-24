INSTALLATION

Pas vraiment d'installation à faire, veillez :
- à avoir installé les fontes fira sans (https://tug.org/FontCatalogue/firasans/, incluses dans texlive normalement)
- à compiler vos documents avec *xelatex*
- à avoir les fichiers beamer[xxx].sty, default.beamer, headersorbonne.tex (ou headersorbonne2pages.tex en fonction 
  de la sortie voulue), toc.tex, sorbonne-med.jpg et sorbonne-med-white.png dans le même répertoire que vos créations

UTILISATION

- Soit directement avec un fichier latex (voir exemple_latex.tex)
- Soit via rmarkdown (voir exemple_rmarkdown.Rmd, qui se compile directement avec le raccourcis Ctrl+Shift+K si vous 
  utilisez RStudio). Vous pouvez dans ce cas ajouter des packages et options spécifiques à latex dans le fichier 
  headersorbonne.tex. Vous pouvez aussi mettre headersorbonne2pages.tex à la place de headersorbonne.tex 
  dans le fichier .Rmd (option 'in_header' au début du fichier) pour avoir un fichier pdf avec 2 diapos par page 
  (plus pratique pour imprimer).
