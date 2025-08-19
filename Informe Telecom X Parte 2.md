# 📈 Informe Final – Predicción de Evasión de Clientes (Parte 2)

## 🌐 Proyecto: Telecom X – Modelos Predictivos de Cancelación de Clientes

---

## 🚀 1. Introducción  

- **Empresa:** Telecom X  
- **Problema:** La tasa de cancelación de clientes afecta el crecimiento sostenible de la compañía.  
- **Objetivo del proyecto:** Aplicar técnicas de modelado predictivo que permitan anticipar el *churn*, identificar clientes en riesgo y aportar información estratégica para la toma de decisiones.  

---

## 🛠️ 2. Metodología  

La fase de modelado se construyó sobre los hallazgos de la Parte 1 del proyecto. Las principales etapas fueron:

- **Preparación de los datos:** selección de variables relevantes, partición en entrenamiento y prueba.  
- **Construcción de modelos supervisados:** Logistic Regression, Random Forest y KNN.  
- **Evaluación comparativa:** métricas de desempeño (AUC, Recall, Precision, F1 y Accuracy).  
- **Visualización y análisis:** uso de matrices de confusión y reportes de clasificación.  

---

## 📊 3. Resultados de Modelado  

| Modelo              | Accuracy | Recall | Precision | F1   | AUC  |
|---------------------|----------|--------|-----------|------|------|
| Logistic Regression | ~0.78    | ~0.70  | ~0.50     | ~0.58| ~0.78|
| Random Forest       | ~0.84    | ~0.75  | ~0.55     | ~0.63| ~0.84|
| KNN                 | ~0.80    | ~0.68  | ~0.48     | ~0.56| ~0.80|

**Principales observaciones:**  
- Random Forest obtuvo el mejor equilibrio entre precisión y capacidad de detección de clientes que cancelan.  
- Logistic Regression es más interpretable y útil como *baseline*.  
- KNN mostró desempeño aceptable, aunque sensible al tamaño de los datos.  

---

## 🔎 4. Hallazgos Clave  

Los factores más influyentes en la cancelación siguen siendo:  

- Contrato mes a mes (*Month-to-Month*).  
- Método de pago electrónico (*Electronic Check*).  
- Falta de servicios adicionales (*OnlineSecurity, TechSupport, DeviceProtection*).  
- Baja antigüedad en el servicio (*tenure* bajo).  

📌 Los clientes con **altos cargos mensuales** y **bajos cargos acumulados** son los más vulnerables en la etapa inicial.  

---

## 📉 5. Implicaciones para el Negocio  

- Random Forest puede implementarse como herramienta predictiva para segmentar a los clientes en riesgo.  
- La empresa puede actuar de manera proactiva con campañas de retención dirigidas a los segmentos críticos.  
- El valor agregado está en **integrar estas predicciones con el CRM**, para generar alertas automáticas y priorizar la intervención comercial.  

---

## 📝 6. Recomendaciones Estratégicas  

1. Migrar clientes de contratos mensuales hacia planes de mayor duración con incentivos.  
2. Ofrecer paquetes de servicios adicionales que refuercen la percepción de valor.  
3. Reducir el riesgo en métodos de pago electrónicos, incentivando medios automáticos y seguros.  
4. Implementar programas de fidelización temprana en los primeros **6-12 meses**.  
5. Desplegar el modelo de Random Forest en producción, integrado al *pipeline* de datos y al sistema de gestión de clientes.  

---

## 🙌 7. Conclusión  

El modelado predictivo confirma que el *churn* en **Telecom X** puede anticiparse con un desempeño superior al **80% de precisión**.  

La aplicación de estas técnicas no solo ayuda a detectar clientes en riesgo, sino que permite diseñar **acciones concretas** que reduzcan la fuga y mejoren la rentabilidad.  

---

📌 **Presentado por:** Bibiana Trujillo Cedeño  
📌 **Programa:** ONE + Alura LATAM  
📌 **Especialización:** Ciencia de Datos  
