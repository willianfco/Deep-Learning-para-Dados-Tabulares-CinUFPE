# Deep Learning para Dados Tabulares CinUFPE
Projeto avaliativo da disciplina Deep Learning para Dados Tabulares do curso de Especialização em Deep Learning do CIn-UFPE.
 
Divida as séries selecionadas nos conjuntos de treinamento, validação e teste com as seguintes porcentagens: 50%, 25% e 25%, respectivamente, seguindo a ordem temporal.

Desenvolva, avalie e compare os modelos no cenário da previsão de um passo à frente.

1) Estimação de um modelo estatístico linear
* Faça todo pré-processamento necessário para treinar um modelo ARIMA utilizando a
metodologia de Box & Jenkins.
* Escolha o modelo mais adequado para fazer a previsão no conjunto de teste a partir do
erro no conjunto de treinamento e da série de resíduos.
* Gere os erros de previsão e gráficos para o conjunto de treinamento e teste. Sugestão:
erro quadrático médio (EQM, ou MSE em inglês) e mean absolute percentage error
(MAPE).

2) Treinamento de três (3) modelos de Aprendizado de Máquina
* Faça todo pré-processamento necessário para treinar uma Rede Neural Multilayer
Perceptron, ou uma Support Vector Regression, e dois modelos de Aprendizado
Profundo (Convolutional Neural Network, Long Short Term Memory ou Transformer).
* Utilize um grid search/random search para estabelecer os parâmetros do modelo.
* Utilize o conjunto de validação para selecionar o melhor modelo.
* Gere os erros de previsão e gráficos para o conjunto de treinamento, validação e teste.
Sugestão: erro quadrático médio (EQM, ou MSE em inglês) e mean absolute percentage
error (MAPE).

Faça a comparação dos quatro modelos implementados e construa uma apresentação
mostrando:
* A série utilizada nos experimentos.
* A metodologia utilizada em cada uma das tarefas.
* Mostre a comparação dos modelos.
