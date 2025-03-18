<h1 align="center" font-size="200em"><b>House Prices - Desafio Kaggle</b></h1>

<div align = "center" >
<!-- imagem -->

[![requirement](https://img.shields.io/badge/IDE-Visual%20Studio%20Code-informational)](https://code.visualstudio.com/docs/?dv=linux64_deb)
![Linguagem](https://img.shields.io/badge/Linguagem-Python-orange)
</div>

Este projeto foi realizado como parte de um desafio no Kaggle, com o objetivo de prever o preço das casas com base em diversas características. Utilizando técnicas de predição, regressão linear, árvore de regressão e KNN, o modelo foi desenvolvido para identificar e prever os preços de casas de maneira precisa.

## 💻Objetivo

O principal objetivo deste projeto foi construir um modelo de predição capaz de prever o preço das casas, utilizando um conjunto de dados que contém diversas variáveis sobre as propriedades, como tamanho, número de quartos, localização e outras características. O modelo foi treinado e validado utilizando métodos de Machine Learning.

## Técnicas e Algoritmos Utilizados

- **Regressão Linear**: Utilizada para prever a variável dependente (preço da casa) com base nas variáveis independentes (características das casas).
- **Árvore de Regressão**: Usada para modelar a relação não linear entre as características das casas e o preço, proporcionando um modelo mais flexível.
- **KNN (K-Nearest Neighbors)**: Utilizado para prever o preço com base nos preços das casas mais próximas no conjunto de dados, um algoritmo baseado em similaridade.
- **Limpeza e Tratamento de Dados**: O conjunto de dados foi limpo e transformado para lidar com valores ausentes, dados inconsistentes e outliers.

## 🔢Tecnologias Utilizadas

- **Python**: Linguagem principal utilizada para análise e modelagem.
- **Pandas**: Para manipulação e análise dos dados.
- **NumPy**: Para operações numéricas.
- **Scikit-learn**: Para implementação dos modelos de Machine Learning (Regressão Linear, Árvore de Regressão, KNN).
- **Matplotlib / Seaborn**: Para visualização dos dados e resultados.

## 📄Estrutura do Projeto

- **data/**: Contém os conjuntos de dados originais e tratados.
- **notebooks/**: Jupyter Notebooks com as análises, limpeza de dados e modelagem.
- **README.md**: Este arquivo, com detalhes do projeto.

## Como Rodar o Projeto

1. Clone este repositório:
   ```bash
   git clone <url-do-repositório>
   ```

2. Instalar as dependências:
  ```bash
  !pip install <nome-das-dependencias>
  ```
3. Executar o projeto

## 🎯Resultados

Para escolher o melhor modelo de predição, realizamos uma comparação entre os algoritmos utilizando tanto o erro absoluto médio (MAE) quanto o erro quadrático médio (MSE). A a árvore de regressão e o KNN foram avaliados com base nesses critérios.

- **Árvore de Regressão**: Foi eficaz para modelar a relação não linear entre as variáveis e os preços das casas, apresentando um erro absoluto e quadrático menores do que a regressão linear.
- **KNN (K-Nearest Neighbors)**: O KNN teve desempenho similar à árvore de regressão, com baixo erro em ambos os critérios de avaliação. Ele se destacou especialmente ao capturar relações mais complexas entre as variáveis.

Com base nos resultados, a árvore de regressão foi escolhido como os melhor modelo para a predição dos preços das casas, devido à sua maior precisão em comparação com o KNN.

## Conclusão

Este projeto demonstra como diferentes técnicas de Machine Learning podem ser aplicadas para prever preços de casas, e como a limpeza e o tratamento adequado dos dados são cruciais para garantir um bom desempenho do modelo. A árvore de regressão foi o modelo que se destacou para esse tipo de análise, embora o KNN tenha sido útil como ponto de partida.

## 👾Compilação e execução
* Especificações da máquina em que o código foi rodado:
  * Processador Intel Core i7, 12th Gen;
  * Sistema Operacional Ubuntu 22.04.5;
  * 16GB de RAM.
* | Comando                |  Função                                                                                           |                     
  | -----------------------| ------------------------------------------------------------------------------------------------- |
  |  `make clean`          | Apaga a última compilação realizada contida na pasta build                                        |
  |  `make`                | Executa a compilação do programa utilizando o gcc, e o resultado vai para a pasta build           |
  |  `make run`            | Executa o programa da pasta build após a realização da compilação                                 |


## Contato
<div>
 <br><p align="justify"> Jullia Fernandes</p>
 <a href="https://t.me/JulliaFernandes">
 <img align="center" src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white"/> 
 </div>
<a style="color:black" href="mailto:julliacefet@gmail.com?subject=[GitHub]%20Source%20Dynamic%20Lists">
✉️ <i>julliacefet@gmail.com</i>
</a>

