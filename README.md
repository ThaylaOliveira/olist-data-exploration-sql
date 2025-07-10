# Olist SQL Analytics — BigQuery + Power BI

Este projeto tem como objetivo explorar a base pública da Olist utilizando SQL no Google BigQuery para responder perguntas analíticas sobre comportamento de clientes, logística, vendas e avaliações. Posteriormente, os resultados serão visualizados em dashboards com Power BI.

---

## 🧠 Objetivos

- Realizar uma análise exploratória dos dados com SQL em ambiente cloud (BigQuery)
- Praticar perguntas analíticas com foco em produto, logística e cliente
- Visualizar os insights em um dashboard no Power BI

---

## 📊 Stack utilizada

- **Google BigQuery (SQL)**
- *(Planejado)* **Looker** para visualização
- *(Planejado)* Python para EDA visual com gráficos

---

## O que você encontrará aqui?

- Funções de agregação como COUNT, SUM, AVG, MIN, MAX, ROUND, EXTRACT, TO_CHAR, etc.
- Cláusulas como SELECT, WHERE, HAVING, GROUP BY, ORDER BY, LEFT JOIN, INNER JOIN, CASE WHEN, LIMIT.
- Funções de janela como RANK, com ROW, OVER, PARTITION BY.
- CTEs e subconsultas.

---

## 🗃️ Fonte de dados

- [Base de dados da Olist no Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

---
## 📂 Data Schema

![Visualização Schema](2-olist_schema.png)

---
## ❓ Perguntas respondidas

Foram respondidas mais de 39 perguntas usando SQL, entre elas:

- Quantos clientes únicos existem no banco de dados?
- Qual a receita total do período analisado?
- Quais são as 5 cidades com mais pedidos?
- Qual é o valor médio do frete por pedido?
- Quais categorias de produtos têm o maior e o menor volume de vendas?
- Quantos pedidos foram entregues com atraso?
- Qual vendedor tem o maior valor médio de pedido?

*A lista completa de perguntas está disponível no arquivo [`olist_queries.sql`](https://github.com/ThaylaOliveira/olist-data-exploration-sql/blob/main/1-business_questions.txt).*

---

## 📌 Próximas etapas

- Criar uma análise visual exploratória com Python
- Construir um dashboard no Looker com KPIs e filtros interativos

---

## 👩‍💻 Sobre Mim

Sou Thayla Oliveira, entusiasta em transformar dados em decisões.  

📫 [LinkedIn](https://www.linkedin.com/in/thayla-oliveira) | [GitHub](https://github.com/ThaylaOliveira)

