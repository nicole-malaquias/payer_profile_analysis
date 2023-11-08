# Análise de dados para o empréstimo de capital de giro da Open

## Objetivo

O objetivo deste projeto é analisar uma base de dados de empréstimos de capital de giro para identificar as características que distinguem bons e maus pagadores. A partir dessa análise, será possível desenvolver um score próprio para os clientes, que ajudará a Open a tomar melhores decisões de crédito.

## Metodologia

A análise será realizada utilizando a linguagem de programação Python com Pandas.

### Inicialização

* Serão calculados o ticket, a taxa e o prazo médios dos empréstimos.
* Serão definidas as variáveis "bad" e "loss".
    * A variável "bad" é uma variável binária que indica se o empréstimo foi inadimplido (1) ou não (0).
    * A variável "loss" indica o impacto financeiro da inadimplência, sendo calculada como o valor em aberto dos empréstimos inadimplidos dividido pelo valor principal e juros total dos empréstimos.

### Análise exploratória

* Serão realizadas análises exploratórias para identificar as características que distinguem bons e maus pagadores.
  Essas análises serão realizadas utilizando técnicas estatísticas como tabelas de frequência, gráficos e testes de hipótese.

Essas características serão utilizadas para desenvolver um score próprio para os clientes da Open.

## Recomendações

Para executar a análise, recomenda-se utilizar o Google Colab.