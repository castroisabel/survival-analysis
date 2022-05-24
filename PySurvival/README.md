# Análise de Sobrevivência com PySurvival

PySurvival é um pacote python de código aberto para modelagem de Análise de Sobrevivência - o conceito de modelagem usado para analisar ou prever **quando** um evento provavelmente acontecerá. A biblioteca fornece uma maneira muito fácil de navegar entre o conhecimento teórico sobre Análise de Sobrevivência e tutoriais detalhados sobre como realizar uma análise completa, construir e usar um modelo.

## Instalação

```bash
pip install pysurvival
```

## Introdução a Análise de Sobrevivência

A análise de sobrevivência é a a área da estatística interessada em estudar a duração entre eventos e é
usada para analisar ou prever quando um evento provavelmente acontecerá. Originou-se da pesquisa médica, mas seu uso se expandiu muito para muitos campos diferentes. Por exemplo:

- Bancos, credores e outras instituições financeiras o usam para calcular a velocidade de pagamento de empréstimos ou quando um mutuário entrará em inadimplência

- As empresas o usam para prever quando os funcionários decidirão sair

- Engenheiros/fabricantes o aplicam para prever quando uma máquina irá quebrar


## Censura

Em análise de sobrevivência a variável resposta é, geralmente, o tempo até a ocorrência de um evento de interesse. Esse tempo é denominado **tempo de falha**. A principal característica dos dados de sobrevivência é a presença de **censura**, que é a observação parcial da resposta.

*Por que os modelos de regressão não podem ser usados?*

Pode-se ficar tentado a usar um modelo de regressão para prever quando os eventos provavelmente ocorrerão. Mas, para isso, seria necessário desconsiderar amostras censuradas, o que resultaria na perda de informações importantes. Felizmente, os modelos de sobrevivência são capazes de levar em conta a censura e incorporar essa incerteza, de modo que, em vez de prever o momento do evento, estamos prevendo a **probabilidade de um evento ocorrer em um determinado momento**.

## Dados




