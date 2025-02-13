
***EN***

# Project

This project involves building and training a neural network using Keras to process and classify data based on numerical features. The network is structured as a sequential model, composed of interconnected layers of neurons.

The model receives as input two values ​​corresponding to the size of the petals, with an initial layer defined by input_shape=[2] and a single neuron at the output (units=1). During construction, the network weights can be initialized with random values ​​(RandomNormal) or fixed (Ones).

Before training, the data undergoes preprocessing, including binarization of categories and normalization using MinMaxScaler to restrict the values ​​between [0,1]. Then, the data is divided into 80% for training and 20% for testing.

The neural network follows the structure of a Multilayer Perceptron (MLP) with three layers: input, hidden and output. Training is done via model.fit(), while performance evaluation is done with model.evaluate(), and new predictions can be generated with model.predict().

The results are visualized through graphs using Matplotlib, allowing analysis of the model's behavior during learning.

This project demonstrates the basic implementation of a neural network, covering everything from data preparation to model evaluation and use for predictions.



---
***PT-BR***

# Projeto


*Criando rede neural para classificação de flores: Ja foi realizado esse projeto anteriormente so que salvo somente no kaggle*


Este projeto envolve a construção e treinamento de uma rede neural utilizando Keras para processar e classificar dados com base em características numéricas. A rede é estruturada como um modelo sequencial, composto por camadas de neurônios interconectadas.

O modelo recebe como entrada dois valores correspondentes ao tamanho das pétalas, com uma camada inicial definida por input_shape=[2] e um único neurônio na saída (units=1). Durante a construção, os pesos da rede podem ser inicializados com valores aleatórios (RandomNormal) ou fixos (Ones).

Antes do treinamento, os dados passam por um pré-processamento, incluindo binarização de categorias e normalização usando MinMaxScaler para restringir os valores entre [0,1]. Em seguida, os dados são divididos em 80% para treino e 20% para teste.

A rede neural segue a estrutura de um Multilayer Perceptron (MLP) com três camadas: entrada, oculta e saída. O treinamento ocorre via modelo.fit(), enquanto a avaliação do desempenho é realizada com modelo.evaluate(), e novas previsões podem ser geradas com modelo.predict().

Os resultados são visualizados por meio de gráficos utilizando Matplotlib, permitindo a análise do comportamento do modelo durante o aprendizado.

Este projeto demonstra a implementação básica de uma rede neural, cobrindo desde a preparação dos dados até a avaliação do modelo e sua utilização para previsões.