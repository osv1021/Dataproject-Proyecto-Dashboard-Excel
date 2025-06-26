
# 📊 Dashboard de Ventas - Proyecto Excel

Este proyecto consiste en el desarrollo de un **dashboard interactivo en Excel** a partir de un conjunto de datos de ventas internacionales. Se ha llevado a cabo un proceso completo de análisis exploratorio, limpieza y visualización de datos, con el objetivo de extraer insights clave sobre el negocio y presentar la información de forma clara y útil.

---

## 📁 Conjunto de datos utilizado

- Fuente: CSV de muestra de datos de ventas
- Total de registros: 2.824 pedidos
- Periodo cubierto: Años 2003, 2004 y 2005
- Información contenida:
  - Fecha de pedido
  - Cliente y país
  - Producto y línea de producto
  - Estado del pedido
  - Cantidad vendida, precio, ingreso

---

## 🎯 Objetivos

- Realizar un análisis exploratorio de datos (EDA)
- Limpiar y transformar datos para el análisis
- Identificar KPIs de negocio relevantes
- Construir un **dashboard interactivo en Excel**

---

## ✅ KPIs mostrados

- **Ingresos totales** (en €)
- **Volumen de ventas** (unidades vendidas)
- **Número de pedidos realizados**

Se muestran en tarjetas grandes para destacar su relevancia y facilitar la lectura.

---

## 📊 Visualizaciones del Dashboard

- 📈 **Ingresos por mes** 
- 🌍 **Ingresos por país** 
- 📦 **Ingresos por línea de producto**
- 🔄 **Distribución por estado del pedido**
- 🏆 **Top 5 clientes por pedidos**
- 💰 **Top 5 clientes por facturación**

---

## 🎛️ Segmentadores de datos

Colocados de forma vertical a la izquierda del dashboard:

- **Año**
- **Trimestre**
- **País**
- **Línea de producto**
- **Estado del pedido**

> Todos los segmentadores están conectados correctamente a KPIs y gráficos, excepto los *Top 5 clientes*, que se mantienen fijos para preservar su comparativa global.

---

## 🧹 Transformaciones realizadas

- Filtrado y eliminación de columnas no necesarias (`PHONE`, `POSTALCODE`, etc.). En la hoja 2 del Excel está explicado el motivo de la eliminación
- Cálculo de métricas como ingresos (SALE), unidades vendidas y total pedidos
- Validación de unicidad de los pedidos (`ORDERNUMBER` como clave)

---

## 🔍 Principales hallazgos

Durante el análisis se identificaron los siguientes insights clave:

- **Estacionalidad**: Los ingresos se concentran especialmente en el último trimestre de cada año.
- **Mercados fuertes**: Estados Unidos, España y Francia son los países con mayor facturación.
- **Clientes clave**: Un número reducido de clientes genera un alto porcentaje de las ventas totales.
- **Líneas de producto líderes**: `Classic Cars` y `Vintage Cars` dominan tanto en volumen como en ingresos.
- **Pedidos en espera**: Aunque la mayoría están completados, existe un volumen destacable de pedidos en estado "On Hold".

---

## 💡 Conclusiones

Este dashboard permite visualizar de forma clara el rendimiento comercial de la empresa en diferentes dimensiones (tiempo, geografía, productos y estado).  
Está diseñado para ser fácil de usar por perfiles no técnicos, y puede adaptarse a nuevas fuentes de datos o escalas de negocio.

---

## 📎 Estructura del archivo Excel

- **Hoja 1:** Datos limpios y transformados
- **Hoja 2:** Limpieza y transformación 
- **Hoja 3:** Tablas dinámicas para análisis
- **Hoja 4:** Gráficos dinámicos utilizados en el Dashboard
- **Hoja 5:** Dashboard

---

## 👤 Autor

**Nombre:** Óscar Sánchez Velayos
