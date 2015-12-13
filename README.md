To compile the file proposal.tex to postscript, do the following:

```
latex proposal
bibtex proposal
latex proposal
latex proposal
dvips proposal -o
```

This will give you a file proposal.ps that you can view with gv or
kghostview or whatever. You can also use xdvi to look at proposal.dvi,
which is handy while you are editing. As examples:

```
gv proposal&
xdvi proposal&
```

