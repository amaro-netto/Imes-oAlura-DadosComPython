# Imersão Dados com Python: Dashboard Interativo de Salários 🚀

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)
[![Plotly](https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white)](https://plotly.com/)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io/)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)](https://code.visualstudio.com/)

> Este projeto foi desenvolvido durante a **Imersão de Dados com Python** da Alura. O objetivo é realizar a análise exploratória e o tratamento de uma base de dados sobre salários na área de tecnologia, culminando na construção e implantação de um dashboard interativo.

---

### 📁 Estrutura do Projeto

A estrutura do projeto é a seguinte:

-   `app.py`: O arquivo principal do dashboard, escrito em Streamlit.
-   `requirements.txt`: Lista todas as bibliotecas e dependências necessárias para o projeto.
-   `dF`: A base de dados ORIGINAL.
-   `dados`: A base de dados tratada, utilizada pelo dashboard.
-   `.venv/`: O ambiente virtual do projeto, que contém todas as bibliotecas instaladas.
-   `.gitignore`: Arquivo para ignorar arquivos e pastas que não devem ser enviados para o repositório, como `.venv`.

---

### 💻 Tecnologias Utilizadas

Este projeto utiliza as seguintes tecnologias:

-   **Python**: Linguagem de programação principal.
-   **Pandas**: Biblioteca para manipulação e análise de dados.
-   **NumPy**: Biblioteca para computação numérica, utilizada para lidar com valores nulos (`NaN`).
-   **Plotly**: Biblioteca para criação de visualizações e gráficos interativos, incluindo o mapa coroplético.
-   **Streamlit**: Framework para construir e implantar dashboards e aplicativos web.
-   **Visual Studio Code**: IDE (Ambiente de Desenvolvimento Integrado) utilizada no desenvolvimento.
-   **Jupyter Notebooks**: Ambiente para desenvolvimento e execução interativa do código.

---

### 🛠️ Pré-requisitos e Instalação

Para executar este projeto localmente, siga os passos abaixo:

1.  **Instale o Python 3.x** em sua máquina.
2.  **Clone o repositório** do projeto.
3.  **Abra a pasta** no VS Code.
4.  **Crie e ative um ambiente virtual** para o projeto:
    ```bash
    python -m venv venv
    # Windows: .\venv\Scripts\activate
    # macOS/Linux: source venv/bin/activate
    ```
5.  **Instale as dependências** a partir do arquivo `requirements.txt`:
    ```bash
    pip install -r requirements.txt
    ```

---

### 📝 Resumo das Aulas

#### **Aula 1: Análise e Exploração Inicial**

-   **Carregamento dos Dados:** A base de dados foi importada usando a biblioteca Pandas.
-   **Análise Exploratória:** Foram utilizados métodos como `.head()`, `.info()`, `.describe()` e `.shape` para obter uma visão geral da base, entender seus tipos de dados e dimensões.
-   **Tradução de Colunas e Categorias:** Colunas e categorias foram traduzidas para o português para facilitar a análise.

#### **Aula 2: Tratamento e Limpeza de Dados**

-   **Identificação de Nulos:** A presença de valores nulos na coluna `ano` foi identificada usando `.isnull().sum()`.
-   **Estratégias de Preenchimento:** Diferentes métodos de tratamento de nulos foram explorados.
-   **Remoção de Dados Nulos:** As linhas incompletas foram removidas, e o tipo de dado da coluna `ano` foi convertido de `float` para `int` usando `.astype()`.

#### **Aula 3: Visualização e Gráficos**

-   **Criação de Gráficos:** Foram criados gráficos estáticos de barra, histograma e boxplot usando `Pandas`, `Matplotlib` e `Seaborn`.
-   **Gráficos Interativos:** A biblioteca `Plotly` foi utilizada para construir gráficos interativos de barras, rosca e um mapa coroplético para o desafio.

#### **Aula 4: Dashboard Interativo**

-   **Criação do Dashboard:** Um aplicativo `app.py` foi desenvolvido para criar um dashboard interativo com **Streamlit**.
-   **Filtros e Métricas:** Uma barra lateral foi implementada para filtros, e métricas principais (salário médio, máximo, etc.) foram adicionadas à página.
-   **Integração de Gráficos:** As visualizações criadas nas aulas anteriores foram integradas ao dashboard principal.

---

### 🚀 Como Executar o Dashboard

Para rodar o dashboard localmente, use o comando no terminal do VS Code:
```bash
streamlit run app.py
```
---

### 📄 Licença

Este projeto é distribuído sob a licença MIT. Para mais detalhes, veja o arquivo `LICENSE` (se aplicável).

---

### 🧑‍💻 Autor

-   **Amaro Netto
