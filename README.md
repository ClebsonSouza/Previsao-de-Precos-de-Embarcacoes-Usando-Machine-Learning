# Previsao_Precos_Embarcacoes
Base de Dados: https://drive.google.com/drive/folders/1o2lpxoi9heyQV1hIlsHXWSfDkBPtze-V?usp=share_link

O desafio é tentar prever o preço de embarcações baseado nas características: tipo de barco, ano, tamanho, novo ou usado, material usado, etc.

Este projeto tem como objetivo desenvolver um modelo de machine learning para prever os preços de barcos com base em diversas características. Utilizando técnicas de Regressão Linear e Regressão por Floresta Aleatória, buscamos fornecer previsões precisas para auxiliar na tomada de decisões de compra e venda no mercado de barcos.

Problema de Negócio
Prever o preço de barcos é crucial para diversas partes interessadas, incluindo vendedores, compradores e empresas de avaliação. Com dados precisos e modelos bem treinados, é possível determinar o valor justo de um barco, o que facilita negociações e transações financeiras.

Estrutura do Projeto
1. Carregamento dos Dados
Carregamos a base de dados a partir do arquivo CSV barcos_ref.csv, contendo informações detalhadas sobre os barcos.

2. Análise de Correlação
Calculamos e visualizamos a matriz de correlação para entender as relações entre as variáveis independentes e o preço dos barcos. Essa análise ajuda a identificar quais características têm maior impacto no preço.

3. Divisão dos Dados
Os dados são divididos em conjuntos de treino e teste utilizando a função train_test_split, garantindo que possamos avaliar a performance dos modelos de maneira eficaz.

4. Treinamento dos Modelos
Dois modelos de machine learning são treinados:

Regressão Linear: Simples e interpretável, útil para entender a relação linear entre as características e o preço.
Floresta Aleatória: Modelo mais complexo que pode capturar relações não lineares e interações entre características.
5. Avaliação dos Modelos
As previsões dos modelos são comparadas usando a métrica R². Essa avaliação nos permite entender qual modelo oferece melhores previsões para os dados de teste.

6. Visualização das Previsões
Visualizamos as previsões dos modelos em um gráfico, facilitando a comparação e a interpretação dos resultados.

7. Previsão para Novos Dados
Carregamos um novo conjunto de dados (novos_barcos.csv) e utilizamos o modelo de Floresta Aleatória para prever os preços desses novos barcos.

Conclusão:
Este projeto fornece uma abordagem prática e eficiente para prever os preços de barcos, utilizando dados históricos e técnicas avançadas de machine learning. As previsões precisas podem ser extremamente úteis para facilitar negociações e decisões no mercado de barcos.
