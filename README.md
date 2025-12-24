# Olist Orders Analysis

Este projeto tem como objetivo praticar análise de dados utilizando Python, Pandas e NumPy,
com foco no desenvolvimento de habilidades essenciais para estágios e posições júnior em dados.

A análise utiliza dados reais do e-commerce brasileiro Olist, explorando pedidos e itens de pedidos
para construir métricas básicas, entender distribuições e identificar padrões nos dados.

---

## Fonte dos dados

Os dados utilizados neste projeto foram obtidos no Kaggle:

- Dataset: Brazilian E-Commerce Public Dataset by Olist
- Link: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

Neste projeto inicial, são utilizados apenas os arquivos:
- `olist_orders_dataset.csv`
- `olist_order_items_dataset.csv`

---

## Arquitetura do projeto

O projeto segue uma arquitetura de **Pipeline Analítico em Camadas (ELT simples)**, separando claramente
as etapas de exploração, transformação e análise dos dados.

As camadas são:

1. **Exploração dos dados**  
   Entendimento das tabelas, colunas, tipos e limitações dos dados.

2. **Transformação / Modelagem**  
   Construção de entidades analíticas, como o pedido agregado.

3. **Métricas e Análise**  
   Geração e interpretação de métricas descritivas e distribuições.

---

## Tecnologias utilizadas

- Python
- Pandas
- NumPy
- Jupyter Notebook
- Git

---

## Estrutura do projeto

```text
olist-orders-analysis/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
├── environment/
├── README.md
└── .gitignore
