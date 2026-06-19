# 🎮 ¿Qué hace exitoso a un videojuego? Análisis de ventas globales 1980-2020

## Contexto
Análisis de un dataset de 16.598 videojuegos lanzados entre 1980 y 2020, con el 
objetivo de identificar qué plataformas, géneros y editoriales concentran el 
éxito comercial a nivel global, y cómo varían las preferencias según la región.

## Datos
- **Fuente:** dataset histórico de ventas de videojuegos (Kaggle)
- **Volumen:** 16.598 registros, 11 variables (plataforma, año, género, 
  editorial, ventas por región y ventas globales en millones de USD)
- **Período:** 1980 - 2020

## Proceso
- Estandarización del dataset original en una tabla estructurada (Tabla-Ventas)
- Construcción de tablas y gráficos dinámicos para responder 15 preguntas de 
  negocio específicas
- Funciones aplicadas: SUMAR.SI, CONTARA, SI.ERROR + ÍNDICE + COINCIDIR, 
  formato condicional, segmentaciones y minigráficos
- Armado de un Dashboard ejecutivo consolidando los indicadores clave

## Hallazgos principales

**Concentración de mercado por plataforma:** PS2, Xbox 360 y PS3 son las tres 
plataformas con más ventas históricas acumuladas, superando los 950 millones 
de copias cada una.

**Wii Sports lidera el ranking histórico** con 82,74 millones de copias 
vendidas, seguido por Super Mario Bros. (40,24M) y Mario Kart Wii (35,82M) — 
los tres títulos de Nintendo.

**Norteamérica concentra el 49% de las ventas globales** (4.392 millones), 
casi el doble que Europa (2.434 millones) y más de 3 veces el mercado japonés 
(1.290 millones).

**Las preferencias de género varían fuerte por región:** mientras que en 
Norteamérica y Europa el género Action domina claramente, en Japón el género 
Role-Playing es el que más se acerca en ventas a Action — algo que no se 
replica en ningún otro mercado.

**Nintendo es la editorial dominante** con 526 millones de copias vendidas, 
muy por encima de Take-Two Interactive (42M) y Microsoft Game Studios (22M).

**2008-2011 fue el pico histórico de la industria**, con más de 600 millones 
de copias vendidas por año, seguido de una caída sostenida hacia 2016-2017 
(coincidiendo con el cambio hacia modelos digitales/móviles no capturados en 
este dataset).

## Herramientas
Excel (tablas dinámicas, gráficos dinámicos, segmentaciones, funciones de 
búsqueda y formato condicional)
