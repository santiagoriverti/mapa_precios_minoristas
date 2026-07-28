# Mapa Interactivo de Precios — ICM-UADE

Mapa georreferenciado de precios de canastas representativas en supermercados argentinos, elaborado por el **Instituto de Economía de la UADE (INECO)** a partir de los datos públicos del [SEPA](https://datos.produccion.gob.ar/dataset/sepa-precios).

🗺️ **[Ver mapa](https://santiagoriverti.github.io/mapa_precios_minoristas/)**

---

## ¿Qué muestra el mapa?

Cada punto representa una sucursal de supermercado relevada por el SEPA. El color indica el costo de la canasta seleccionada: **verde = más barato**, **rojo = más caro**.

**Abril 2026 — 2.373 sucursales en las 24 provincias**

| Canasta | Costo promedio nacional |
|---------|------------------------|
| Vulnerable | $252.982 |
| Popular | $451.672 |
| Media | $634.923 |
| Media Alta | $879.459 |
| Celíaca Media | $691.836 (+9,0% vs Media) |
| Vegana Básica | $427.033 (−5,5% vs Popular) |

---

## Cómo usar el mapa

**Panel de filtros** (esquina inferior izquierda):
- **Canasta** — cambiar entre las 6 canastas
- **Cadena** — filtrar por Coto, DIA, Carrefour, Disco, etc.
- **Provincia** — aislar una jurisdicción

**Click sobre una sucursal** — muestra el nombre del local, cadena, barrio, provincia y costo de la canasta seleccionada.

---

## Fuente de datos

Los precios provienen del **Sistema Electrónico de Publicidad de Precios Argentinos (SEPA)**, Ministerio de Economía de la Nación. Las cadenas están obligadas a publicar diariamente los precios vigentes en cada punto de venta.

El mapa se genera con el pipeline del repositorio [precios_minoristas_supermercados](https://github.com/santiagoriverti/precios_minoristas_supermercados).

---

## Contacto

Instituto de Economía — INECO/UADE  
✉️ investigacion@uade.edu.ar  
🌐 [INECO](https://www.uade.edu.ar/sites/investigacion/instituto-de-economia-ineco/)
