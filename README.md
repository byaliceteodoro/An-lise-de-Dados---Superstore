# 📊 Análise de Dados - Superstore

## 🎯 Objetivo

Este projeto tem como objetivo analisar o desempenho de vendas, lucratividade e o impacto de descontos em um dataset de varejo, utilizando SQL Server para exploração de dados e (futuramente) Power BI para visualização.

---

## 🛠️ Ferramentas utilizadas

* SQL Server
* Power BI *(em desenvolvimento)*

---

## 📈 Principais análises

### 💰 Visão Geral

* Receita total: **1.13B**
* Lucro total: **1.79B**
* Total de vendas: **37.873**

⚠️ Observação: Foram identificadas possíveis inconsistências nos dados, como lucro superior à receita, indicando necessidade de validação da base.

---

### 📦 Análise por Categoria

* Furniture apresenta **baixa margem (~10%)**
* Technology e Office Supplies apresentam **alta lucratividade**

👉 Insight: Nem sempre maior venda significa maior lucro — margens variam por categoria.

---

### 🌍 Análise por Região

* West é a região **mais lucrativa**
* Central apresenta o **menor desempenho**

👉 Insight: Diferenças regionais podem indicar problemas operacionais ou estratégicos.

---

### 💣 Impacto dos Descontos

* Descontos acima de **20–30%** geram prejuízo
* Relação direta entre aumento de desconto e queda no lucro

👉 Insight: Estratégias agressivas de desconto comprometem a rentabilidade.

---

### 🚨 Produtos com maior prejuízo

* Produtos de alto valor apresentam grandes perdas com descontos elevados
* Destaque para equipamentos tecnológicos e móveis corporativos

👉 Insight: Necessidade de revisão na política de descontos para produtos específicos.

---

## 📊 Dashboard

🚧 Em desenvolvimento no Power BI

*(Aqui será incluída uma visualização interativa com os principais insights do projeto)*

---

## 📁 Estrutura do projeto

projeto-analise-superstore/
│
├── dados/
│   └── superstore.csv
│
├── sql/
│   └── analises.sql
│
├── dashboard/
│   └── (em construção)
│
└── README.md

---

## 🧠 Conclusão

A análise demonstrou que fatores como categoria, região e principalmente desconto impactam diretamente a lucratividade.
Os resultados indicam a importância de estratégias comerciais mais equilibradas para maximizar o lucro e evitar prejuízos.

---

## 👨‍💻 Autor
Alice Teodoro
