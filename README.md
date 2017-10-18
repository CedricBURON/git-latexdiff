# git-latexdiff
A tool to see the diff between two commits of a latex file. This file is written for Linux and needs `bash`to be run.

This tool is based on https://gitlab.com/git-latexdiff/git-latexdiff

usage:
```
git-latexdiff file.tex first-commit-hash second-commit-hash
```

It is also possible to make the diff with HEAD:
```
git-latexdiff file.tex previous-commit-hash
```
The program will display the pdf with deleted part in red, strikethrough and added part in blue underlined with waves. For the moment, only bibtex bibliography is accepted (though I'm working on a version for biber).
