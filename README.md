# stock-prediction
Previsão de preços de ações com LSTM e comparação com Prophet


Projeto: Previsão de Preços de Ações (Apple Inc.)
Este projeto utiliza um modelo LSTM (Long Short-Term Memory) e Prophet para prever os preços das ações da Apple Inc. A abordagem inclui uma comparação com uma baseline simples (previsão usando o último valor observado), demonstrando como um modelo mais sofisticado pode melhorar as previsões.


Objetivo
O objetivo é:

-Utilizar LSTM para realizar a previsão de preços de ações.
-Comparar o desempenho do modelo LSTM com uma baseline simples.
-Demonstrar o uso do Prophet para comparação.


Tecnologias e Ferramentas Usadas
Linguagem: Python


Bibliotecas:
-yfinance (para download dos dados de ações)
-scikit-learn (métricas e pré-processamento)
-TensorFlow (construção do modelo LSTM)
-Prophet (modelo de previsão)
-Matplotlib (visualização de gráficos)


Estrutura do Projeto
stock_price_prediction.ipynb: Contém o notebook principal com o código, treinamentos e visualizações.


Modelos Implementados:
-LSTM (focado em padrões de longo prazo nas séries temporais)
-Prophet (modelo de previsão desenvolvido pelo Facebook)


Próximos Passos
Testar o modelo com outros ativos financeiros.
Ajustar hiperparâmetros do LSTM (épocas, batch size, camadas).
Explorar técnicas mais avançadas, como attention mechanisms.
Implementar um serviço web para mostrar previsões em tempo real.
