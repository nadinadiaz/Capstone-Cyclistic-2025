# 🚲 Análisis de Comportamiento de Usuarios – Caso Cyclistic
### Estrategia de Conversión de Usuarios Casuales a Miembros Anuales

![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Tidyverse](https://img.shields.io/badge/Tidyverse-white?style=for-the-badge&logo=tidyverse&logoColor=276DC3)
![Big Data](https://img.shields.io/badge/Data_Volume-6M+_Rows-informational)

> ## 🔎 Recursos del Proyecto
> * 📄 [Ver Presentación Ejecutiva (PDF)](https://nadinadiaz-github-io.vercel.app/docs/Comportamiento_de_usuarios_en_Cyclistic.pdf)
> * 📊 [Ver Reporte Interactivo con Gráficos (HTML)](https://htmlpreview.github.io/?https://github.com/nadinadiaz/Google-Data-Analytics-Capstone-Project/blob/main/Capstone1v2.html)
> * 💻 [Explorar Código Fuente (R Markdown)](https://github.com/nadinadiaz/Capstone-Cyclistic-2025/blob/main/Cyclist.Rmd)

---


## 📌 Descripción del Proyecto
Este proyecto es el **Capstone de la Certificación de Google Data Analytics**. El objetivo estratégico es identificar las diferencias de comportamiento entre **miembros anuales** y **usuarios casuales** de Cyclistic para diseñar una estrategia de marketing basada en datos que incremente la tasa de conversión.

## 🗄️ Gestión de Datos (Big Data Handling)
Debido a la magnitud del dataset, este proyecto implicó el procesamiento de un volumen masivo de información:
* **Volumen:** +6,000,000 de registros históricos.
* **Procesamiento:** Se utilizaron técnicas de optimización en **R** para la limpieza, unión y transformación de múltiples archivos mensuales.
* **Nota sobre el Dataset:** Debido a que el dataset original excede **1GB**, los archivos fuente no se incluyen en este repositorio. Pueden descargarse de la fuente oficial: [Index of bucket "cyclistic-tripdata"](https://divvy-tripdata.s3.amazonaws.com/index.html).

## 📊 Hallazgos Clave

**1️⃣ Dominio del mercado**
Los miembros anuales generan el **64.5% de los viajes**, con un patrón de uso claramente utilitario (commuting).

**2️⃣ Engagement del segmento casual**
Los usuarios casuales realizan viajes **58% más largos**, concentrados en fines de semana y temporadas cálidas.

**3️⃣ Diferencias en patrones de uso**
Los miembros presentan picos a las **8 AM y 5 PM**, mientras que los usuarios casuales muestran mayor actividad durante tardes y fines de semana.


## 🛠️ Stack Tecnológico
* **Lenguaje:** R (v4.x)
* **Librerías Clave:** `tidyverse` (data wrangling), `lubridate` (manejo de series temporales), `ggplot2` (visualización avanzada).
* **Entorno:** RStudio / R Markdown.

## 📂 Estructura del Repositorio
* `Analisis_Cyclistic.Rmd`: Script fuente con el pipeline completo (ETL + Análisis).
* `Informe_Final.html`: Reporte técnico interactivo (Renderizado vía RMarkdown).
* `Presentacion_Estrategica.pdf`: Resumen ejecutivo para Stakeholders.
  
## 🚀 Recomendaciones Estratégicas

**1️⃣ Membresía "Weekend Warrior"**
Diseñar una membresía específica para usuarios recreativos que utilizan el servicio principalmente los fines de semana.

**2️⃣ Campañas de retargeting estacional**
Dirigir campañas a usuarios casuales activos en verano, incentivando la conversión a membresías anuales.

**3️⃣ Calculadora de valor en la app**
Implementar una herramienta que muestre a los usuarios casuales cuánto ahorrarían si se convirtieran en miembros según su historial de viajes.


---
*Analizado por Nadina Díaz – Bioingeniera & Data Analyst*
