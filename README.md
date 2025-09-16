# 📉 Value at Risk (VaR) – Análise de Risco em Investimentos  

Este projeto apresenta a aplicação do **Value at Risk (VaR)**, uma das métricas mais utilizadas em gestão de risco financeiro.  
O **VaR** responde à pergunta:  
> *"Qual é a perda máxima esperada de um investimento, dentro de um intervalo de confiança (ex.: 95%), em determinado período?"*  

O estudo foi aplicado nas ações do **Banco do Brasil (BBAS3)** entre **2015 e 2019**.  

---

## Tecnologias utilizadas
- Python 3.x  
- Bibliotecas:  
  - NumPy  
  - Pandas  
  - Matplotlib  
  - SciPy  
  - Jupyter  

---

## Estrutura do projeto
- **VaR.ipynb** → Notebook principal com explicações, código e cálculos.  
- **BBrasil.xlsx** → Base de dados com preços históricos da ação BBAS3.  

---

## O que você vai encontrar
-  **Conceito inicial** → explicação simples do Value at Risk.  
-  **Dados históricos** → importação e análise dos preços da ação BBAS3 (2015–2019).  
-  **Cálculo dos retornos diários** → preparação da base para o VaR.  
-  **Cálculo do VaR paramétrico** → baseado na distribuição normal.  
-  **Discussão dos resultados** → interpretação do risco encontrado.  

---

## Como executar
- Clone este repositório:  
  ```bash
  git clone https://github.com/seu-usuario/var-analise-risco.git
  cd var-analise-risco
