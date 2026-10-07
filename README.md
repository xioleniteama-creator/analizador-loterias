# Analizador de loterías · Demo de datos

**Diseño y desarrollo: Xioleni Salazar** · [Portafolio](https://xioleni.com/)

[Abrir el analizador](https://xioleni.com/proyectos/analizador-loterias/)

## Descripción del proyecto

Interfaz para procesar y explorar datos históricos de lotería mediante filtros, patrones y visualizaciones interactivas. El objetivo es presentar la información de forma visual para facilitar su lectura y comparación.

## Ficha del proyecto

- **Tipo:** herramienta de análisis y visualización.
- **Código:** HTML · CSS · JavaScript · Chart.js.
- **Dificultad:** Media–alta.
- **Enfoque:** exploración, filtros y lectura visual de patrones.

## Qué incluye

- Datos de ejemplo integrados en el repositorio y paneles de análisis.
- Filtros para explorar los resultados históricos disponibles.
- Gráficas y comparativas interactivas creadas con Chart.js.
- Estructura de interfaz preparada para evolucionar con un backend.

## Datos y alcance

Esta copia estática usa una muestra histórica de solo lectura en [`backup/loterias_backup.json`](backup/loterias_backup.json). No incluye sincronización en vivo ni acciones de administración; esas funciones pertenecen al backend del sitio alojado.

Las frecuencias y patrones describen resultados pasados: no predicen sorteos futuros ni aumentan la probabilidad de ganar.

## Ejecutar localmente

Sirve la carpeta con `py -m http.server 8000` y abre `http://localhost:8000` para que el navegador pueda cargar el archivo JSON.

## Créditos

Diseño e implementación de **Xioleni Salazar**.
