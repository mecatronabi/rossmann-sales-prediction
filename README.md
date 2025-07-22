## 🧠 Rossmann Sales Prediction

### 📌 Project Overview (English)
This project develops a predictive model for Rossmann store sales. It includes data acquisition through Kaggle API, exploratory data analysis (EDA), and machine learning modeling using Random Forest, XGBoost, and LightGBM. The final goal is to generate accurate daily sales predictions based on historical data and store metadata.

### 📊 Dataset
- **Source:** [Rossmann Store Sales on Kaggle](https://www.kaggle.com/competitions/rossmann-store-sales/data)
- **Access:** Downloaded using Kaggle API with token authentication.
- **Files:**
  - `train.csv`, `test.csv`: sales and store information
  - `store.csv`: store metadata

### 🔍 EDA (Exploratory Data Analysis)
- Sales and customer distribution
- Outlier detection (boxplots)
- Sales patterns by day of the week, store type, assortment
- Correlation analysis and log transformations

### 🤖 Modeling
- **Target variable:** `Sales`
- **Features used:** Promo, StateHoliday, StoreType, Assortment, DayOfWeek, etc.
- Models trained:
  - Random Forest Regressor
  - XGBoost Regressor
  - LightGBM Regressor
- Evaluation metric: RMSE (Root Mean Squared Error)

### 📂 Folder Structure
```
rossmann-sales-prediction/
│
├── data/               # Raw input data (.csv)
├── notebooks/          # Jupyter Notebooks (EDA, Modeling)
├── images/             # Charts and visualizations
├── .venv/              # Virtual environment (excluded)
├── .gitignore          # Ignore config
└── README.md           # Project documentation
```

### ⚙️ Technologies Used
- Python 3
- pandas, numpy, matplotlib, seaborn
- scikit-learn, xgboost, lightgbm
- Jupyter Notebook

### 🚀 How to Run
1. Clone the repo:
```bash
git clone https://github.com/mecatronabi/rossmann-sales-prediction.git
```
2. Create virtual environment:
```bash
python -m venv .venv
.venv\Scripts\activate
```
3. Install dependencies:
```bash
pip install -r requirements.txt
```
4. Open and run the notebooks in `/notebooks`

---

## 🧠 Predicción de Ventas de Rossmann (Español)

### 📌 Descripción del Proyecto
Este proyecto desarrolla un modelo predictivo para estimar las ventas diarias de las tiendas Rossmann. Incluye la descarga de datos mediante la API de Kaggle, análisis exploratorio de datos (EDA), y modelado con algoritmos de machine learning como Random Forest, XGBoost y LightGBM.

### 📊 Datos Utilizados
- **Fuente:** [Rossmann Store Sales en Kaggle](https://www.kaggle.com/competitions/rossmann-store-sales/data)
- **Acceso:** Descargados con la API de Kaggle
- **Archivos:**
  - `train.csv`, `test.csv`: información de ventas y tiendas
  - `store.csv`: metadatos de cada tienda

### 🔍 Análisis Exploratorio (EDA)
- Distribución de ventas y clientes
- Detección de valores atípicos (boxplots)
- Patrones de ventas por día de la semana, tipo de tienda y surtido
- Análisis de correlación y transformación logarítmica

### 🤖 Modelado
- **Variable objetivo:** `Sales`
- **Variables utilizadas:** Promo, StateHoliday, StoreType, Assortment, DayOfWeek, etc.
- Modelos entrenados:
  - Random Forest Regressor
  - XGBoost Regressor
  - LightGBM Regressor
- Métrica de evaluación: RMSE (Error Cuadrático Medio)

### 📂 Estructura de Carpetas
```
rossmann-sales-prediction/
│
├── data/               # Datos crudos (.csv)
├── notebooks/          # Notebooks de Jupyter (EDA, Modelado)
├── images/             # Gráficas y visualizaciones
├── .venv/              # Entorno virtual (excluido)
├── .gitignore          # Configuración de exclusiones
└── README.md           # Documentación del proyecto
```

### ⚙️ Tecnologías Usadas
- Python 3
- pandas, numpy, matplotlib, seaborn
- scikit-learn, xgboost, lightgbm
- Jupyter Notebook

### 🚀 ¿Cómo Ejecutarlo?
1. Clona el repositorio:
```bash
git clone https://github.com/mecatronabi/rossmann-sales-prediction.git
```
2. Crea un entorno virtual:
```bash
python -m venv .venv
.venv\Scripts\activate
```
3. Instala las dependencias:
```bash
pip install -r requirements.txt
```
4. Abre y ejecuta los notebooks en `/notebooks`

---

📌 *Created by [Nabila Isabel Padilla Resendiz](https://www.linkedin.com/in/nabilap/) — July 2025*
