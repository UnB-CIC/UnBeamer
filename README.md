UnBeamer
========

Implementação da classe *UnBeamer*, que define algumas facilidades para criar
uma apresentação com [LaTeX](http://www.latex-project.org/) e
[Beamer](http://www.ctan.org/pkg/beamer), e do tema *UnB*, que define a aparência
da apresentação.

A proposta é ter uma identidade unificada para apresentações cujo escopo seja 
relacionado a [Universidade de Brasília](http://www.unb.br), buscando um visual 
simples.


## Instalação

Para instalar (no Linux), basta seguir os seguintes passos:

- Obter o [arquivo ZIP](https://github.com/gnamos/UnBeamer/archive/master.zip).

- Descompactar o arquivo para [diretório local](http://tug.org/tds/tds.html).
```
unzip UnBeamer-master.zip -d ~/texmf/tex/latex
```

- Gerar a documentação e os arquivos da classe e tema.
```
cd ~/texmf/tex/latex
pdflatex UnBeamer.dtx
```

- Embora desnecessário nas versões mais recentes do [TeX Live](https://www.tug.org/texlive/), 
pode ser preciso atualizar os registros.
```
texhash ~/texmf
```

Veja a documentação gerada (arquivo UnBeamer.pdf) para instruções e exemplos de uso.
