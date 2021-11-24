# RNA_python-MLP
Uma rede neural artificial pode ser entendida como uma implementação computacional que visa obter algum dado útil de uma base de dados. Tal rede pode ser implementada de diversas formas visando alcançar algum objetivo. Uma das primeiras redes neurais construídas foi Multi-Layer Perceptron (MLP) ou rede perceptron de múltiplas camadas. A MLP consiste no cascateamento em diversas camadas de um neurônio básico de uma rede neural, o perceptron. Esse neurônio artificial pode ser dividido em pesos, entradas e saída. Cada parte sua tem uma relação matematica importante que torna possivel gerar algum resultado. Os pesos são os pesos sinápticos que influencia diretamente na saida do neurônio, a entrada é a fonte de dados que entra no neurônio e, influencia pelos pesos, gera uma saída que resulta de um cálculo sistemático.
# Detalhes da implementação 
A implementação é feita em etapas, que vão desde a criação de dados para o treinamento, até a predição final após a construções do algoritmo.
A implementação foi realizada na linguagem orientada objeto Python, visto a grande facilidade de lidar com dados, matrizes e listas, além de possuir bibliotecas uteis para gráficos. O objetivo da rede neural é conseguir classificar qual letra A, B ou C está
3
sendo exibida numa matriz de entrada para a rede. Utilizando a lógica de programação em python, algumas bibliotecas para visualizar e tratar os dados, foi possível construir um programa que mostra transparentemente o funcionamento de uma MLP.
Inicialmente, é criado 3 matrizes que representam as letras A, B e C. Após isso, é mais adequado passar para a rede neural não uma matriz, mas sim um único array com todos os dados de entrada. Isso é feito transformando a matriz em um array do Numpy (biblioteca matemática e estatística do python). Após esse tratamento, inicia-se o código da MLP em si. A arquitetura resumida da rede implementada pode ser vista na Figura 3 abaixo.
Figura 3.

![alt text](https://github.com/FirerPlayer/RNA_python-MLP/blob/main/img1.jpg)

Mais detalhes podem ser vistos no Relatório de Redes Neurais Artificiais, produzido para completar a disciplina de Redes Neurais Artificiais na UFPA.
