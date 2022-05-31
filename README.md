# cv

Compile with XeLatex

## Mac Installation
* `brew install --cask basictex`
* Try `xelatex.tex`. 
* If it successfully genreates the pdf, the installation is done. In my case, it shows blablabla.sty not found:
  * Get sty files, in ctan website
  * If you get the zip file and it doesn't contain .sty file, build first, then copy the dir
    * `latex textpos.ins`
    * `sudo mv -r textpos /usr/local/texlive/2023basic/texmf-dist/tex/latex/`
  * If you already get the .sty file, just copy them or each dirs in that directory
    * `sudo mv -r *.sty /usr/local/texlive/2023basic/texmf-dist/tex/latex`
  * `sudo texhash`
  * [qq](https://tex.stackexchange.com/questions/10252/how-do-i-add-a-sty-file-to-my-mactex-texshop-installation)

## Run
`xelatex cv.tex`
