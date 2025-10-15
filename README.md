# Analise-de-dados-olist

## Descrição
Este projeto realiza uma análise detalhada do marketplace **Olist** utilizando **Python** e **PostgreSQL**.  

Os dados foram armazenados em um banco PostgreSQL e consultados diretamente no notebook usando a biblioteca `sqlalchemy`. Cada métrica e indicador foi obtido via queries SQL antes de ser analisado em Python com Pandas, Matplotlib e outras bibliotecas presentes.  

O objetivo é explorar o comportamento de **clientes, vendedores, produtos e regiões**, identificando padrões, oportunidades de crescimento e pontos de melhoria na operação do marketplace.

---

## Objetivos do Projeto
- Compreender a evolução de clientes, pedidos e faturamento ao longo do tempo.  
- Analisar o crescimento da base de vendedores e sua distribuição geográfica.  
- Identificar categorias de produtos mais vendidas e de maior faturamento.  
- Avaliar métodos de pagamento mais utilizados e ticket médio por estado/região.  
- Examinar eficiência logística, tempo médio de entrega e percentual de cancelamentos.  
- Gerar insights estratégicos para expansão, fidelização de clientes e otimização do marketplace.

---

## Dados Utilizados
- **Fonte dos Dados**: Dataset Olist  
- **Descrição**: Contém informações de pedidos, clientes, vendedores, produtos, categorias, métodos de pagamento e logística.  
- **Período analisado**: Setembro de 2016 a Agosto de 2018
- Os datasets do Olist não estão incluídos neste repositório devido ao tamanho. Para utilizar o notebook, você deve baixar os arquivos CSV diretamente do Kaggle, importa-los no PostgreSQL e em seguida realizar a conexão do notebook com o banco através da biblioteca sqlalchemy:

- [Olist Datasets no Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
 

---

## Ferramentas Utilizadas
- **PostgreSQL**: armazenamento e consulta do dataset.  
- **SQL**: extração e agregação dos dados para análise.  
- **Python** e **Jupyter Notebook**: análise e visualização de dados.  
- Bibliotecas Python:
  - `pandas` – manipulação e processamento de dados  
  - `matplotlib` e `seaborn` – visualização de dados  
  - `sqlalchemy` – conexão com PostgreSQL e execução de queries SQL
  - `IPython.display` – exibição organizada de DataFrames e resultados no Jupyter Notebook
---

## Pré-requisitos
- Python 3.12 ou superior  
- PostgreSQL instalado e com o dataset carregado  
- Bibliotecas Python listadas acima  

---

## Instalação das Dependências
Execute o seguinte comando no terminal para instalar todas as bibliotecas necessárias:
```bash
python3 -m pip install pandas matplotlib seaborn sqlalchemy IPyhton
