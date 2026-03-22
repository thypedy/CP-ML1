# 🧠 CP-ML1 - Projeto de Machine Learning

## 📌 Descrição do Projeto

Este projeto tem como objetivo aplicar o pipeline completo de Machine Learning utilizando o dataset **Ames Housing**.

Foram desenvolvidos dois modelos:

* 🔵 **Regressão** → prever o preço de imóveis
* 🟢 **Classificação** → classificar imóveis como caros ou baratos

O projeto inclui etapas como preparação de dados, análise exploratória, engenharia de features, treinamento e avaliação dos modelos.

---

## 📊 Dataset

O dataset utilizado foi o **Ames Housing**, que contém informações detalhadas sobre imóveis, como:

* Área da casa
* Qualidade do imóvel
* Número de cômodos
* Preço de venda

Arquivo incluído no repositório:
📁 `AmesHousing.csv`

---

## ⚙️ Tecnologias Utilizadas

* Python 3.x
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook / VSCode

---

## 🚀 Como Executar o Projeto

### 🔽 1. Clonar o repositório

```bash
git clone <SEU_LINK_DO_REPOSITORIO>
cd CP-ML1
```

---

### 🐍 2. Criar ambiente virtual

```bash
python -m venv venv
```

---

### ▶️ 3. Ativar ambiente virtual

#### Windows:

```bash
venv\Scripts\activate
```

#### Linux/Mac:

```bash
source venv/bin/activate
```

---

### 📦 4. Instalar dependências

```bash
pip install pandas numpy matplotlib scikit-learn jupyter
```

---

### 📓 5. Executar o Notebook

```bash
jupyter notebook
```

Abra o arquivo:

```
projeto.ipynb
```

Ou utilize o VSCode para abrir diretamente o notebook.

---

## 📈 Etapas do Projeto

* ✔ Coleta de dados
* ✔ Preparação e limpeza dos dados
* ✔ Análise exploratória (EDA)
* ✔ Engenharia de features
* ✔ Divisão treino/teste
* ✔ Treinamento de modelos
* ✔ Avaliação com métricas

---

## 🤖 Modelos Utilizados

### 🔵 Regressão

* Linear Regression
* Métricas: MAE, RMSE, R²

### 🟢 Classificação

* K-Nearest Neighbors (KNN)
* Métricas: Accuracy, Precision, Recall, F1-score
* Avaliação adicional: Curva ROC e AUC

---

## 📊 Resultados

* 📈 R² ≈ 0.83 → bom desempenho na regressão
* 📊 AUC ≈ 0.98 → excelente desempenho na classificação

---

## 🧾 Conclusão

O projeto demonstrou a aplicação completa do pipeline de Machine Learning, evidenciando a importância da preparação dos dados e da escolha adequada de métricas para obtenção de modelos eficientes.

---

## 👨‍💻 Autores
Andrey Nagata - Rm555339
Henrique Soubhia - Rm554493
Oliver Trindade - Rm554954
Pedro Gutierre - Rm555445
William Feng - Rm555132
