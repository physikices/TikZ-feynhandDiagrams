# TikZ-feynhandDiagrams

Diagramas de Feynman em TikZ usando o pacote `tikz-feynhand`.

## Como compilar

```sh
pdflatex main.tex
```

Os diagramas ficam em `img/` e são incluídos no documento principal por meio do comando `\feynhandfigure{nome-do-arquivo}` definido em `main.tex`.
