# Portafolio Cartográfico y Análisis Espacial (SIG)

Colección de productos cartográficos, análisis territoriales y modelamiento espacial desarrollados en **QGIS** y **ArcGIS**, abarcando desde el ordenamiento territorial y contexto regional en Colombia hasta el análisis geomorfológico planetario.

**Autor:** Julián Andrés Cruz Sambony  
**Enfoque:** Sistemas de Información Geográfica (SIG), Teledetección, Modelado Ráster y Gestión del Territorio.

---

## 1. Cartografía Planetaria y Modelamiento Ráster (Proyecto MARSNOVA)

### Ruta Candidata, Matriz de Costos y Zonas Bloqueadas en Marte (Cráter Gale)
![Ruta y matriz de costos MARSNOVA](mapas/mapa_marsnova_matriz_de_coste_ruta.png)

* **Contexto:** Desarrollo cartográfico para el desafío *NASA Space Apps Challenge 2026*.
* **Procesamiento Técnico:** Derivación de pendiente, rugosidad e índice de posición topográfica a partir de un Modelo Digital de Terreno (DTM de 1 m) de **HiRISE** (MRO). Generación de una matriz de costo relativo (clases 1–6) a resolución de 10 m con restricción de pendientes $>20^\circ$ (zonas bloqueadas) para el trazado de rutas seguras de exploración humana (EVA).
* **Sistema de Referencia (SRC):** `USER:100000 - Mars Gale HiRISE Equirectangular 137.3E` | **Escala:** 1:15.000.

---

### Evaluación de Sitio Candidato para Base Operativa (P02)
![Evaluación base P02](mapas/mapa_marsnova_evaluacion_base.png)

* **Procesamiento Técnico:** Análisis multicriterio a escala local sobre ortoimagen HiRISE y ráster de fricción (10 m) para validar la viabilidad topográfica del punto medio de ruta (`P02`), confirmando pendiente local $\approx 8,01^\circ$ y costo relativo clase `2/6`.

---

## 2. Cartografía Territorial y Urbana (Colombia)

### Localización de La Vega (Cauca) en el Contexto Regional del Macizo Colombiano
![Localización La Vega Macizo Colombiano](mapas/mapa_localizacion_la_vega_macizo_colombiano.png)

* **Objetivo:** Contextualización político-administrativa y regional del municipio de La Vega dentro de la estrella fluvial del Macizo Colombiano y el departamento del Cauca.
* **Fuentes de Datos:** Instituto Geográfico Agustín Codazzi (IGAC - Colombia en Mapas) y servicios base Esri.
* **Sistema de Referencia (SRC):** `MAGNA-SIRGAS 2018` / `WGS 84` | **Escala:** 1:400.000.

---

### Mapa de Localización Urbana: Comuna 1 y Área de Estudio (Popayán, Cauca)
![Localización Comuna 1 Popayán](mapas/mapa_localizacion_comuna_1_area_de_estudio.png)

* **Objetivo:** Delimitación cartográfica multiescalar (departamento, municipio, comunas y división barrial) para caracterización urbana y delimitación de área de estudio en Popayán.
* **Fuentes de Datos:** Alcaldía de Popayán (SIG POP) e Instituto Geográfico Agustín Codazzi (IGAC).
* **Sistema de Referencia (SRC):** `MAGNA-SIRGAS 2018 / Origen-Nacional (EPSG:9377)` | **Escala:** 1:82.000.
---

### Zonificación Cafetera: Subregión Centro del Departamento del Cauca
![Zonificación Cafetera Subregión Centro Cauca](mapas/mapa_zonificacion_cafetera_subregion_centro_cauca.jpg)

* **Objetivo:** Delimitación espacial y caracterización político-administrativa de los municipios que integran la Subregión Cafetera Centro del Cauca (Morales, Cajibío, Piendamó - Tunía, El Tambo, Popayán, Totoró, Timbío, Rosas, Sotará, Puracé y La Sierra), articulada con esquemas de localización multiescalar a nivel departamental y nacional.
* **Fuentes de Datos:** Instituto Geográfico Agustín Codazzi (IGAC), Federación Nacional de Cafeteros (FNC) e imagen base satelital de Google.
* **Sistema de Referencia (SRC):** `MAGNA-SIRGAS / Origen Nacional (EPSG:9377)` | **Escala:** 1:100.000.
