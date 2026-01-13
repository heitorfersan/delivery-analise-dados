# 📊 Análise de Dados – Delivery de Refeições

Este projeto tem como objetivo realizar uma **análise exploratória de dados (EDA)** de um delivery de refeições, utilizando as bibliotecas **Pandas** e **NumPy**, simulando um cenário real de negócio.

O projeto faz parte de um desafio de curso e tem como foco a aplicação prática de conceitos fundamentais de **análise de dados**, desde o tratamento dos dados até a geração de indicadores (KPIs).

---

## 🧠 Objetivos do Projeto

- Carregar e explorar dados reais de pedidos
- Tratar valores ausentes e inconsistências
- Criar novas variáveis (engenharia de features)
- Realizar agregações e análises por item e categoria
- Analisar a evolução temporal das vendas
- Calcular indicadores importantes para o negócio
- Integrar diferentes fontes de dados (merge)

---

## 📁 Estrutura do Repositório

delivery-analise-dados/
│
├── dados/
│ ├── pedidos.csv
│ └── cardapio.csv
│
├── analise_delivery.ipynb
├── README.md
└── requirements.txt

---

## 🗂️ Descrição dos Dados

### 📄 pedidos.csv
Contém o histórico de pedidos realizados no delivery:
- **Data**: data do pedido
- **Item**: nome do item pedido
- **Quantidade**: quantidade vendida
- **Preco_Unitario**: preço cobrado por unidade

### 📄 cardapio.csv
Contém informações dos itens disponíveis no cardápio:
- **Nome_Item**: nome do item
- **Categoria**: tipo do produto (Salgados, Bebidas, etc.)
- **Preco_Base**: preço padrão do item

---

## 🔧 Tecnologias Utilizadas

- Python 3
- Pandas
- NumPy
- Google Colab
- GitHub

---

## 📈 Principais Análises Realizadas

- Análise exploratória dos dados
- Criação da coluna **Receita_Item**
- Tratamento de valores nulos
- Itens mais vendidos e mais lucrativos
- Receita total por mês
- Receita por categoria de produto
- Filtros por categoria e volume de vendas
- Cálculo de KPIs:
  - Receita Total
  - Total de Itens Vendidos
  - Ticket Médio
- Cálculo de percentis usando NumPy

---

## 📊 Principais KPIs

- **Receita Total**: soma de toda a receita gerada
- **Total de Itens Vendidos**: soma das quantidades
- **Ticket Médio**: receita total dividida pelo número de pedidos
