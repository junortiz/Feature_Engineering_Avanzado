# 📘 Análisis Estadístico Avanzado

![Banner](Banner.png)


Este repositorio contiene ejercicios y notebooks para aprender fundamentos de estadística descriptiva, exploración de datos y análisis bivariado. Está dividido en dos secciones completas:

---

## 1. FUNDAMENTOS Y EXPLORACIÓN INICIAL

> **Objetivo:** Comprender y calcular medidas básicas de tendencia central, dispersión y distribución de datos.

### Contenido de esta sección

1. 📊 **Repaso de conceptos básicos:**

   * Media, mediana, varianza y desviación estándar
2. 🛠️ **Ejercicio práctico:**

   * Análisis estadístico completo de un dataset financiero con Python

### Notebook asociado

* **`1_FundamentoExploracionKurtosis.ipynb`**

  * Importación de librerías necesarias (`pandas`, `numpy`, `seaborn`, `matplotlib`, `scipy.stats`)
  * Carga y limpieza de datos (llenado de valores nulos)
  * Cálculo de estadística descriptiva con `df.describe()` y funciones manuales
  * Función reutilizable `analizar_columna()` para obtener media, mediana, moda, desvío, varianza, percentiles, asimetría y curtosis
  * Visualizaciones: histogramas, KDE, boxplots, Q-Q plots

**Duración estimada:** 3 horas

---

## 2. ANÁLISIS BIVARIADO COMPLETO

> **Objetivo:** Explorar relaciones entre dos variables mediante técnicas numéricas y gráficas.

### Contenido de esta sección

1. 🔢 **Correlación de Pearson:**

   * Matriz de correlación para variables numéricas
   * Heatmap con anotaciones y un decimal
2. 🔄 **Correlación de Spearman:**

   * Alternativa para relaciones no lineales
3. 📊 **Pruebas de Chi-cuadrado:**

   * Tabla de contingencia (`pd.crosstab`)
   * Cálculo de chi-cuadrado con `scipy.stats.chi2_contingency`
   * Interpretación de valores observados vs. esperados y p-value
4. 📈 **Gráficos de dispersión con líneas de regresión:**

   * Scatter plots con `matplotlib`
   * Ajuste de recta (regresión lineal) con `np.polyfit`
5. 🧮 **ANOVA de dos vías:**

   * Comparar grupos (`Fare` vs. `Sex` y `Survived`)
   * Uso de `pingouin.anova()` para efectos principales e interacción
   * Interpretación de F, p-value y eta-cuadrado parcial

### Notebooks y archivos

* **`2_AnalisisBivariado.ipynb`** *(crear)*

  * Código para **Pearson** y **Spearman**, gráficos de heatmap
  * Ejemplos de `countplot`, `crosstab` + heatmap
  * Cálculos de chi-cuadrado y tablas de frecuencia en porcentajes
  * Scatter + línea de regresión y explicación de pendiente
  * ANOVA de dos vías con `pingouin` y gráficos de interacción (opcional)

---

## 🚀 Cómo comenzar

1. Clonar el repositorio:

   ```bash
   git clone https://github.com/junortiz/Feature_Engineering_Avanzado.git
   cd Feature_Engineering_Avanzado
   ```
2. Crear y activar un entorno virtual (recomendado):

   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate     # Windows
   ```
3. Instalar dependencias:

   ```bash
   pip install -r requirements.txt
   ```
4. Abrir los notebooks en Jupyter:

   ```bash
   jupyter notebook
   ```

---

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.

---

*El niño curioso ha preparado estos notebooks con explicaciones sencillas y ejemplos prácticos para aprender estadística y análisis de datos paso a paso.*
