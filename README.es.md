# 🔗 Detección de Spam en URLs usando PLN y SVM
Este repositorio presenta un proyecto de Procesamiento de Lenguaje Natural (PLN) orientado a detectar URLs de spam mediante aprendizaje automático. El proyecto incluye limpieza de texto, extracción de características y clasificación utilizando un modelo SVM con ajuste por búsqueda en malla (*grid search*).

---

## 📁 Estructura del Proyecto

```
📦 URL-Spam-Detection/
├── explore (5).ipynb         # Notebook de Jupyter con el análisis completo
├── README.md                 # Descripción del proyecto y uso
```

---

## 📊 Conjunto de Datos

📂 Fuente: GitHub de 4Geeks Academy - `url_spam.csv`  
💡 Contenido:  
- Texto de URL  
- Etiquetas de spam (clasificación binaria)  

🔍 Limpieza inicial eliminó más de 600 entradas duplicadas  

---

## 🧹 Preprocesamiento de PLN

- ✅ Conversión a minúsculas y eliminación de *stopwords* (`nltk`)  
- 🔤 Lematización con `WordNetLemmatizer`  
- 🔧 Limpieza con expresiones regulares  
- ☁️ Nube de palabras para comparar términos de spam vs. no-spam  

---

## 🧠 Modelo y Evaluación

- ✨ Modelo: *Support Vector Machine* (SVM)  
- 🔍 Ajuste de hiperparámetros: `GridSearchCV` con `RepeatedStratifiedKFold`  
- 📈 Métricas: Reporte de clasificación con Precisión, Recall y F1-score  

---

## 🚀 Cómo Ejecutarlo

1. Clona el repositorio:

```bash
git clone https://github.com/your-username/URL-Spam-Detection.git
cd URL-Spam-Detection
```

2. Instala las dependencias:

```bash
pip install -r requirements.txt
```

3. Ejecuta el notebook:

```bash
jupyter notebook "explore.ipynb"
```

---

## 📚 Librerías Utilizadas

- `pandas`, `numpy`  
- `nltk`, `regex`  
- `matplotlib`, `wordcloud`  
- `sklearn`  

---

## 📬 Contacto

Proyecto desarrollado como parte del currículo de PLN de **4Geeks Academy**.  
¡No dudes en abrir un *issue* o hacer un *fork* del repositorio para contribuir!
