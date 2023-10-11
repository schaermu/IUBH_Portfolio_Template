# LaTeX Template für IUBH Portfolios

Im Gegensatz zum [IUBH Template](https://github.com/schaermu/IUBH_Template) werden die 3 Files `P1_konzept.tex`, `P2_erarbeitung.tex` und `P3_abstract.tex` separat in den Output-Ordner `out.nosync` kompiliert. Dies erleichtert die Einreichung auf Pebble.
## Voraussetzungen
* VS Code
* TexLive-Installation auf WSL 2 / Ubuntu
  * `apt-get install texlive-latex-extra texlive-extra-utils texlive-xetex texlive-lang-german texlive-bibtex-extra fontconfig ttf-mscorefonts-installer latexmk biber xindy python3-pygments`
* [Biber](https://sourceforge.net/projects/biblatex-biber/files/biblatex-biber/current/binaries/)
* [Arial on WSL2](https://askubuntu.com/questions/651441/how-to-install-arial-font-and-other-windows-fonts-in-ubuntu)
* VS Code Erweiterungen:
  * [latex-workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) - Tooling
  * [latex-utilities](https://marketplace.visualstudio.com/items?itemName=tecosaur.latex-utilities) - Tooling (Addons)
  * [LTeX](https://marketplace.visualstudio.com/items?itemName=valentjn.vscode-ltex) - Rechtschreibprüfung & Grammatik