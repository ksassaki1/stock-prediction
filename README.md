
# 📈 **Stock Price Prediction Project**

Este projeto utiliza um modelo **LSTM (Long Short-Term Memory)** e o **Prophet** para prever os preços das ações da **Apple Inc.**. O objetivo é comparar a capacidade desses dois modelos em identificar padrões temporais nos preços das ações e fornecer previsões precisas.

---

## 🎯 **Objetivo**
- Utilizar **LSTM** para realizar previsões de preços de ações.
- Avaliar o desempenho do modelo **LSTM** utilizando métricas adequadas.
- Demonstrar o uso do **Prophet** para comparação e análise adicional.

---

## 🛠 **Tecnologias e Ferramentas Usadas**
- **Linguagem:** Python  
- **Bibliotecas:**
  - `yfinance`: Para download dos dados históricos de ações.
  - `scikit-learn`: Para métricas e pré-processamento dos dados.
  - `TensorFlow`: Para construção e treinamento do modelo LSTM.
  - `Prophet`: Modelo de previsão desenvolvido pelo Facebook.
  - `Matplotlib`: Para visualização dos resultados.

---

## 📂 **Estrutura do Projeto**
### **Arquivos e Diretórios**
- **`stock_price_prediction.ipynb`**: Notebook principal contendo:
  - Preparação e limpeza dos dados.
  - Treinamento dos modelos **LSTM** e **Prophet**.
  - Comparação entre os dois modelos.
  - Visualização dos resultados e métricas de desempenho.

---

## 🧠 **Modelos Implementados**
- **LSTM:**  
  - Modelo de rede neural recorrente que captura padrões complexos e de longo prazo em séries temporais.
  - Útil para detectar tendências sutis em dados financeiros históricos.

- **Prophet:**  
  - Modelo projetado para capturar tendências e sazonalidades de forma eficiente, especialmente em séries temporais com dados ausentes ou eventos sazonais.

---

## 🚀 **Próximos Passos**
- Testar o modelo com outros ativos financeiros para generalização.
- **Ajustar hiperparâmetros do LSTM**:  
  - Explorar o número de épocas, tamanho de lote (batch size) e a profundidade das camadas.
- Explorar **técnicas avançadas**:  
  - Implementar mecanismos de **attention** para melhorar a previsão.
- Desenvolver um **serviço web**:  
  - Mostrar previsões em tempo real utilizando um framework como **Streamlit** ou **Flask**.

---

## 📊 **Sugestões de Aperfeiçoamento**
1. **Validação Cruzada:** Implementar uma técnica como **TimeSeriesSplit** para uma validação mais robusta.
2. **Early Stopping e Model Checkpoint:** Utilizar callbacks do TensorFlow para evitar overfitting.
3. **Implementação de um Dashboard:** Adicionar um **dashboard interativo** utilizando **Plotly** ou **Dash** para uma melhor visualização dos resultados.
4. **Comparação com Modelos Tradicionais:** Incluir modelos como ARIMA ou SARIMA para enriquecer a análise comparativa.
5. **Backtesting:** Realizar um backtest para avaliar o desempenho das previsões em dados fora da amostra.

---


## 👤 **Autor**
Guilherme Koiti Tanaka Sassaki  
[LinkedIn](https://www.linkedin.com/in/guilherme-sassaki-10b81ba7/)
