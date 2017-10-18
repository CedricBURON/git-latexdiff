# git-latexdiff
A tool to see the diff between two commits of a latex file

This tool is based on https://gitlab.com/git-latexdiff/git-latexdiff

usage:
```
git-latexdiff file.tex first-commit-hash second-commit-hash
```

It is also possible to make the diff with HEAD:
```
git-latexdiff file.tex previous-commit-hash
```
