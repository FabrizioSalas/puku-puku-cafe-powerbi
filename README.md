# ☕ Dashboard de Control de Gestión: Puku Puku Café

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-8C4A2F?style=flat)
![Datos](https://img.shields.io/badge/Datos-simulados-lightgrey?style=flat)

Dashboard interactivo en Power BI para el control de gestión de una cafetería peruana con tres sedes (Miraflores, Barranco y San Isidro). Proyecto académico elaborado con **datos simulados**; no representa información real de ningún negocio.

![Dashboard de Control de Gestión](dashboard_puku_imagen.png)

## 🎯 Objetivo

Reunir en una sola vista los indicadores clave de la operación de la cafetería, para apoyar decisiones sobre ventas, costos, menú y personal.

## ❓ Qué permite responder

- 📈 ¿Cómo evolucionan las ventas y cuánto crecen frente al mes anterior?
- 📍 ¿Qué sedes y categorías generan más ventas?
- ⏰ ¿En qué horas y días se concentra la demanda?
- 🍽️ ¿Qué productos conviene potenciar o revisar según su margen y su popularidad?
- 💰 ¿Los costos de alimentos y de mano de obra están dentro de los rangos esperados?

## 📊 Contenido del dashboard

**Indicadores (KPIs)**
- 💵 Ventas totales y % de crecimiento vs. mes anterior
- 🎟️ Ticket promedio y promedio de personas por ticket
- 🥘 % Food Cost, con alerta de rango
- 👨‍🍳 % Labor Cost y costo laboral por hora
- ⚖️ % Prime Cost (food cost + labor cost) frente a una meta de referencia
- 🪑 RevPASH (ingreso por asiento disponible por hora)

**Visualizaciones**
- 🧩 Matriz BCG (ingeniería de menú): margen unitario vs. cantidad vendida por producto y categoría
- ⏰ Picos de demanda por hora
- 🏢 Ventas totales por sede y categoría
- 📋 Tabla resumen por sede: ventas, ticket promedio, % food cost y total de tickets

**Filtros:** 📅 fecha (2023–2024), 📍 sede, 🏷️ categoría y 🗓️ día de la semana.

## 🔎 Hallazgos principales

- 📍 **Miraflores lidera las ventas**, con cerca del 39% del total (521,829 de 1,351,781), seguida de San Isidro (~33%) y Barranco (~29%). La diferencia viene del **tráfico y no del gasto**: el ticket promedio es casi igual en las tres sedes (entre 83.76 y 85.37), pero Miraflores atiende más tickets (6,212, frente a 5,152 y 4,658).
- ⏰ **La demanda se concentra en tres franjas**: desayuno (~9 h), almuerzo (~13 h, el pico más alto) y cena (~19 h). Entre el almuerzo y la cena y después de las 21 h la demanda cae, lo que ayuda a planificar los turnos del personal.
- 💰 **Los costos están bajo control**: el food cost (32.17%) está dentro del rango definido y es casi idéntico entre sedes (32.14%–32.21%). Con un labor cost de 14.30%, el prime cost (46.46%) queda por debajo de la referencia de 60% del dashboard.
- 🥩 **Ingeniería de menú**: las cantidades vendidas por producto son muy parejas (alrededor de 3,000 a 3,150 unidades), así que el **margen es lo que diferencia a los productos**. El Rib Eye a la Cerveza destaca con el margen unitario más alto (~33). En cambio, Café Americano, Muffin de Arándanos y Espresso Doble venden bien pero con margen bajo (menos de 10): una oportunidad para revisar precio o receta.
- 🧁 **Postres y snacks aportan poco** en las tres sedes, mientras que comidas, cenas y desayunos concentran la mayor parte de las ventas. Hay espacio para impulsar venta cruzada con postres y bebidas.
- 📉 **Alerta de crecimiento**: el último mes muestra una caída de 23.33% frente al mes anterior. Conviene revisar si se debe a estacionalidad o a menos tickets.

## 🛠️ Herramientas

Power BI Desktop · DAX · [Power Query]

## 📂 Contenido del repositorio

- `dashboard puku.pbix`: archivo del dashboard en Power BI
- `dashboard_puku_imagen.png`: vista previa del dashboard
- `README.md`: descripción del proyecto

## 🚀 Cómo abrirlo

1. Descarga el archivo `dashboard puku.pbix`.
2. Ábrelo con [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (gratuito para Windows).
3. Para una vista rápida, mira la imagen de arriba.

## 👤 Autor

**César Fabrizio Salas Molina** · [LinkedIn](https://www.linkedin.com/in/c%C3%A9sar-fabrizio-salas-molina-84565b401) · [GitHub](https://github.com/FabrizioSalas)
