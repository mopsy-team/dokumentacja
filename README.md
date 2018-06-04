# dokumentacja

Repozytorium na pracę licencjacką, prezentacje i inne materiały niebędące kodem

Aby skompilować pracę należy wpisać polecenie: 
`pdflatex -synctex=1 -interaction=nonstopmode %.tex|makeglossaries %|pdflatex -synctex=1
-interaction=nonstopmode %.tex|pdflatex -synctex=1 -interaction=nonstopmode %.tex`

albo polecenia:
`pdflatex praca`
`makeglossaries praca`
`pdflatex praca`
