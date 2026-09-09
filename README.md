# 📊 Projeto ETL com Python e Pandas

## 📌 Sobre o Projeto

Este projeto apresenta a implementação de um processo de **ETL (Extract, Transform, Load)** utilizando **Python** e a biblioteca **Pandas**.

O objetivo é demonstrar, na prática, como trabalhar com dados desde sua extração, passando pelo processo de limpeza e transformação, até a geração de uma base final pronta para análise.

O projeto foi desenvolvido em **Google Colab**, utilizando Python e Pandas para manipulação e tratamento dos dados.

---

## 🔄 Processo ETL

O projeto está dividido em três etapas principais:

### 1. 📥 Extract — Extração

Nesta etapa os dados são carregados para o ambiente Python.

São utilizadas ferramentas do Pandas para leitura e importação dos dados, permitindo trabalhar com diferentes fontes, como arquivos CSV.

Exemplo:

```python
import pandas as pd

df = pd.read_csv("dados.csv")

df.head()
```

---

### 2. 🧹 Transform — Transformação

Após a extração, os dados passam por processos de tratamento e transformação.

Entre as operações realizadas estão:

* Verificação dos dados;
* Identificação de valores nulos;
* Tratamento de dados ausentes;
* Remoção de registros duplicados;
* Padronização dos dados;
* Alteração de tipos de dados;
* Seleção e criação de colunas;
* Aplicação de filtros;
* Agrupamento de informações;
* Organização da estrutura da base.

Exemplos de operações utilizando Pandas:

```python
df.info()

df.isnull().sum()

df.drop_duplicates()

df.dropna()

df["coluna"] = df["coluna"].astype(str)
```

Também podem ser utilizadas operações de agregação:

```python
df.groupby("categoria")["valor"].sum()
```

---

### 3. 📤 Load — Carregamento

Após o tratamento, os dados são organizados em uma estrutura final que pode ser utilizada posteriormente para:

* Análise de dados;
* Criação de dashboards;
* Power BI;
* Relatórios;
* Banco de dados;
* Processos automatizados de análise.

Exemplo de exportação:

```python
df.to_csv("dados_tratados.csv", index=False)
```

---

## 🛠️ Tecnologias Utilizadas

* 🐍 **Python**
* 🐼 **Pandas**
* ☁️ **Google Colab**
* 📄 **CSV**
* 🔄 **ETL**

---

## 📚 Principais conceitos praticados

Durante o desenvolvimento do projeto foram trabalhados conceitos importantes de análise e engenharia de dados, como:

```text
Python
   ↓
Pandas
   ↓
Extração
   ↓
Limpeza
   ↓
Transformação
   ↓
Tratamento
   ↓
Organização
   ↓
Exportação
```

O projeto demonstra principalmente a utilização do Pandas para transformar uma base de dados bruta em uma estrutura mais organizada e adequada para análises posteriores.

---

## 📂 Estrutura do Projeto

```text
projeto-etl-pandas/
│
├── projeto_etl.ipynb
├── dados/
│   ├── dados_originais.csv
│   └── dados_tratados.csv
│
└── README.md
```

> A estrutura pode variar de acordo com os arquivos utilizados no projeto.

---

## ▶️ Como executar o projeto

### 1. Clone o repositório

```bash
git clone URL_DO_REPOSITORIO
```

### 2. Acesse a pasta

```bash
cd projeto-etl-pandas
```

### 3. Instale o Pandas

```bash
pip install pandas
```

### 4. Abra o notebook

O projeto pode ser executado utilizando:

* Google Colab
* Jupyter Notebook
* VS Code

---

## 🔗 Google Colab

O projeto também está disponível no Google Colab:

**[Abrir projeto no Google Colab](https://colab.research.google.com/drive/1JNgm-7KJYz9Fb_cSDV2H6_zYCh6Fry6G)**

---

## 🎯 Objetivo Profissional

Este projeto faz parte do meu portfólio de **Dados e Python**, demonstrando conhecimentos práticos em:

* Python;
* Pandas;
* Manipulação de dados;
* Limpeza de dados;
* Transformação de dados;
* Processos ETL;
* Preparação de dados para análise.

A proposta é demonstrar não apenas conhecimento da sintaxe do Pandas, mas também a capacidade de utilizar a biblioteca em um fluxo real de tratamento e preparação de dados.

---

## 👨‍💻 Autor

**Tiago da Silva Carvalho**

Projeto desenvolvido para fins de estudo, prática e construção de portfólio profissional na área de **Dados / Python / ETL**.
