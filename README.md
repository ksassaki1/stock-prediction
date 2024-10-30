# Previsão de Preços de Ações com LSTM e Comparação com Prophet

## Descrição do Projeto
Este projeto utiliza um modelo **LSTM (Long Short-Term Memory)** e **Prophet** para prever os preços das ações da Apple Inc. A abordagem inclui uma **comparação com uma baseline simples** (previsão baseada no último valor observado), demonstrando como modelos mais sofisticados podem melhorar a precisão das previsões.

---

## Objetivo
- Utilizar **LSTM** para realizar a previsão de preços de ações.
- Comparar o desempenho do modelo **LSTM** com uma **baseline simples**.
- Demonstrar o uso do **Prophet** para comparação.

---

## Tecnologias e Ferramentas Usadas
- **Linguagem:** Python  
- **Bibliotecas:**
  - `yfinance`: Para download dos dados históricos de ações.
  - `scikit-learn`: Para métricas e pré-processamento.
  - `TensorFlow`: Para construção do modelo LSTM.
  - `Prophet`: Modelo de previsão desenvolvido pelo Facebook.
  - `Matplotlib`: Para visualização de gráficos.

---

## Estrutura do Projeto
- **`stock_price_prediction.ipynb`**: Contém o notebook principal com:
  - Preparação dos dados
  - Treinamento dos modelos
  - Comparação entre **LSTM**, **Prophet** e a baseline
  - Visualizações dos resultados

---

## Modelos Implementados
1. **LSTM**: Focado em capturar padrões complexos e de longo prazo em séries temporais.
2. **Prophet**: Modelo de previsão projetado para capturar tendências e sazonalidades.
3. **Baseline**: Previsão usando o último valor conhecido, servindo como referência simples.

---

## Resultados
- **LSTM RMSE**: 7.86  
- **Baseline RMSE**: 2.71  

Apesar do **LSTM** ser mais poderoso, a baseline teve um desempenho competitivo, destacando a dificuldade de prever séries temporais financeiras.

---

## Próximos Passos
- **Testar o modelo com outros ativos financeiros**.
- **Ajustar hiperparâmetros** do LSTM (épocas, batch size, camadas).
- Explorar técnicas mais avançadas, como **attention mechanisms**.
- Implementar um **serviço web** para mostrar previsões em tempo real.

---

