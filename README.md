# 🔍 Predicción de Rangos Salariales: Ciencia de Datos aplicada al Mercado Laboral 💼

---

## 📌 Contexto del Proyecto

Este proyecto surge a partir del requerimiento de una empresa tecnológica para desarrollar un sistema predictivo capaz de estimar **rangos salariales** (inferior, promedio y superior) utilizando datos reales de procesos de selección.

El objetivo principal es apoyar a profesionales y organizaciones en la toma de decisiones basadas en análisis de datos, facilitando negociaciones salariales y estrategias de contratación más efectivas.

---

## 🗂️ Dataset

- Más de **50,000 registros históricos** de ofertas laborales representativas del mercado actual.  
- Variables relevantes: **cargo, empresa, experiencia, industria, habilidades, ubicación y salario**.  
- Alta calidad y diversidad para asegurar la robustez del modelo.

---

## ⚙️ Tecnologías y Herramientas Utilizadas

- **Python**: lenguaje principal para análisis y modelado  
- **NumPy & Pandas**: manipulación y preprocesamiento de datos  
- **Scikit-learn**: entrenamiento y evaluación de modelos predictivos  
- **Ipywidgets**: interacción dinámica durante el análisis  
- **Plotly & Altair**: visualizaciones interactivas para interpretación  
- **Exportación a PDF**: generación de reportes técnicos y análisis de impacto económico

---

## 🧠 Modelos Evaluados

Se exploraron y compararon distintos algoritmos de Machine Learning:

- 🔹 Regresión Logística  
- 🔸 Árbol de Decisión  
- 🌲 **Random Forest** → *Modelo final seleccionado por su mayor precisión*

---

## 📊 Resultados y Evaluación

- Métricas evaluadas: **precisión (accuracy), matriz de confusión, classification report**  
- **Random Forest** alcanzó una precisión del **95.43%**  
- Impacto económico positivo estimado: **💰 USD $528,010**  
- Excelente balance entre aciertos y reducción de errores

---

## ✅ Conclusiones

El sistema demuestra un alto nivel de precisión y confiabilidad para predecir rangos salariales, contribuyendo a una mayor **transparencia, eficiencia y equidad** en el mercado laboral.

Se recomienda su implementación para áreas de Recursos Humanos, selección de personal y consultoría estratégica.

---

## 📂 Estructura del Proyecto

```
salary-prediction-model/
├── README.md
├── salary_prediction_model.ipynb
├── salary_prediction_model_clean.ipynb
└── reporte_modelo_impacto_Economico.pdf
```

## 📂 Archivos del Proyecto

### 📊 `salary_prediction_model.ipynb`
Notebook principal realizado en **Google Colab**, con widgets interactivos.  
Ideal para exploración dinámica y educativa del modelo.  
🔗 [Abrir en Google Colab](https://colab.research.google.com/drive/1hMMbVlPv8VqgCGqm8JjV4my9uLKNTrRo?usp=sharing)

---

### ✅ `salary_prediction_model_clean.ipynb`
Versión limpia optimizada para **visualización en GitHub**.  
Se eliminaron los `metadata.widgets` para evitar errores de renderizado.  
Ideal para revisión estática y lectura directa del código.

---

### 📄 `reporte_modelo_impacto_Economico.pdf`
Reporte técnico profesional que presenta:  
- Resultados del modelo  
- Métricas de evaluación  
- Visualizaciones  
- Impacto económico estimado

---

## 🔗 Enlaces de Interés

- 📂 Repositorio GitHub: [`salary-prediction-model`](https://github.com/usuario/salary-prediction-model)  
- 🧪 Notebook Interactivo: [Abrir en Google Colab](https://colab.research.google.com/drive/1hMMbVlPv8VqgCGqm8JjV4my9uLKNTrRo?usp=sharing)
