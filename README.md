# 🛒 Dashboard de Vendas

## 📊 Sobre o Projeto

Este projeto consiste em um **Dashboard Interativo de Vendas** desenvolvido em Python utilizando a biblioteca Streamlit.

A aplicação permite visualizar, analisar e explorar dados de vendas de forma dinâmica e intuitiva, oferecendo informações importantes sobre o desempenho comercial, como receita total, quantidade de vendas, faturamento por estado, categorias de produtos e desempenho dos vendedores.

Além disso, o projeto conta com uma página dedicada à consulta e exportação de dados, permitindo que o usuário aplique filtros personalizados e faça o download dos resultados em formato CSV.

O objetivo é transformar dados brutos de vendas em informações relevantes para auxiliar na análise e na tomada de decisões.

## 🌐 Acesse o Projeto

Você pode acessar a versão online do dashboard através do link abaixo:

🔗 **[Acessar Dashboard de Vendas no Streamlit]([[https://dashboardvendas-aeopvpnpiwboigrpnkkrvo.streamlit.app)]])**

## 🚀 Funcionalidades

### 📁 Dataset de Vendas

- Visualização dos dados em uma tabela interativa.
- Seleção personalizada das colunas que serão exibidas.
- Filtro por categoria de produto.
- Filtro por faixa de preço.
- Filtro por período da compra.
- Exibição da quantidade de linhas e colunas do resultado.
- Exportação dos dados filtrados para CSV.
- Personalização do nome do arquivo exportado.

### 📈 Dashboard de Vendas

- Filtro de vendas por vendedor.
- Visualização da receita total.
- Exibição da quantidade total de vendas.
- Gráfico geográfico de receita por estado.
- Gráfico de receita mensal.
- Gráfico de receita por estado.
- Gráfico das categorias de produtos com maior receita.
- Ranking dos 10 vendedores com maior receita.
- Ranking dos 10 vendedores com maior quantidade de vendas.

## 🛠️ Tecnologias Utilizadas

As principais tecnologias e bibliotecas utilizadas no desenvolvimento do projeto foram:

- **Python** — Linguagem de programação.
- **Streamlit** — Desenvolvimento da interface web interativa.
- **Pandas** — Manipulação, transformação e análise dos dados.
- **Plotly Express** — Criação de gráficos interativos.
- **JSON** — Armazenamento e carregamento dos dados de vendas.

## 📂 Estrutura do Projeto

```text
├── dados/
│   └── vendas.json
│
├── dataset.py
├── graficos.py
├── utils.py
├── app.py
├── dataset_vendas.py
├── requirements.txt
└── README.md
```

### Descrição dos arquivos

| Arquivo | Descrição |
|---|---|
| `dados/vendas.json` | Arquivo com os dados de vendas utilizados no projeto. |
| `dataset.py` | Responsável pelo carregamento e preparação dos dados. |
| `graficos.py` | Contém a criação dos gráficos utilizados no dashboard. |
| `utils.py` | Contém funções auxiliares para análise, formatação e exportação dos dados. |
| `app.py` | Aplicação principal do dashboard de vendas. |
| `dataset_vendas.py` | Página de visualização e exportação do dataset. |
| `requirements.txt` | Lista das dependências necessárias para executar o projeto. |

> Os nomes dos arquivos podem ser ajustados conforme a organização utilizada no repositório.

## ⚙️ Como Executar o Projeto

### 1. Clone o repositório

```bash
git clone https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
```

### 2. Acesse a pasta do projeto

```bash
cd SEU-REPOSITORIO
```

### 3. Crie um ambiente virtual

```bash
python -m venv venv
```

### 4. Ative o ambiente virtual

**Windows:**

```bash
venv\Scripts\activate
```

**Linux ou macOS:**

```bash
source venv/bin/activate
```

### 5. Instale as dependências

```bash
pip install -r requirements.txt
```

Caso ainda não exista um arquivo `requirements.txt`, instale as bibliotecas manualmente:

```bash
pip install streamlit pandas plotly
```

### 6. Execute a aplicação

Para iniciar o dashboard:

```bash
streamlit run app.py
```

Para executar a página de consulta do dataset:

```bash
streamlit run dataset_vendas.py
```

Após executar o comando, o Streamlit disponibilizará a aplicação no navegador.

## 📊 Análises Disponíveis

O dashboard apresenta diferentes perspectivas dos dados de vendas:

- **Receita por Estado:** permite identificar as regiões com maior faturamento.
- **Receita Mensal:** possibilita acompanhar a evolução das vendas ao longo do tempo.
- **Receita por Categoria:** identifica as categorias de produtos com melhor desempenho financeiro.
- **Desempenho dos Vendedores:** permite comparar os vendedores com base na receita gerada e na quantidade de vendas realizadas.

Essas análises possibilitam identificar tendências, avaliar o desempenho comercial e compreender melhor o comportamento das vendas.

## 🎯 Objetivos do Projeto

Este projeto foi desenvolvido com o objetivo de:

- Praticar manipulação e análise de dados utilizando Pandas.
- Desenvolver dashboards interativos com Streamlit.
- Criar visualizações de dados utilizando Plotly.
- Aplicar filtros dinâmicos em conjuntos de dados.
- Trabalhar com arquivos JSON e exportação de dados CSV.
- Desenvolver habilidades em análise de dados e Business Intelligence (BI).

## 👨‍💻 Autor

Desenvolvido como projeto de estudo e prática em Python, análise de dados e desenvolvimento de dashboards interativos.

