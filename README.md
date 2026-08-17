# ☕ Dashboard de Ventas – Cafetería

> Proyecto final del curso **Herramientas Básicas para el Análisis de Datos** – UTN

Alumna: **Noelia Leder**


Análisis y visualización de las ventas de una cadena de cafeterías en distintas sucursales de Buenos Aires, a partir de un dataset transaccional con más de 900 registros. El proyecto abarca la limpieza de datos y la construcción de un dashboard interactivo en **Power BI** para explorar ingresos, ganancias, calificaciones de clientes y comportamiento de consumo.

---

## 🎯 Objetivo del proyecto

- Analizar la evolución mensual de ingresos y ganancias.
- Identificar qué sucursales, categorías y productos son más rentables.
- Estudiar la relación entre calificación del cliente, propina y consumo total.
- Comparar precio unitario vs. costo unitario a lo largo del año.
- Construir un dashboard interactivo y filtrable para la toma de decisiones.

---

## 📊 Dataset utilizado

| | |
|---|---|
| **Archivo** | `dataset_cafeteria_moderna.csv` |
| **Registros** | 1034 transacciones |
| **Variables** | 15 columnas |

**Principales columnas:**

`id_transaccion`, `fecha`, `hora`, `sucursal`, `dni_cliente`, `edad_cliente`, `categoria_producto`, `producto`, `cantidad`, `precio_unitario`, `costo_unitario`, `propina`, `metodo_pago`, `canal`, `calificacion`, `total_consumido`, `mes_num`, `mes`, `margen_ganancia`

Los datos fueron procesados y limpiados previamente (tipado de fechas, normalización de texto, cálculo de márgenes) antes de cargarse al modelo de Power BI.

---

## 🛠️ Herramientas utilizadas

- **Python** (pandas) → limpieza y preparación del dataset
- **Power BI** → construcción del dashboard
- **GitHub** → documentación y carga del proyecto

---

## 📈 Dashboard

El dashboard permite filtrar por **mes, sucursal, categoría, producto, método de pago y canal**, y muestra:

- 💰 Ingresos totales, ticket promedio y ganancia total/promedio
- 📅 Evolución mensual de ganancias e ingresos
- ⭐ Distribución de calificaciones de clientes
- 💵 Relación entre precio unitario y costo unitario por mes
- ☕ Propina y consumo total por transacción, según calificación

**KPIs principales:**

| Indicador | Valor |
|---|---|
| Ingresos totales | $5,10 mill. |
| Ticket promedio | $5,54 mil |
| Ganancia total | $3,62 mill. |
| Ganancia promedio | $301,31 mil |
| Transacciones | 921 |
| Calificación promedio | 4,25 ⭐ |

<img width="1276" height="712" alt="Imagen_dashboard_cafeteria" src="https://github.com/user-attachments/assets/bb2bb44a-ca97-4279-9708-087ac582af2c" />

> 📁 El archivo interactivo se encuentra en `dashboard/Dashboard cafeteria.pbix` (requiere Power BI Desktop para visualizarlo).

---

## 📂 Estructura del proyecto

```
├── data/
│   ├── raw/
│   │   └── dataset_cafeteria_moderna.csv              
│   └── clean/
│       └── data_set_limpio (4).csv       
├── notebook/
│   └── Proyecto_cafeteria_entrega (1).ipynb          
├── dashboard/
│   └── Dashboard cafeteria.pbix                
└── README.md
```

---

## 🚀 Cómo usarlo

1. Cloná el repositorio.
2. Abrí `dashboard/Dashboard cafeteria.pbix` con **Power BI Desktop**.
3. Explorá el tablero usando los filtros de la izquierda (mes, sucursal, categoría, producto, método de pago, canal).

---

## 📚 Fuentes

- Dataset generado mediante Claude IA (Anthropic): https://claude.ai
- Captura del dashboard: elaboración propia.

---

## 📄 Licencia y autoría

© 2025 – Proyecto académico realizado por **[Noelia Leder]**
Para la Universidad Tecnológica Nacional (UTN)

