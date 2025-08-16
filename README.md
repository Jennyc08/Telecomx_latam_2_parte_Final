# 📊 Análisis de Cancelación de Clientes - Telecom X

Este proyecto aborda el problema de la **cancelación de clientes (Churn)** en la empresa Telecom X, aplicando técnicas de análisis exploratorio de datos, preprocesamiento y modelos de machine learning para identificar los factores más relevantes que influyen en la retención de clientes.

---

## 🚀 Objetivos del Proyecto

- Analizar el comportamiento de los clientes y sus patrones de cancelación.  
- Identificar las variables que más influyen en la evasión de clientes.  
- Construir y evaluar modelos predictivos para predecir el **Churn**.  
- Proponer **estrategias de retención** basadas en los resultados.  

---

## 📂 Flujo de Trabajo

1. **Carga y limpieza de datos**  
   - Eliminación de columnas irrelevantes (IDs, duplicados).  
   - Tratamiento de valores nulos e inconsistencias.  
   - Estandarización de nombres de columnas.

2. **Transformación de variables**  
   - Conversión de variables categóricas a numéricas con *OneHotEncoding*.  
   - Normalización de datos para modelos sensibles a la escala.  

3. **Análisis exploratorio (EDA)**  
   - Distribución de clientes activos vs cancelados.  
   - Matriz de correlación para detectar relaciones clave.  
   - Gráficos comparativos:  
     - Tiempo de contrato × Cancelación  
     - Cargos totales × Cancelación  

4. **Balanceo de clases**  
   - Detección de desbalance entre clases.  
   - Aplicación de técnicas como **SMOTE** para oversampling.  

5. **Modelado predictivo**  
   - Modelos aplicados:  
     - **Regresión Logística** (requiere normalización).  
     - **Random Forest** (no sensible a la escala).  
   - Evaluación con métricas:  
     - Accuracy, Precision, Recall, F1-score, Matriz de Confusión.  

6. **Interpretación de resultados**  
   - Importancia de variables en Random Forest.  
   - Coeficientes en Regresión Logística.  
   - Comparación crítica entre modelos.

---

## 📈 Resultados Clave

- Los **cargos mensuales altos** y los **contratos de corto plazo** se relacionan fuertemente con la cancelación.  
- La **antigüedad del cliente** muestra una correlación inversa: a mayor tiempo con la empresa, menor probabilidad de cancelar.  
- El **Random Forest** obtuvo mejor desempeño global, mostrando mayor robustez frente a datos desbalanceados.  
- La **Regresión Logística** permitió una interpretación más clara de las variables, destacando las más influyentes.

---

## 🎯 Recomendaciones Estratégicas

1. **Ofrecer descuentos o planes personalizados** a clientes con cargos mensuales altos.  
2. **Incentivar contratos de mayor duración** para reducir la tasa de cancelación.  
3. **Programas de fidelización** para clientes con baja antigüedad, reforzando la permanencia.  
4. Aplicar un sistema de **alertas tempranas** basado en las variables más predictivas para actuar antes de que el cliente cancele.  

---

## 🛠️ Tecnologías Utilizadas

- **Python** (pandas, numpy, matplotlib, seaborn, scikit-learn, imbalanced-learn)  
- **Jupyter Notebook / Google Colab** para la implementación  
- **GitHub** para control de versiones y documentación  

---

## 📌 Conclusión

Este proyecto demuestra cómo el análisis de datos y el machine learning pueden aportar **insights valiosos para la toma de decisiones estratégicas**, mejorando la retención de clientes y reduciendo la tasa de cancelación en Telecom X.

