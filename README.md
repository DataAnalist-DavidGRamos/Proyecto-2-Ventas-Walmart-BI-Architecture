# 🛒 Walmart BI Architecture - Relational Analysis
![BI](https://img.shields.io/badge/Analysis-Business%20Intelligence-blue)
![Excel](https://img.shields.io/badge/Design-MVC%20Architecture-blue)
## 📌 Resumen
Este proyecto consiste en un análisis detallado de las ventas de Walmart (2010-2012) para identificar la eficiencia operativa de las tiendas, la participación de los departamentos y los riesgos por volatilidad. El objetivo es transformar datos crudos en insights accionables para la toma de decisiones estratégicas.En otras palabras se basa en el análisis de eficiencia operativa para Walmart usando lógica multicapa relacional.

## 🛠️ Herramientas Utilizadas
* **Google Sheets / Excel:** Procesamiento, limpieza y creación de Dashboards.
* **Técnicas de Limpieza:** Manejo de duplicados, corrección de formatos de fecha y estandarización de categorías.
* **Métricas Analíticas:** Cálculo de KPI de eficiencia, participación y coeficiente de variación.

## 🧠 Arquitectura MVC
1. **Raw**: Tablas ventas, departamento, tiendas.
2. **Transformación**: Unión relacional (Primary/Foreign Keys).
3. **Analítica**: KPIs financieros.
4. **Presentación**: Dashboard interactivo.

## 🔬 Hallazgos
  Detectados 6,435 registros sin departamento asignado.
  Identificados 27 registros con ventas nulas o negativas.
  "Data Cleaning" 
  
* 🌟 **ROI Superficie**: "Las tiendas de Tipo B son altamente eficientes, pero las Tipo A dominan en volumen total. Las tiendas Tipo C son el punto débil, aportando solo el 10% Tiendas Tipo A son 25% más eficientes que Tipo C.
* 🚨 **Fricción Inventario**: Ahorro potencial del 15% en Electrónica (picos vs valles).
* 🏘️ **Mix Ganador**: "Hogar" domina en regiones de baja densidad.


## 📊 Datos
Los datos están en Google Sheets: [https://docs.google.com/spreadsheets/d/1ruhaUG9n1VCUbC-RXhsXp_SO2GCLdbHTn9Lt2RxMkos/edit?usp=drive_link)]

## 📝 Descripción
Mi proyecto consiste en asumir el rol de analista en Walmart, donde la Dirección Comercial necesita un resumen ejecutivo para ajustar presupuestos e inventario. Trabajo con datos de ventas semanales de 2012, que incluyen información de tiendas, departamentos y ventas.
