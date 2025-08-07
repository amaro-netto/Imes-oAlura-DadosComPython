# Imersão Dados com Python: Análise de Salários 🚀

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)](https://code.visualstudio.com/)

> Este projeto foi desenvolvido durante a **Imersão de Dados com Python** da Alura. Ele se dedica à análise exploratória e ao tratamento de uma base de dados sobre salários na área de tecnologia, com o objetivo de extrair insights e preparar os dados para futuras análises.

### 🛠️ Pré-requisitos e Instalação

Para executar este projeto localmente, siga os passos abaixo:

1. **Instale o Python 3.x** em sua máquina.

2. **Clone o repositório** do projeto.

3. **Crie e ative um ambiente virtual:**

   ```bash
   python -m venv venv
   # No Windows: .\venv\Scripts\activate
   # No macOS/Linux: source venv/bin/activate
   ```

4. **Instale as dependências** do projeto:

   ```bash
   pip install pandas numpy
   ```

### 📝 Aulas Detalhadas

#### **Aula 1: Análise e Exploração Inicial**

* **Carregamento dos Dados:** A base de dados foi importada usando a biblioteca Pandas.

* **Análise Exploratória:** Foram utilizados métodos como `.head()`, `.info()`, `.describe()` e `.shape` para obter uma visão geral da base, entender seus tipos de dados e dimensões.

* **Tradução de Colunas e Categorias:** Com o auxílio de inteligência artificial, as colunas e as categorias (`'SE'`, `'FT'`, `'0'`, `100`) foram traduzidas para o português, tornando o dataframe mais intuitivo.

#### **Aula 2: Tratamento e Limpeza de Dados**

* **Identificação de Nulos:** A presença de 10 valores nulos na coluna `ano` foi identificada usando `.isnull().sum()`.

* **Estratégias de Preenchimento:** Diferentes métodos de tratamento de nulos foram explorados, como preenchimento por média/mediana (`.fillna()`), por propagação (`.ffill()`, `.bfill()`) e com valores fixos. A biblioteca `NumPy` foi utilizada para representar os valores nulos como `np.nan`.

* **Remoção de Dados Nulos:** As 10 linhas incompletas foram removidas de forma segura utilizando `.dropna()`, criando um novo dataframe `df_limpo`.

* **Conversão de Tipos:** O tipo de dado da coluna `ano` foi convertido de `float` para `int` usando `.astype()`, corrigindo o formato de `2025.0` para `2025`.

### 🚀 Como Executar

Para rodar o projeto, abra o arquivo `.ipynb` no VS Code ou em outra IDE compatível com Jupyter Notebooks e execute as células na ordem.

### 🧑‍💻 Autor

* Amaro Netto
