# Atividades realizadas do Bootcamp em Ciências de Dados do Atlântico Avanti

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)![Seaborn](https://img.shields.io/badge/seaborn-%2300A2C1.svg?style=for-the-badge&logo=seaborn&color=444876&logoColor=white)![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)![Markdown](https://img.shields.io/badge/Markdown-000?style=for-the-badge&logo=markdown)![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)



![GitHub](https://img.shields.io/github/license/atlantico-academy/equipe1-2024.2.svg) [![PyPI](https://img.shields.io/pypi/v/atlantico-academy-equipe2-2024.1.svg)](http://pypi.org/project/atlantico-academy-equipe2-2024.1/) [![GitHub last commit](https://img.shields.io/github/last-commit/atlantico-academy/equipe1-2024.2.svg)](https://github.com/atlantico-academy/equipe1-2024.2/commit/developer)


<p align="justify">Este repositório reúne todos os materiais e códigos do Bootcamp em Ciência de Dados do <a href="https://www.atlanticoavanti.com.br/bootcamp">Atlântico Avanti</a>, incluindo as atividades e o projeto individual feitos durante o curso. Ele serve como um recurso útil para revisar os conceitos e práticas aprendidos.</p>


## Banco de dados

<p align="justify">O conjunto de dados <a href="https://www.kaggle.com/c/titanic/data">Titanic</a> foi retirado da plataforma <a href="https://www.kaggle.com/c/titanic/data">Kaggle</a>, embora também esteja disponível em outras fontes. Amplamente utilizado para análises e projetos de aprendizado de máquina, ele fornece informações detalhadas sobre os passageiros do RMS Titanic, que afundou em 15 de abril de 1912 após colidir com um iceberg, resultando na perda de muitas vidas. O dataset inclui dados sobre embarque e sobrevivência dos passageiros, permitindo realizar análises e previsões sobre o evento. A variável principal é <b>"Survived"<b> e as variáveis usadas para prever são: <b>Pclass<b>, <b>Sex<b>, <b>Age<b>, <b>SibSp<b>, <b>Parch<b>, <b>Fare<b>, <b>Embarked<b>, <b>Class<b>, <b>Who<b>, <b>Adult_male<b>, <b>Deck<b>, <b>Embark_town<b>, <b>Alive<b> e <b>Alone<b>.</p>

## Principais Atividade Realiazadas

 - [Coleta do Conjunto de Dados](https://github.com/KesavaS2/avanti-bootcamp-cdd/blob/master/notebooks/00download_data.ipynb)
 - [Criação do Dicionário de Dados](https://github.com/KesavaS2/avanti-bootcamp-cdd/blob/master/notebooks/00download_data.ipynb)
 - [Análise Exploratória](https://github.com/KesavaS2/avanti-bootcamp-cdd/blob/master/notebooks/01-exploratory_data_analysis.ipynb)
 - [Análise Comparativa de Modelos](https://github.com/KesavaS2/avanti-bootcamp-cdd/blob/master/notebooks/02-comparative_analysis.ipynb)
    - Limpeza de dados
    - Transformação de Dados
    - Modelagem Preditiva


## Desenvolvedora

 - [Kesava Menezes](https://github.com/KesavaS2)
 

### Organização de diretórios


```
.
├── data/              # Diretório contendo todos os arquivos de dados
│   ├── external/      # Arquivos de dados de fontes externas
│   ├── interim/       # Arquivos de dados intermediários
│   ├── processed/     # Arquivos de dados processados
│   └── raw/           # Arquivos de dados originais, imutáveis
├── docs/              # Documentação gerada através da biblioteca mkdocs
├── models/            # Modelos treinados e serializados, predições ou resumos de modelos
├── notebooks/         # Diretório contendo todos os notebooks utilizados nos passos
├── references/        # Dicionários de dados, manuais e todo o material exploratório
├── src/               # Código fonte utilizado nesse projeto
│   ├── data/          # Classes e funções utilizadas para download e processamento de dados
│   ├── deployment/    # Classes e funções utilizadas para implantação do modelo
│   └── model/         # Classes e funções utilizadas para modelagem
├── app.py             # Arquivo com o código da aplicação do streamlit
├── Procfile           # Arquivo de configuração do heroku
├── pyproject.toml     # Arquivo de dependências para reprodução do projeto
├── poetry.lock        # Arquivo com sub-dependências do projeto principal
├── README.md          # Informações gerais do projeto
└── tasks.py           # Arquivo com funções para criação de tarefas utilizadas pelo invoke

```
