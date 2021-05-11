---
layout: post
title: Algoritmo kNN(K vizinhos mais próximos)
categories: [kNN from Scratch, Python, Machine Learning, Análise de dados]
tags: [Python, Classificação, kNN, Dados]
fullview: true
comments: true
---

### Nesse notebook comento passo a passo a implementação do algoritmo kNN from scratch, esse algoritmo é tipicamente usado para tarefas de classificação, o principal parâmetro é o "k" que definirá quantos vizinhos serão selecionados. Utilizando o cálculo da distância euclidiana, calcula-se a distância entre um ponto P1 de classe desconhecida e N outros pontos de classes conhecidas. Os k rótulos dos pontos com menor distância euclidiana em relação a P1 serão selecionados e o rotulo mais comum (maior repetição) será atribuído a P1. Os dados utilizados são do Dataset Iris, obtidos através da biblioteca sklearn.


<p align="center">
  <img src="https://res.cloudinary.com/dyd911kmh/image/upload/f_auto,q_auto:best/v1531424125/Knn_k1_z96jba.png">
</p>

<h5 align="center">Exemplificação algoritmo kNN</h5>

<a class="btn btn-default" href="https://github.com/misaelpedro/kNN-from-Scratch"> Clique para acessar.</a>
