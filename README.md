
# 📊 Análisis de Cancelaciones de Clientes - TelecomX

Este repositorio contiene un análisis exploratorio de datos (EDA) sobre los registros de clientes de **TelecomX**, una empresa de telecomunicaciones que enfrenta una **alta tasa de cancelaciones**. El objetivo principal es identificar patrones y variables asociadas con la pérdida de clientes para apoyar futuras estrategias de retención y el desarrollo de modelos predictivos.

---

## 🧠 Objetivos del Proyecto

- Comprender los factores que inciden en la cancelación del servicio por parte de los clientes.
- Realizar un análisis exploratorio profundo usando Python.
- Crear visualizaciones estratégicas para descubrir tendencias y correlaciones.
- Generar un informe técnico con recomendaciones operativas y de modelado.

---

## 🔧 Tecnologías y Librerías Utilizadas

- **Python 3.x**
- [pandas](https://pandas.pydata.org/)
- [numpy](https://numpy.org/)
- [seaborn](https://seaborn.pydata.org/)
- [matplotlib](https://matplotlib.org/)
- [plotly](https://plotly.com/python/)
- [fpdf](https://py-pdf.github.io/fpdf2/)
- [python-docx](https://python-docx.readthedocs.io/en/latest/)

---

## ⚙️ Proceso ETL

### 1. **Extracción**
Los datos fueron extraídos desde una fuente pública en formato JSON:

```
https://raw.githubusercontent.com/alura-cursos/challenge2-data-science-LATAM/refs/heads/main/TelecomX_Data.json
```

### 2. **Transformación**
- Limpieza de datos: tratamiento de valores nulos, duplicados y errores tipográficos.
- Conversión de tipos de datos (e.g., TotalCharges a `float`).
- Creación de nuevas variables si es necesario.

### 3. **Carga**
- Carga de los datos en `pandas.DataFrame` para análisis.
- Exportación de informes en formato `.docx` y `.pdf`.

---

## 📈 Análisis Exploratorio de Datos (EDA)

Se realizó un EDA detallado, que incluye:

- Distribución de cancelaciones.
- Cancelaciones por tipo de contrato.
- Relación entre cargos mensuales, permanencia y cancelación.
- Visualizaciones interactivas con `Plotly`.

---

## 📝 Informe Técnico

Se ha generado un **informe técnico completo** en los formatos `.docx` y `.pdf`, disponible en la carpeta `/output/` del proyecto. Este informe incluye:

- Descripción del problema.
- Metodología aplicada.
- Principales hallazgos.
- Recomendaciones para modelado predictivo.
- Estrategias sugeridas para el negocio.

---

## 🔮 Próximos pasos

- Codificación de variables categóricas (`pd.get_dummies`).
- Entrenamiento de modelos supervisados: **Logistic Regression**, **Random Forest**, **XGBoost**.
- Evaluación de desempeño y análisis de importancia de variables (e.g., SHAP).
- Construcción de dashboard interactivo con **Dash** o **Streamlit**.

---

## 📁 Estructura del Proyecto

```
📦 TelecomX-Churn-Analysis
├── 📁 data/               # Datos sin procesar
├── 📁 notebooks/          # Análisis exploratorio y visualizaciones
├── 📁 output/             # Informes generados (.docx, .pdf)
├── 📁 src/                # Código fuente de procesamiento y visualización
├── README.md              # Documento explicativo
```

---

## 👨‍🔬 Autor

**Dr. Martin Abreu**  
Científico de Datos en formación | Docente e Investigador en Ciencias de la Educación  
📫 martinabreu[at]example.com  
🔗 [LinkedIn](https://linkedin.com) | [ORCID](https://orcid.org) | [Google Scholar](https://scholar.google.com)

---

## 📜 Licencia

Este proyecto está bajo la Licencia MIT. Consulte el archivo `LICENSE` para más información.
