# IND2627 - Introducción al Aprendizaje Estadístico

Este repositorio contiene las tareas, ejercicios y actividades del curso **IND2627 - Introducción al Aprendizaje Estadístico**. El contenido cubre diversos temas de machine learning y análisis estadístico, implementados en Python usando Jupyter Notebooks.

## 📚 Contenido del Repositorio

### Tareas (Homeworks)

#### **Homework 1 - Regresión Lineal Múltiple**
- **Exercise 1**: Análisis exploratorio de datos y regresión lineal múltiple
- **Exercise 2**: Validación de modelos y análisis de residuos
- **Exercise 3**: Predicción y evaluación de modelos
- **Datasets**: `Default.csv`, `Insurance.csv`

#### **Homework 2 - Métodos de Regularización y Selección de Variables**
- **Exercise 1**: Best Subset Selection, Forward y Backward Stepwise Selection (Dataset: Hitters)
- **Exercise 2**: Ridge y LASSO Regression (Dataset: Hitters)
- **Exercise 3**: Principal Component Analysis (PCA) y Principal Component Regression (PCR) (Dataset: Boston Housing)
- **Topics**: Regularización L1/L2, selección de características, reducción de dimensionalidad

#### **Homework 3 - Modelos No Lineales**
- **Exercise 1**: Polynomial Regression y Regression Splines (Dataset: Wage)
- **Exercise 2**: Smoothing Splines y Local Regression
- **Exercise 3**: Generalized Additive Models (GAMs)
- **Dataset**: `Wage.csv`

#### **Homework 4 - Support Vector Machines**
- **Notebook principal**: `Homework_4.ipynb`
- **Contenido**:
  - Maximal Margin Classifier
  - Support Vector Classifier
  - Kernels (Linear, Polynomial, RBF)
  - Aplicación práctica en clasificación binaria
- **Dataset**: `Heart.csv` (Heart Disease dataset)

### Actividades Extra

#### **Lecture 10 - Support Vector Machines**
- **Notebook**: `SVM_exercise.ipynb`
- **Dataset**: `Heart.csv`
- Ejercicios adicionales sobre conceptos teóricos y prácticos de SVM

## 🛠️ Tecnologías y Bibliotecas

El proyecto utiliza las siguientes bibliotecas de Python:

### Análisis de Datos y Manipulación
- `pandas` - Manipulación y análisis de datos
- `numpy` - Operaciones numéricas y álgebra lineal

### Machine Learning y Modelado Estadístico
- `scikit-learn` - Algoritmos de machine learning y preprocesamiento
- `statsmodels` - Modelos estadísticos y pruebas
- `patsy` - Fórmulas estadísticas estilo R

### Visualización
- `matplotlib` - Visualizaciones básicas
- `seaborn` - Visualizaciones estadísticas avanzadas

### Notebooks
- `jupyter` - Entorno de desarrollo interactivo
- `ipython` - Shell interactivo mejorado

## 📋 Requisitos

### Opción 1: Usar pip (requirements.txt)
```bash
pip install -r requirements.txt
```

### Opción 2: Usar Conda (environment.yml)
```bash
conda env create -f environment.yml
conda activate ind2627-stats
```

## 🚀 Uso

1. Clonar el repositorio:
```bash
git clone https://github.com/santiago-v-2013/IND2627_Intro_Stat.git
cd IND2627_Intro_Stat/Subject
```

2. Instalar las dependencias (ver sección de Requisitos)

3. Iniciar Jupyter Notebook:
```bash
jupyter notebook
```

4. Navegar a la carpeta deseada y abrir el notebook correspondiente

## 📂 Estructura de Directorios

```
Subject/
├── README.md
├── LICENSE
├── requirements.txt
├── environment.yml
├── homework_1/
│   ├── exercise_1.ipynb
│   ├── exercise_2.ipynb
│   ├── exercise_3.ipynb
│   └── datasets/
│       ├── Default.csv
│       └── Insurance.csv
├── homework_2/
│   ├── exercise_1.ipynb
│   ├── exercise_2.ipynb
│   └── exercise_3.ipynb
├── homework_3/
│   ├── exercise_1.ipynb
│   ├── exercise_2.ipynb
│   ├── exercise_3.ipynb
│   └── datasets/
│       └── Wage.csv
├── homework_4/
│   ├── Homework_4.ipynb
│   └── datasets/
│       └── Heart.csv
└── Extra_Activities/
    └── Lecture_10/
        ├── SVM_exercise.ipynb
        └── datasets/
            └── Heart.csv
```

## 📖 Temas Cubiertos

1. **Regresión Lineal** - Modelos lineales simples y múltiples
2. **Regularización** - Ridge, LASSO, Elastic Net
3. **Selección de Variables** - Best Subset, Forward/Backward Selection
4. **Reducción de Dimensionalidad** - PCA, PCR
5. **Modelos No Lineales** - Polinomios, Splines, GAMs
6. **Support Vector Machines** - Clasificación con diferentes kernels
7. **Validación de Modelos** - Cross-validation, Test/Train split
8. **Evaluación de Modelos** - MSE, RMSE, R², AIC, BIC, ROC-AUC

## 📝 Notas Importantes

- Algunos datasets se cargan desde fuentes externas cuando no están disponibles localmente
- El dataset Boston Housing se utiliza con precaución debido a consideraciones éticas mencionadas en los notebooks
- Todos los notebooks incluyen documentación detallada y explicaciones paso a paso

## 👤 Autor

Santiago V.

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

## 🎓 Curso

**IND2627 - Introducción al Aprendizaje Estadístico**  
Doctorado - Universidad de Chile
