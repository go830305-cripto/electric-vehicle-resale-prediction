# Electric Vehicle Resale Prediction

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/go830305-cripto/electric-vehicle-resale-prediction/blob/main/notebooks/electric-vehicle-resale-prediction.ipynb)

## 🚀 Sobre o Projeto
Este projeto usa Machine Learning para prever o valor de revenda de veículos elétricos com base em atributos como bateria, autonomia, preço inicial, etc.

## 📊 Tecnologias
- Python 3.10+
- pandas, numpy, scikit-learn
- matplotlib, seaborn
- xgboost (opcional)
- Jupyter Notebook

## 🏗️ Estrutura do Repositório
data/ | notebooks/ | README.md | requirements.txt | .gitignore

## 📝 Instalação
1. Clone o repositório:
```bash
git clone https://github.com/go830305-cripto/electric-vehicle-resale-prediction.git
cd electric-vehicle-resale-prediction
Crie e ative o ambiente virtual:

# macOS / Linux
python3 -m venv env
source env/bin/activate

# Windows
python -m venv env
env\Scripts\activate
Instale as dependências:

pip install -r requirements.txt
📊 Como usar
Abra o notebook notebooks/electric-vehicle-resale-prediction.ipynb (VS Code ou Jupyter Notebook).
O dataset está em data/electric_vehicle_analytics.csv.

⚙️ Dependências
pandas

numpy

scikit-learn

matplotlib

seaborn

xgboost

🔗 Contato
GitHub: go830305-cripto


---

### **2️⃣ requirements.txt**

Crie `requirements.txt` na mesma pasta:

pandas
numpy
scikit-learn
matplotlib
seaborn
xgboost


---

### **3️⃣ .gitignore**

Crie `.gitignore` na mesma pasta:

pycache/
*.pyc
.ipynb_checkpoints/
.env


---

## **Passo 3 — Enviar tudo para o GitHub**

1. Abra o **Terminal na pasta** `electric-vehicle-resale-prediction`  
2. Copie e cole **tudo de uma vez**:

```bash
git init
git add .
git commit -m "Adicionar arquivos finais"
git remote remove origin 2>/dev/null
git remote add origin https://github.com/go830305-cripto/electric-vehicle-resale-prediction.git
git branch -M main
git push -u origin main --force