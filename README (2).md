<div align="center">

# 🤖 Programação em IA

**Fundamentos de Ciência de Dados e Aprendizado de Máquina em Python**

![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)
![spaCy](https://img.shields.io/badge/spaCy-09A3D5?logo=spacy&logoColor=white)

</div>

---

## 📖 Sobre o projeto

Este repositório reúne exercícios e práticas de **fundamentos de Ciência de Dados e Aprendizado de Máquina**, organizados em uma trilha progressiva de estudos. O conteúdo cobre:

- **Manipulação e análise de dados** com Pandas
- **Algoritmos de Machine Learning** com Scikit-Learn
- **Redes Neurais e classificação de imagens** com TensorFlow/Keras
- **Processamento de Linguagem Natural (PLN)** com spaCy

Todo o material está em **Jupyter Notebooks**, com código e explicações lado a lado, pensado para ser executado e modificado durante o estudo.

## 📑 Sumário

- [Estrutura do repositório](#-estrutura-do-repositório)
- [Conteúdo dos módulos](#-conteúdo-dos-módulos)
- [Tecnologias](#-tecnologias)
- [Como começar](#-como-começar)
- [Trilha de estudo sugerida](#-trilha-de-estudo-sugerida)
- [Autor](#-autor)
- [Licença](#-licença)

## 🗂️ Estrutura do repositório

```
.
├── 01-pandas/
│   ├── Exercício - Salários de São Francisco.ipynb
│   ├── Salaries.csv
│   ├── introducao_jupyter.ipynb
│   └── pandas_01.ipynb
├── 02-sklearn/
│   ├── comparando_modelos.ipynb
│   ├── exemplo_sklearn_01.ipynb
│   ├── exemplo_sklearn_02.ipynb
│   ├── exemplo_sklearn_03.ipynb
│   └── exemplo_sklearn_04.ipynb
├── 03-tensorflow/
│   └── Classificacao_TensorFlow_Keras.ipynb
├── 04-spacy/
│   ├── spacy_01.ipynb
│   ├── spacy_02.ipynb
│   └── texto.txt
├── requirements.txt
└── README.md
```

## 📚 Conteúdo dos módulos

### 🐼 [01-pandas](01-pandas/): Análise de dados

| Arquivo | Descrição |
|---------|-----------|
| `introducao_jupyter.ipynb` | Introdução ao uso do Jupyter Notebook |
| `pandas_01.ipynb` | Operações fundamentais com Pandas: Series, DataFrames, seleção e filtragem |
| `Exercício - Salários de São Francisco.ipynb` | Prática de análise de dados com um dataset do Kaggle |
| `Salaries.csv` | Dataset de salários usado no exercício |

### 🌲 [02-sklearn](02-sklearn/): Machine Learning clássico

| Arquivo | Descrição |
|---------|-----------|
| `exemplo_sklearn_01.ipynb` | Regressão Logística |
| `exemplo_sklearn_02.ipynb` | Árvores de Decisão |
| `exemplo_sklearn_03.ipynb` | Random Forest e Matriz de Confusão |
| `exemplo_sklearn_04.ipynb` | Support Vector Machines (SVM) |
| `comparando_modelos.ipynb` | Comparação de acurácia entre LogisticRegression, DecisionTree, RandomForest e SVC |

### 🧠 [03-tensorflow](03-tensorflow/): Redes Neurais

| Arquivo | Descrição |
|---------|-----------|
| `Classificacao_TensorFlow_Keras.ipynb` | Rede Neural Sequencial para classificação de imagens com o dataset Fashion MNIST |

### 💬 [04-spacy](04-spacy/): Processamento de Linguagem Natural

| Arquivo | Descrição |
|---------|-----------|
| `spacy_01.ipynb` | Introdução ao Processamento de Linguagem Natural com spaCy |
| `spacy_02.ipynb` | Leitura do arquivo `texto.txt` e análise de PLN |
| `texto.txt` | Texto em português usado nos experimentos de PLN |

## 🛠️ Tecnologias

| Biblioteca | Uso no projeto |
|------------|----------------|
| [Pandas](https://pandas.pydata.org/) | Manipulação e análise de dados |
| [NumPy](https://numpy.org/) | Computação numérica |
| [Matplotlib](https://matplotlib.org/) | Visualização de dados |
| [scikit-learn](https://scikit-learn.org/) | Algoritmos de Machine Learning |
| [TensorFlow / Keras](https://www.tensorflow.org/) | Redes Neurais e Deep Learning |
| [spaCy](https://spacy.io/) | Processamento de Linguagem Natural |
| [Jupyter](https://jupyter.org/) | Ambiente interativo de notebooks |

## 🚀 Como começar

### Pré-requisitos

- Python 3.9 ou superior (confira a compatibilidade do TensorFlow com a sua versão)
- Git
- Jupyter Notebook, JupyterLab ou VS Code com a extensão Jupyter

### Instalação

**1. Clone o repositório**

```bash
git clone https://github.com/GalvaoLabs/programacao-ia-generativa.git
cd programacao-ia-generativa
```

**2. Crie e ative um ambiente virtual (recomendado)**

```bash
python -m venv venv

# Linux/macOS
source venv/bin/activate

# Windows
venv\Scripts\activate
```

**3. Instale as dependências**

```bash
pip install -r requirements.txt
```

Ou, se preferir, instale manualmente:

```bash
pip install pandas numpy matplotlib scikit-learn tensorflow spacy jupyter
```

**4. Baixe o modelo de idioma do spaCy em português**

```bash
python -m spacy download pt_core_news_sm
```

### Executando os notebooks

```bash
jupyter notebook
```

Navegue até a pasta do módulo desejado, abra o notebook e execute as células em ordem, de cima para baixo.

> 💡 **Dica:** os notebooks do módulo `04-spacy` e do exercício de salários leem arquivos locais (`texto.txt` e `Salaries.csv`). Execute-os a partir da própria pasta do módulo para que os caminhos funcionem.

## 🧭 Trilha de estudo sugerida

```
Jupyter → Pandas → Scikit-Learn → TensorFlow/Keras → spaCy
```

1. **Ambiente:** `introducao_jupyter.ipynb`
2. **Dados:** `pandas_01.ipynb` e o exercício de salários
3. **Machine Learning:** `exemplo_sklearn_01` a `04`, finalizando com `comparando_modelos`
4. **Deep Learning:** `Classificacao_TensorFlow_Keras.ipynb`
5. **PLN:** `spacy_01` e `spacy_02`

## 👤 Autor

**Miguel Henrique S. Galvão**

[![GitHub](https://img.shields.io/badge/GitHub-GalvaoLabs-181717?logo=github&logoColor=white)](https://github.com/GalvaoLabs)

## 📄 Licença

Projeto de uso livre para fins educacionais.
