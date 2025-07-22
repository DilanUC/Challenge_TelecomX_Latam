# 📊 TELECOMX LATAM - Análisis de Evasión de Clientes (Churn)

Este proyecto analiza datos de clientes de Telecom X para comprender los factores que influyen en la **evasión de clientes (Churn)**, identificar patrones y proponer recomendaciones estratégicas para reducirla.

---

## 🚀 Objetivo
Analizar los datos de clientes para:
- Conocer las características de los usuarios que cancelan el servicio.
- Identificar patrones asociados a la evasión.
- Proponer acciones para mejorar la retención.

---

## 📦 Extracción de Datos
- Los datos fueron obtenidos desde la **API de Telecom X** en formato JSON.
- Se cargaron y transformaron a un **DataFrame de pandas** para facilitar su manipulación.

---

## 🧹 Limpieza y Tratamiento de Datos
- Exploración de la estructura y tipos de datos.
- Corrección de valores nulos y categorías vacías (por ejemplo, en la columna `Churn`).
- Conversión de variables numéricas y normalización de formatos.
- Creación de una columna adicional `Cuentas_Diarias` (cálculo del costo diario).
- Estandarización: conversión de variables como `Churn` a formato binario y renombrado de columnas para mayor claridad.

---

## 📊 Análisis Descriptivo
Se calcularon métricas estadísticas de variables numéricas:
- **Media, mediana, desviación estándar, valores mínimos y máximos.**
- Variables analizadas: `CargoMensual`, `CargoTotal`, `MesesAntiguedad`.

---

## 📈 Análisis Exploratorio
Se realizaron varias visualizaciones y análisis para profundizar:

- **Distribución de evasión:** proporción de clientes que cancelaron frente a los que permanecen.
- **Evasión según variables categóricas:** género, tipo de contrato, método de pago, tipo de internet, telefonía.
- **Evasión según variables numéricas:** antigüedad, cargos mensuales y totales, comparando clientes que cancelaron vs. los que permanecen.

---

## 🔍 Principales Insights
- Mayor evasión entre clientes con **contratos mes a mes** y pagos electrónicos.
- Clientes con **menor antigüedad** tienden a cancelar más.
- Cargos mensuales más altos parecen estar asociados a mayor evasión.

---

## 💡 Recomendaciones Estratégicas
- Incentivar contratos a largo plazo mediante descuentos o beneficios.
- Diseñar campañas de retención enfocadas en clientes nuevos o con cargos altos.
- Revisar políticas para clientes que pagan por métodos electrónicos y buscar fidelizarlos.

---

## 📝 Informe Final
Incluido dentro del notebook:
- Introducción.
- Detalle de limpieza y tratamiento.
- Análisis descriptivo y exploratorio.
- Conclusiones e insights clave.
- Recomendaciones accionables.

---

## 🛠️ Herramientas Utilizadas
- **Python 3**
- **Pandas** para manejo de datos.
- **Matplotlib** y **Seaborn** para visualización.
- **Jupyter Notebook** como entorno de análisis.

---

## ✅ Resultado
Un dataset limpio, estructurado y visualizado, que permite entender mejor la evasión y diseñar estrategias para mejorar la retención de clientes.

---

**Autor:** *Dilan Utria*  
📅 **Proyecto:** TELECOMX_LATAM  
