English:
Multi-Layer Perceptron (MLP) Neural Network for Fraud Detection and Optdigits Classification

This Python code provides a flexible implementation of a Multi-Layer Perceptron (MLP) neural network for two potential applications: fraud detection and Optdigits classification. The code includes a graphical user interface (GUI) built with the Tkinter library, allowing users to specify parameters, load data, and train the network.
Key Features:

    MLP Network: The code defines an MLP neural network with user-configurable input size, hidden layer size, output size, and learning rate.
    Training and Testing: It supports the training of the neural network with labeled data. The dataset is divided into training and testing sets, and the network is trained using backpropagation.
    GUI Interface: The GUI allows users to input the hidden layer size, learning rate, and the number of training epochs. It also provides a button to load the dataset.
    Results Visualization: The code generates plots to visualize the training and testing error rates over epochs.
    Data Loading: Users can load their own datasets in CSV format. The code handles data preprocessing and one-hot encoding of target labels.
    Error Tracking: The code keeps track of errors during training and provides results for each epoch.

Applications:

    Fraud Detection: This code can be used for fraud detection tasks where the goal is to classify transactions as either "fraudulent" or "non-fraudulent" based on input features. The neural network learns to detect patterns indicative of fraudulent transactions.
    Optdigits Classification: In the context of Optdigits classification, the code can be applied to recognize handwritten digits from the Optdigits dataset. The network learns to classify input images into the correct digit categories.

Other Applications:

This code offers a versatile platform for experimenting with MLP neural networks and can be applied to various classification tasks beyond fraud detection and Optdigits classification. While it has been used for these specific purposes, it can be adapted for a wide range of machine learning and classification applications.
Usage:

    Launch the GUI by running the script.
    Specify the hidden layer size, learning rate, and the number of training epochs.
    Load your dataset in CSV format using the "Carregar Dados" (Load Data) button.
    Click the "Treinar Rede" (Train Network) button to initiate training.
    Monitor the training progress and view error rate plots.
    The code also provides a "Créditos" (Credits) button to acknowledge the authors.

This code offers a versatile platform for experimenting with MLP neural networks and can be applied to various classification tasks, including fraud detection, Optdigits recognition, and more.

====================================================================================

Português:
Rede Neural Multi-Layer Perceptron (MLP) para Detecção de Fraudes e Classificação Optdigits

Este código em Python oferece uma implementação flexível de uma rede neural Multi-Layer Perceptron (MLP) para duas possíveis aplicações: detecção de fraudes e classificação Optdigits. O código inclui uma interface gráfica de usuário (GUI) construída com a biblioteca Tkinter, permitindo que os usuários especifiquem parâmetros, carreguem dados e treinem a rede.
Principais Características:

    Rede MLP: O código define uma rede neural MLP com tamanho de entrada, tamanho da camada oculta, tamanho de saída e taxa de aprendizado configuráveis pelo usuário.
    Treinamento e Teste: Ele suporta o treinamento da rede neural com dados rotulados. O conjunto de dados é dividido em conjuntos de treinamento e teste, e a rede é treinada usando retropropagação.
    Interface GUI: A GUI permite que os usuários informem o tamanho da camada oculta, a taxa de aprendizado e o número de épocas de treinamento. Também fornece um botão para carregar o conjunto de dados.
    Visualização de Resultados: O código gera gráficos para visualizar as taxas de erro de treinamento e teste ao longo das épocas.
    Carregamento de Dados: Os usuários podem carregar seus próprios conjuntos de dados no formato CSV. O código trata da pré-processamento dos dados e codificação one-hot das etiquetas alvo.
    Acompanhamento de Erros: O código mantém o registro de erros durante o treinamento e fornece resultados para cada época.

Aplicações:

    Detecção de Fraudes: Este código pode ser usado para tarefas de detecção de fraudes, onde o objetivo é classificar transações como "fraudulentas" ou "não fraudulentas" com base em características de entrada. A rede neural aprende a detectar padrões indicativos de transações fraudulentas.
    Classificação Optdigits: No contexto da classificação Optdigits, o código pode ser aplicado para reconhecer dígitos escritos à mão a partir do conjunto de dados Optdigits. A rede aprende a classificar imagens de entrada nas categorias corretas de dígitos.

Outras Aplicações:

Este código oferece uma plataforma versátil para experimentar com redes neurais MLP e pode ser aplicado a várias tarefas de classificação além da detecção de fraudes e classificação Optdigits. Embora tenha sido usado para esses fins específicos, ele pode ser adaptado para uma ampla variedade de aplicações de aprendizado de máquina e classificação.
Uso:

    Inicie a GUI executando o script.
    Especifique o tamanho da camada oculta, a taxa de aprendizado e o número de épocas de treinamento.
    Carregue seu conjunto de dados no formato CSV usando o botão "Carregar Dados".
    Clique no botão "Treinar Rede" para iniciar o treinamento.
    Monitore o progresso do treinamento e visualize os gráficos de taxa de erro.
    O código também fornece um botão "Créditos" para reconhecer os autores.

Este código oferece uma plataforma versátil para experimentar com redes neurais MLP e pode ser aplicado a várias tarefas de classificação, incluindo detecção de fraudes, reconhecimento de Optdigits e muito mais.
