# 📊 Análisis Financiero de Adventure Works Cycles con Power BI

## 📌 Descripción del Proyecto
Este proyecto consiste en el desarrollo de un **dashboard financiero interactivo en Power BI** para **Adventure Works Cycles (AWC)**, una empresa ficticia del sector de fabricación y comercialización de bicicletas.

El objetivo principal es **analizar el desempeño financiero y comercial**, visualizando ingresos, costos, utilidades, márgenes y otros **KPIs clave**, con especial enfoque en el mercado de **Estados Unidos**, con el fin de apoyar la toma de decisiones estratégicas basadas en datos.

El proyecto se desarrolla como un **caso de estudio**, simulando un entorno laboral real de análisis financiero y de negocios.

---

## 🎯 Objetivos
- Mejorar la **calidad de los datos** mediante procesos de limpieza y transformación en Power Query  
- Diseñar un **modelo de datos relacional** alineado con las necesidades del negocio  
- Crear **medidas DAX** para el cálculo de métricas financieras clave  
- Desarrollar un **dashboard interactivo, claro y orientado al negocio**  
- Facilitar el análisis comparativo entre períodos actuales y anteriores  

---

## 🛠️ Tecnologías Utilizadas
- Power BI Desktop  
- Power Query  
- DAX  
- Modelado de datos (esquema estrella)  
- Visualización de datos  

---

## 🧹 Preparación y Limpieza de Datos
- Conexión a la base de datos **AdventureWorksDW2019**
- Limpieza y transformación de datos:
  - Eliminación de columnas innecesarias  
  - Estandarización de tipos de datos  
  - Renombrado de campos  
  - Creación de columnas calculadas  
- Integración y validación de tablas relacionadas  

---

## 🧱 Modelo de Datos
Se diseñó un **modelo en estrella**, compuesto por:
- **Tabla de hechos**: FactInternetSales  
- **Tablas de dimensiones**:  
  - DimDate  
  - DimProduct  
  - DimCustomer  
  - DimPromotion  
  - DimSalesTerritory  
  - DimGeography  

---

## 📐 Métricas Clave (DAX)
- Ingresos Totales  
- Ingresos Año Anterior (LY)  
- Costos (COGS)  
- Utilidad Bruta y Neta  
- Margen de Utilidad  
- Variación Interanual  
- Ingresos Acumulados (YTD)  
- Cantidad Vendida  
- Clientes Totales  

---

## 📊 Diseño del Dashboard
- Portada con navegación
- Vista financiera general con KPIs y comparativos
- Análisis geográfico del mercado de EE. UU.
- Segmentadores interactivos

---

## 💡 Principales Insights
- Crecimiento estable de los ingresos
- Márgenes financieros controlados
- Bicicletas como principal motor de rentabilidad
- EE. UU. concentra alto volumen con márgenes más ajustados

---

## 📄 Entregables
- Archivo Power BI (.pbix)  
- Dashboard financiero interactivo  

---

## 🚀 Conclusión
Este proyecto demuestra la capacidad de **transformar datos financieros en información estratégica**, aplicando buenas prácticas de limpieza, modelado y visualización de datos en Power BI.
