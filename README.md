# 📊 Análisis de Evasión de Clientes (Churn) – Telecom X

## 📌 Introducción

La evasión de clientes (*churn*) es uno de los principales retos para las empresas de telecomunicaciones, ya que la pérdida de clientes puede afectar significativamente los ingresos y la estabilidad del negocio.

El objetivo de este proyecto es analizar los datos de clientes de **Telecom X** para identificar patrones asociados con la cancelación del servicio. A través de técnicas de **limpieza de datos, análisis exploratorio y visualización**, se busca comprender qué factores influyen en la evasión de clientes.

---

# 🎯 Objetivo del proyecto

Realizar un **Análisis Exploratorio de Datos (EDA)** para identificar patrones y variables que puedan estar relacionadas con la evasión de clientes, proporcionando información útil para futuras estrategias de retención de clientes.

---

# 📂 Dataset

El conjunto de datos contiene información sobre los clientes de Telecom X, incluyendo:

- 👤 Datos demográficos de los clientes (género)
- 📄 Tipo de contrato
- 🌐 Servicios contratados
- 💳 Método de pago
- 💰 Cargos mensuales y gasto total
- 📉 Estado de evasión del cliente (*churn*)

---

# 🧹 Limpieza y preparación de datos

Antes de realizar el análisis se llevaron a cabo varios pasos de limpieza y preparación:

- Carga de datos desde un archivo JSON
- Conversión a DataFrame de Pandas
- Estandarización de nombres de columnas
- Identificación y tratamiento de valores faltantes
- Corrección de tipos de datos en variables numéricas
- Eliminación de registros incompletos
- Creación de una nueva variable: cuentas_diarias


---

# 🔎 Análisis Exploratorio de Datos

Durante el análisis se exploraron diferentes aspectos relacionados con la evasión de clientes.

### 📊 Distribución de churn

Se analizó la proporción de clientes que permanecen en la empresa frente a aquellos que cancelan el servicio.

### 📑 Variables categóricas analizadas

Se exploró la relación entre churn y variables como:

- tipo de contrato
- método de pago
- género
- servicio de internet

### 📈 Variables numéricas analizadas

También se analizaron variables numéricas como:

- tiempo de permanencia del cliente
- cargos mensuales
- gasto total
- cargos diarios

Además, se exploraron **correlaciones entre variables numéricas** para identificar relaciones con la evasión.

---

# 💡 Principales hallazgos

El análisis permitió identificar algunos factores asociados con la evasión de clientes:

- 📅 Clientes con **menor tiempo de permanencia** presentan mayor probabilidad de cancelar.
- 📄 Los contratos **month-to-month** tienen mayor tasa de evasión.
- 💳 El método de pago **electronic check** muestra mayor evasión.
- 💰 Clientes con **cargos mensuales más altos** presentan mayor tendencia a irse.
- 🌐 Los servicios de **fibra óptica** presentan niveles de evasión más altos.

---

# 🚀 Recomendaciones

A partir del análisis se sugieren algunas estrategias para reducir la evasión:

1️⃣ Fortalecer estrategias de retención para **nuevos clientes**, tales como promociones en los primeros meses.

2️⃣ Incentivar **contratos a largo plazo** mediante beneficios o descuentos.

3️⃣ Promover **métodos de pago automáticos**.

4️⃣ Revisar la **percepción de valor de los planes con mayor costo**.

5️⃣ Evaluar la experiencia del cliente en servicios de **fibra óptica**.

---

# 🛠️ Herramientas utilizadas

- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab
- GitHub


---

# 👩‍💻 Autor
Andrea T. Valdés🦇


Proyecto desarrollado como parte de un desafío de un curso de data science de AluraLATAM y Oracle Next Education
