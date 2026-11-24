[README.md](https://github.com/user-attachments/files/35362589/README.md)
# Numism-tica# NumisMusée — Catálogo Numismático

Aplicación web móvil de gestión numismática para **Jesús De la Torre**, diseñada con estética de museo (tonos beige, grafito y oro, tipografía editorial *Lora* / *Cormorant Garamond* y cifras tabulares *Lato*) y preparada para funcionar en Android, alojarse en **GitHub Pages** e incrustarse en **Google Sites**.

## Características principales

* **Almacenamiento 100% local y sin dependencias de nube:** Persistencia en **IndexedDB** con respaldo automático en `localStorage` para mantener la compatibilidad dentro de marcos incrustados (`<iframe>`) en Google Sites y navegadores móviles.
* **Planisferio interactivo en gama de grises:** Mapa mundial con D3.js y TopoJSON que resalta con colores distintivos los países presentes en la colección (incluyendo España, Hungría y demás territorios catalogados), con zoom táctil y filtrado directo al pulsar.
* **Catalogación y fotografías:** Registro de *Monedas*, *Billetes*, *Especiales* y categorías personalizadas (*Otro*), con compresión automática de imagen, orientación automática para exposición y botón manual de giro de `90°`.
* **Escala numismática y control de duplicados:** Clasificación en `FDC`, `PROOF`, `SC`, `EBC`, `MBC`, `BC`, `RC`, `MC` y `DVC`, detección de piezas duplicadas al registrar y autorrellenado de procedencias ya utilizadas.
* **Búsqueda, visita virtual e informes:** Filtrado avanzado por texto, país, tipo, estado, composición y año; galería de visita virtual; y descarga directa de tablas **CSV**, informes **PDF** y copias de seguridad completas en **JSON** sin ventanas emergentes bloqueadas.

## Estructura del proyecto

```text
├── index.html   # Aplicación web completa (interfaz, lógica, almacenamiento y exportación)
└── README.md    # Documentación del repositorio
