I put the \HCode command inside

```
\ifdefined\HCode
```

and

```
\fi
```

This is needed because `pdflatex` gets run on all the files, as part of the TikZ externalization procedure.
