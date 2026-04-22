# 📊 Análise de Dados - Superstore

## 🎯 Objetivo

Este projeto tem como objetivo analisar o desempenho de vendas, lucratividade e o impacto de descontos em um dataset de varejo, utilizando **SQL Server para exploração de dados** e **Power BI para visualização interativa**.

---

## 🛠️ Ferramentas utilizadas

* SQL Server
* Power BI
* Vega-Lite (custom visual no Power BI)

---

## 📊 Dashboard Interativo

O dashboard foi desenvolvido no Power BI com foco em **análise exploratória e suporte à decisão**, permitindo identificar padrões de lucratividade e impacto dos descontos.

### 🔍 Principais componentes:

* KPIs de receita, lucro e volume de pedidos
* Análise de lucratividade por categoria
* Comparação de desempenho por região
* Impacto dos descontos no lucro
* Ranking de produtos com maiores prejuízos
* Painel de filtros dinâmicos (categoria, região, produto e período)

📸 **Preview do Dashboard:**

![Dashboard Superstore](https://github.com/user-attachments/assets/41c90ba5-4bf0-41ba-8f26-422f3f138f7d)

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
* Technology e Office Supplies apresentam **maior lucratividade**

👉 Insight: Alto volume de vendas não garante maior rentabilidade.

---

### 🌍 Análise por Região

* West é a região **mais lucrativa**
* Central apresenta o **menor desempenho**

👉 Insight: Diferenças regionais indicam oportunidades de otimização operacional.

---

### 💣 Impacto dos Descontos

* Descontos acima de **20–30%** tendem a gerar prejuízo
* Relação inversa entre desconto e lucro

👉 Insight: Estratégias agressivas de desconto comprometem a margem.

---

### 🚨 Produtos com maiores perdas

* Produtos de alto valor concentram maiores prejuízos
* Destaque para itens de tecnologia e móveis corporativos

👉 Insight: Necessidade de revisão na política de descontos por produto.

---

## 🎨 Diferenciais do Projeto

* Uso de **Vega-Lite dentro do Power BI** para criação de visual customizado
* Dashboard com **design focado em experiência do usuário (UX)**
* Aplicação de conceitos de **storytelling com dados**
* Estrutura organizada para análise exploratória e tomada de decisão

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
│   └── dashboard.pbix
│
└── README.md

---

## 🧠 Conclusão

A análise evidencia que **descontos são o principal fator de impacto negativo na lucratividade**, além de variações relevantes por categoria e região.

Os resultados reforçam a importância de uma estratégia comercial equilibrada, focada em maximizar receita sem comprometer a margem.

---

## 👨‍💻 Autor

Alice Teodoro
