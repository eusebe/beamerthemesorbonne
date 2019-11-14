INSTALLATION

Pas vraiment d'installation à faire, veillez :
- à avoir installé les fontes fira sans (https://tug.org/FontCatalogue/firasans/, incluses dans texlive normalement)
- à avoir les fichiers beamer[xxx].sty, default.beamer, headersorbonne.tex (ou headersorbonne2pages.tex en fonction 
  de la sortie voulue), toc.tex, sorbonne-med.jpg et sorbonne-med-white.png dans le même répertoire que vos créations

UTILISATION

- Soit directement avec un fichier latex (voir exemple_latex.tex). L'option par défaut est "style=medecine" (thème 
  rouge et logo "sorbonne université médecine". Vous pouvez aussi utiliser l'option "style=universite" pour obtenir
  un thème bleu et le logo "sorbonne université".
- Soit via rmarkdown (voir exemple_rmarkdown.Rmd, qui se compile directement avec le raccourcis Ctrl+Shift+K si vous 
  utilisez RStudio). Vous pouvez dans ce cas ajouter des packages et options spécifiques à latex dans le fichier 
  headersorbonne.tex. Vous pouvez aussi mettre headersorbonne2pages.tex à la place de headersorbonne.tex 
  dans le fichier .Rmd (option 'in_header' au début du fichier) pour avoir un fichier pdf avec 2 diapos par page 
  (plus pratique pour imprimer). Enfin, headersorbonnemed.tex et headersorbonnemed2pages permettent d'obtenir des 
  diapos avec un thème rouge et le logo "sorbonne université médecine"
- La compilation fonctionne avec pdflatex ou xelatex. L'aspect des fonts ne sera pas exactement le même. Si vous 
  arrivez à faire fonctionner xelatex, utilisez le modèle de document 'exemple_rmarkdown_xelatex.Rmd'. Sinon, 
  'exemple_rmarkdown_pdflatex.Rmd'