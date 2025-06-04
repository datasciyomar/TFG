# Análisis de factores de riesgo para infecciones nosocomiales en pacientes críticos

Este repositorio contiene el código y los materiales desarrollados como parte del Trabajo Final de Grado de Ahmad Yaman Omar Dallal, presentado en el Grado en Ciencia de Datos Aplicada (UOC).

## 🎯 Objetivo del proyecto

Desarrollar un modelo predictivo basado en técnicas de aprendizaje automático capaz de estimar el riesgo de infecciones nosocomiales en pacientes críticos hospitalizados, utilizando datos reales anonimizados de la base MIMIC-IV (versión demo v2.2).

## 🏥 Contexto

Las infecciones nosocomiales constituyen una de las principales complicaciones en unidades de cuidados intensivos (UCI). La aplicación de modelos predictivos basados en datos puede facilitar la identificación temprana de pacientes en riesgo y contribuir a mejorar la calidad asistencial y la sostenibilidad del sistema sanitario.

## 📊 Estructura del notebook

El notebook está organizado en las siguientes secciones:

1. **Carga y organización de los datos**  
   Automatización de lectura de tablas clínicas y estructuración inicial.

2. **Preprocesamiento de datos**  
   Limpieza, tratamiento de nulos, creación de la variable objetivo.

3. **Análisis exploratorio (EDA)**  
   Evaluación de variables, visualización de patrones clínicos.

4. **Ingeniería de características**  
   Generación de variables derivadas para el modelado.

5. **Modelado predictivo**  
   Entrenamiento de modelos (Logistic Regression, Random Forest, XGBoost), métricas de evaluación.

6. **Interpretabilidad del modelo**  
   Aplicación de SHAP para entender la influencia de cada variable en las predicciones.

## 🧪 Dataset

- **Fuente**: [MIMIC-IV Clinical Database Demo v2.2](https://physionet.org/content/mimiciv-demo/2.2/)
- **Licencia**: Requiere registro en PhysioNet y cumplimiento de requisitos éticos.

⚠️ *Este proyecto utiliza la versión demo, por lo que algunos resultados podrían variar frente al conjunto completo.*

## 🧰 Herramientas utilizadas

- Python 3.12
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn, XGBoost
- SHAP
- Jupyter Notebook

## 📈 Resultados clave

- AUC > 0.92 y F1-score > 0.84 en la predicción de infecciones.
- Variables más influyentes: duración de la estancia, frecuencia cardíaca, número de cultivos positivos.

## 📎 Enlace al notebook

Puedes consultar el notebook completo en GitHub:  
[🔗 Ver notebook](./TFG_OmarDallal_AhmadYaman.ipynb)

También puedes visualizarlo en [nbviewer](https://nbviewer.org/):  
[🔗 Visualizar en nbviewer](https://nbviewer.org/github/datasciyomar/TFG/blob/main/TFG_OmarDallal_AhmadYaman.ipynb)  

## 📄 Licencia

Este proyecto está bajo la licencia [Creative Commons BY-NC-ND 3.0 ES](http://creativecommons.org/licenses/by-nc-nd/3.0/es/).

---

*Trabajo Final de Grado presentado en la Universitat Oberta de Catalunya (UOC), curso 2024–2025/2.*  
Tutor: Xavier Florit Medina
