# layout19racks

https://nestum447.github.io/layout19racks/

# Simulación de Bodega Interactiva

Este proyecto es una **simulación de bodega** con racks interactivos, ideal para visualizar y administrar la ocupación de una bodega o inventario de manera visual. Permite seleccionar sububicaciones, marcar niveles como “Ubicación Piso”, calcular totales por rack y generar un archivo Excel con los datos y colores reflejados.

---

## Características principales

- **19 racks** interactivos, con **6 sububicaciones** en racks 1–4 nivel 1, y **3 sububicaciones** en los demás niveles/racks.
- Selección de sububicaciones con **dos estados de color**:
  - Verde → seleccionado
  - Naranja → ubicación piso
- **Totales por rack** y gran total de todos los racks:
  - Verde
  - Naranja
  - Combinadas
  - No seleccionadas
- Botón para **seleccionar/deseleccionar todos los racks**.
- Botón para **descargar un archivo Excel** que refleja:
  - Estado de cada sububicación
  - Colores en Excel (verde y naranja)
  - Totales por rack y gran total

---

## Uso

1. Abrir el archivo `index.html` en cualquier navegador moderno.
2. Interactuar con los racks:
   - Hacer clic sobre cada sububicación para cambiar su estado a verde.
   - Usar el botón “Ubicación Piso” por fila para cambiar a naranja.
   - Usar los botones de selección/deselección por fila o por rack.
3. Ver los **totales dinámicos** por rack y gran total al final de la página.
4. Presionar el botón **⬇ Descargar Excel** para exportar los datos con colores y totales.

---

## Tecnologías utilizadas

- HTML y CSS para la interfaz visual.
- JavaScript para la interactividad.
- [SheetJS (xlsx)](https://sheetjs.com/) para generar archivos Excel con formato de color y totales.

---

## Estructura del proyecto

