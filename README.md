Template para UFSCTeX
=====================

ufscThesis é uma classe LaTeX desenvolvida por Roberto Simoni e Carlos Rocha, que formata dissertações de acordo com as normas estabelecidas pela BU-UFSC.

UFSCTeX (https://github.com/royertiago/ufsctex) é um "reempacotamento" do trabalho feito por eles visando facilitar o uso em ambientes Linux. (O nome "UFSCTeX" é usado para distinguir do original de Simoni e Rocha. Esta é uma exigência da LPPL, uma das duas licenças da ufscThesis.)

Este repositório contém um template para textos produzidas com esta classe.

O código original, de Simoni e Rocha, pode ser obtido em
http://sbu.paginas.ufsc.br/files/2011/03/modelo.zip.

Organização
===

 - anexos: Diretório com anexos do trabalho
 - apendices: Diretório com apendices do trabalho
 - pre_textual: elementos pré textuais
 - template.tex: arquivo principal



Uso
===

```
 apt-get install abntex
 apt-get install texlive-full
```

Gerar versao
=====
```
  latexmk -pdf template.tex
```

Apos a execução do comando é gerado um [documento](template.pdf) com a estrutura do trabalho.  

Licença
=======

O código é disponibilizado sob GPL. Para detalhes, ver LICENSE.txt.
