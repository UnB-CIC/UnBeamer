UnBeamer
========

Implementação da classe *UnBeamer*, que define algumas facilidades para criar uma apresentação com [LaTeX](http://www.latex-project.org/) e [Beamer](http://www.ctan.org/pkg/beamer), e do tema *UnB*, que define a aparência da apresentação.

A proposta é ter uma identidade unificada para apresentações cujo escopo seja relacionado a [Universidade de Brasília](http://www.unb.br), buscando um visual simples.

Instalação
----------

Para instalar, basta seguir os seguintes passos:

- Obter o [arquivo ZIP](https://github.com/gnramos/UnBeamer/archive/master.zip).

- Descompactar o arquivo para [diretório local](http://tug.org/tds/tds.html) (no caso do [MikTeX](http://miktex.org/), vejam [aqui](http://docs.miktex.org/manual/localadditions.html)).

```bash
unzip UnBeamer-master.zip -d ~/texmf/tex/latex
```

- Gerar a documentação e os arquivos da classe e tema.

```bash
cd ~/texmf/tex/latex
pdflatex UnBeamer.dtx
```

- Embora desnecessário nas versões mais recentes do [TeX Live](https://www.tug.org/texlive/), 
pode ser preciso atualizar os registros. 

```bash
texhash ~/texmf
```

Aparentemente o [MikTeX](http://miktex.org/) no Windows não é tão esperto, mas a versão 2.9 quase consegue... No Windows XP (32 bits), a instalação pode ser feita da seguinte forma: após baixar o arquivo ZIP, existem [algumas opções](http://docs.miktex.org/manual/localadditions.html). Supondo o reuso da classe, descompacte-o _no seu diretório local_ e registre-o como _root_. Abra o arquivo ```UnBeamer.dtx``` no TeXWorks, e compile-o com a opção _pdflatex_ (gerando o PDF com instruções para a classe). O programa reclama da ausência de alguns pacotes, mas já se oferece para instalá-los (aceite!). Dois arquivos ```tex``` são gerados como exemplos de uso, copie-os para outro diretório (já que o MikTeX teria problemas para compilá-los de dentro do diretório local), por exemplo sua pasta de Downloads.

Veja a documentação gerada (arquivo UnBeamer.pdf) para instruções e exemplos de uso.
