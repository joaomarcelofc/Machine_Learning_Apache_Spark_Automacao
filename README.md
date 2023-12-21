[![author](https://img.shields.io/badge/author-jaomarcelofc-red.svg)](https://www.linkedin.com/in/joao-marcelo-fonseca-cunha) [![](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-365/)

# Machine Learning na Engenharia Civil com Apache Spark – Automação de preparação de dados

# Objetivo
Este projeto aborda todo o processo de Machine Learning no contexto de um problema na área de Engenharia Civil. Mas ao invés de aplicar as tarefas uma a uma, criaremos módulos de automação. Ou seja, vamos desenvolver nosso próprio sistema de AutoML, sem o uso de frameworks específicos e aplicando Machine Learning com o Spark MLlib no PySpark.

<p align="center">
  <img src= "imagens/pythonspark.png"width=50% >
</p>

# Definição do problema e fonte de dados
O concreto é o material mais importante na Engenharia Civil. A resistência à compressão do concreto é uma função altamente não linear da idade e dos ingredientes usados para preparar o concreto. Nosso trabalho será construir um modelo preditivo capaz de prever a força do concreto com base em uma série de características e ingredientes do concreto. Usaremos um dataset disponível publicamente no link abaixo: 

https://archive.ics.uci.edu/ml/datasets/Concrete+Compressive+Strength

Como iremos prever um valor numérico que representa a força do concreto e temos dados de entrada e saída, este é um problema de regressão. Vamos experimentar diferentes algoritmos de regressão e escolher o que apresentar a melhor performance. Técnicas de otimização de hiperparâmetros serão exploradas para chegar ao melhor modelo possível. Com o modelo treinado faremos previsões usando novos dados.
