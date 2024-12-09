# Análisis de Enfermedades Cardíacas 🫀

Este proyecto analiza datos relacionados con enfermedades cardíacas para identificar patrones y construir modelos de predicción que puedan ser utilizados para predecir la presencia de esta condición. El análisis incluye visualizaciones, estadísticas descriptivas y modelos de Machine Learning.

---

## 📂 Estructura del Proyecto

1. **`Heart.ipynb`**:  
   Contiene todo el análisis y modelado, incluyendo:
   - Limpieza de datos.
   - Visualización de patrones significativos.
   - Construcción y evaluación de modelos de predicción (Regresión Logística, XGBoost, etc.).
   - Interpretación de resultados.

2. **`requirements.txt`**:  
   Archivo que lista todas las dependencias necesarias para reproducir el análisis. 

3. **`README.md`**:  
   Este archivo, que proporciona una descripción general del proyecto.

---

## 🛠️ Requisitos del Sistema

Es **altamente recomendable** crear un entorno virtual para instalar las dependencias de este proyecto. Esto ayuda a evitar conflictos con las librerías instaladas globalmente en tu sistema.

### Pasos para Crear un Entorno Virtual

1. **Crear el entorno virtual:**  
```bash
   python -m venv env
```

2. **Activar el entorno virtual:**  
   - En Windows:  
```bash
     .\env\Scripts\activate
```
   - En macOS/Linux:  
```bash
     source env/bin/activate
```

3. **Instalar las dependencias:**  
   Una vez activado el entorno virtual, instala las dependencias necesarias ejecutando:  
```bash
   pip install -r requirements.txt
```

4. **Desactivar el entorno virtual (opcional):**  
   Cuando termines de trabajar en el proyecto, puedes desactivar el entorno virtual ejecutando:  
```bash
   deactivate
```

---

## 📊 Descripción del Dataset

El dataset utilizado contiene información sobre factores de riesgo relacionados con enfermedades cardíacas, como:
- Edad, género.
- Colesterol, presión arterial.
- Presencia de dolor en el pecho, anomalías en el ECG.
- Indicadores de actividad física, entre otros.

Fuente de los datos: Repositorio de **UCI Machine Learning**

---

## 🚀 Resultados Clave

1. **Factores importantes:**  
   - Angina inducida por el ejercicio (`exang_True`).
   - Tipo de dolor de pecho (`cp_atypical angina`, `cp_typical angina`).
   - Número de vasos afectados (`ca_2.0`).

2. **Mejor Modelo Predictivo:**  
   - **XGBoost** para selección de características y **Regresión Logística** para el modelado.
   - F1-Score en prueba: **0.855**.

3. **Visualizaciones Interactivas:**  
   - Identificación de patrones a través de gráficos de dispersión, histogramas y heatmaps de correlación.

---

## 📈 Modelos Construidos

1. **Regresión Logística:**  
   Modelo interpretativo basado en probabilidades, con alta capacidad de generalización.

2. **XGBoost:**  
   Algoritmo de boosting, utilizado para selección de características y análisis.

3. **Random Forest y Gradient Boosting:**  
   Probados para evaluar su desempeño frente a los modelos principales.

---

## 🔍 Cómo Reproducir el Proyecto

1. **Clona este repositorio:**  
```bash
   git clone https://github.com/jarkillo/Missing_Keys.git
```
2. **Accede al directorio del proyecto:**  
```bash
   cd tu-repositorio
```
3. **Crea y activa un entorno virtual (opcional pero recomendado):**  
   Consulta la sección [Requisitos del Sistema](#🛠️-Requisitos-del-Sistema).

4. **Instala las dependencias:**  
```bash 
   pip install -r requirements.txt
```
5. **Abre el notebook:**  
```bash
   jupyter notebook Heart.ipynb
```
---

## 📂 Próximos Pasos

1. Incorporar datos adicionales para enriquecer el análisis.
2. Probar modelos más avanzados como redes neuronales.
3. Implementar la validación en datasets externos.

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Si usas este proyecto, por favor, menciona esta fuente.

---

## 🛠️ Herramientas Utilizadas

- **Lenguaje:** Python 3.8+
- **Librerías:** pandas, numpy, scikit-learn, matplotlib, seaborn, XGBoost.
- **Entorno:** Jupyter Notebook

---

## 📬 Contacto

Si tienes preguntas o sugerencias, no dudes en contactarme:  
📧 **jarkoarenal@gmail.com**