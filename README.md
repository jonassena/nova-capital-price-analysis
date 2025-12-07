# 🚀 Análise de Diferencial de Preço Ponderado (WAPD) e Potencial de Margem - Nova Capital

### Desafio: Inteligência de Mercado (IM) e Otimização de Preços

Este projeto apresenta a metodologia e os resultados do Case Técnico de Inteligência de Mercado. O objetivo foi diagnosticar o posicionamento de preço da empresa (Nova Capital) versus a concorrência e quantificar o potencial de recuperação de margem.

---

## 💰 RESULTADO FINANCEIRO CHAVE

Através da identificação e ajuste de preço de 10 SKUs estratégicos no Quadrante Q1, a análise projeta um potencial de recuperação de **R$ 313.447,54** em Margem Bruta em um período de 6 meses.

---

## 🧠 Metodologia e Modelagem

A análise foi conduzida em três fases principais:

| Fase | Objetivo Analítico | KPI Chave |
| :--- | :--- | :--- |
| **I. Preparação** | Limpeza de dados transacionais e preços da concorrência, cálculo do **Diferencial de Preço Ponderado (WAPD)**. | WAPD (diferencial_preco_ponderado) |
| **II. Estratégia** | Segmentação de todo o portfólio em Matriz de 4 Quadrantes (Alto/Baixo Volume vs. Caro/Barato) e Análise de Inconsistência Regional. | Classificação de Quadrantes (Q1, Q2, Q3, Q4) |
| **III. Quantificação** | Definição de Preço Alvo e Cálculo do Ganho Financeiro (Margem Potencial). | Total de Margem Potencial (R$) |

### Matriz de Quadrantes (Diagnóstico)

O WAPD foi usado como eixo principal para identificar os 20 SKUs mais críticos:
* **Q1 (Oportunidade de Margem):** 10 SKUs com preços excessivamente baixos (WAPD muito negativo).
* **Q2 (Risco de Market Share):** 10 SKUs com preços excessivamente altos (WAPD muito positivo).

---

## 🎯 Principais Insights (Inconsistência Regional)

1.  **Potencial de Preço:** O ajuste de preço é direcionado apenas para os SKUs do Q1, cuja precificação está abaixo da concorrência, gerando o KPI de Margem.
2.  **Inconsistência Operacional:** O SKU **82729** (classificado como Risco de Market Share) apresentou uma **faixa de variação de preço de 128,12%** entre as regiões de venda, indicando uma falha grave na execução da política de preço regional que deve ser corrigida imediatamente.

---

## 🛠️ Ferramentas

* **Linguagem:** Python (Pandas e NumPy)
* **Ambiente:** Google Colab
* **Entrega:** Dashboard Protótipo em Power BI

### 📁 Estrutura do Repositório

* `Case_Nova_Casa.ipynb`: Código-fonte completo (Metodologia e Resultados).
* `case_im_tb1.csv` e `case_im_tb2.csv`: Dados brutos utilizados na análise.
