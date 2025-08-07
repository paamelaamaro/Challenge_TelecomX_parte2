# 📊 Análise de Evasão de Clientes - Telecom

Este projeto tem como objetivo analisar os fatores que influenciam a evasão de clientes (churn) de uma empresa do setor de telecomunicações, utilizando técnicas de ciência de dados e machine learning.

---

## 📁 Sobre o Projeto

- **Tipo de problema**: Classificação binária
- **Variável alvo**: `Churn` (Sim/Não)
- **Modelo escolhido**: Random Forest
- **Técnicas aplicadas**: Limpeza de dados, balanceamento, encoding, normalização, análise exploratória, avaliação de modelos, interpretação de variáveis.

---

## 🧠 Objetivos

- Identificar clientes com maior risco de cancelamento.
- Compreender os fatores que mais influenciam a evasão.
- Propor ações para retenção de clientes com base em dados.

---

## 🛠️ Tecnologias e Bibliotecas

- Python
- Pandas / NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)

---

## 📈 Resultados

- O modelo **Random Forest** teve melhor desempenho geral:
  - **Acurácia**: 77.8%
  - **Recall (Churn)**: 60%
  - **AUC ROC**: 0.82

- Principais variáveis que influenciam a evasão:
  - Tempo de contrato (`customer.tenure`)
  - Tipo de contrato (`account.Contract`)
  - Total gasto (`account.Charges.Total`)
  - Tipo de serviço de internet
  - Serviços adicionais (segurança, suporte técnico)

---

## 🧪 Como reproduzir o projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/spaamelaamaro/Challenge_TelecomX_parte2
