# Latex template for my PhD thesis at Université de Lille
Template by Elis DE CASTRO, inspired from Paris Saclay
[https://www.overleaf.com/latex/templates/template-phd-thesis-paris-saclay-university/ywxthgcxmfcr]

## How to use this template
The main file is [thesis.tex](thesis.tex).

To add your name, the title of your thesis, the jury members, the school logo, you should modify:
* [layout/firstpage](layout/firstpage.tex)
* [layout/lastpage](layout/lastpage.tex) 
* [thesis.tex](thesis.tex)

To add acknowledgements or a dedication, you should modify:
* [layout/acknowledgements](layout/acknowledgements.tex)
* [layout/dedication](layout/dedication.tex)

The content of the thesis chapters is in:
* [chaps/1](chaps/1.tex)
* [chaps/2](chaps/2.tex)
...

The content of the appendices is in:
* [appendices/1](appendices/1.tex)
* [appendices/2](appendices/2.tex)
...

In case you add or remove a chapter file or an appendix file, don't forget to update 
the corresponding variable (`\NumOfChapters` or `\NumOfAppendices`) in [thesis.tex](thesis.tex).

If you want to improve this template, feel free to make pull requests!

