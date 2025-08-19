# 📈 Proyecto Telecom X – Modelos Predictivos de Cancelación de Clientes

## 🚀 Descripción
Este proyecto corresponde a la **Parte 2** del análisis de evasión de clientes en Telecom X.  
En esta fase, se aplican **modelos de Machine Learning supervisados** para anticipar la cancelación de clientes (*churn*) y proponer estrategias de retención.  

El trabajo forma parte del programa de especialización en **Ciencia de Datos – Alura + ONE**.  

---

## 🔬 Objetivo
Construir y evaluar modelos predictivos para:  
- Identificar clientes en riesgo de cancelar.  
- Comparar el desempeño entre diferentes algoritmos (Logistic Regression, Random Forest, KNN).  
- Generar información accionable que sirva de base para decisiones estratégicas en Telecom X.  

---

## 🛠️ Tecnologías utilizadas
- Python 3.10+  
- Pandas, NumPy, Scikit-learn  
- Matplotlib, Seaborn, Plotly  
- Google Colab  

---

## 📁 Estructura del proyecto
- `TelecomX_Modelos.ipynb`: Notebook con el modelado predictivo, métricas y visualizaciones.  
- `Informe_Final_Modelos.md`: Informe final con resultados de la Parte 2.  
- `imagenes_word`: Carpeta con imágenes utilizadas en el informe (importante descargar junto al `.md`).  
- `README.md`: Archivo de referencia del proyecto.  
- `TelecomX_diccionario.md`: Diccionario de variables del dataset.  
- `TelecomX_Data.json`: Archivo de datos (también accesible desde la URL del reto).  
- `Analisis_graficas.word`: Análisis detallado de las gráficas exploratorias (Parte 1).  

---

## 📊 Modelos implementados
- **Logistic Regression**: Modelo interpretable, usado como *baseline*.  
- **Random Forest**: Modelo con mejor equilibrio entre precisión y recall.  
- **KNN**: Modelo alternativo, sensible al tamaño de los datos.  

---

## 📅 Principales hallazgos
- **Random Forest** alcanzó un desempeño superior al 80% en accuracy y AUC, siendo el más recomendable para producción.  
- El contrato **Month-to-Month**, el método de pago **Electronic Check** y la ausencia de servicios adicionales son los principales predictores del churn.  
- Clientes con **alta factura mensual** y **baja antigüedad** son los más propensos a cancelar en la etapa inicial.  

---

## 🔧 Cómo ejecutar el proyecto
1. Abre el archivo `TelecomX_Modelos.ipynb` en **Google Colab**.  
2. Asegúrate de contar con las bibliotecas necesarias (`pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `plotly`).  
3. Ejecuta todas las celdas desde la preparación de datos hasta la evaluación de los modelos.  

---

## 📊 Requisitos
- Python 3.10+  
- Bibliotecas de análisis y machine learning instaladas (o entorno Colab).  
- Dataset en formato `.csv` o `.json` cargado desde la API proporcionada.  

---

## 👥 Autora
Proyecto desarrollado por **Bibiana Trujillo Cedeño**, participante del programa **ONE + Alura LATAM**, Especialización en Ciencia de Datos.  

---

Informe: https://github.com/BibiTC/DS-challenge-telecom-X-Parte2.git
