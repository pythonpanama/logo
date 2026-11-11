# Guía de Contribución

¡Gracias por tu interés en colaborar con los activos de marca de **Python Panamá**!

Este repositorio almacena los logos, recursos gráficos y directrices visuales de la comunidad.

---

## Cómo Contribuir

Puedes colaborar de diferentes formas:
1. **Añadir nuevos formatos**: Si cuentas con versiones vectoriales (`.svg`), transparencias (`.png`) o iconos (`.ico`, `.webp`).
2. **Nuevas aplicaciones**: Diseños de banners para eventos, stickers, fondos de pantalla o plantillas de presentación.
3. **Mejoras a la documentación**: Clarificación en las guías de uso, paletas de colores o tipografías.

---

## Estándares y Especificaciones Técnicas

Al proponer o agregar un nuevo archivo gráfico:

- **Formatos preferidos:**
  - Vectores: SVG optimizado (sin capas innecesarias ni metadatos de software de edición propietario).
  - Raster: PNG de alta resolución con canal alfa (fondo transparente), exportado a 300 DPI para impresión o 72/144 DPI para pantallas.
- **Nomenclatura recomendada:**
  - Minúsculas y guiones bajos o medios: `python-panama-<variante>-<color|mono>.<formato>`
  - Ejemplos:
    - `python_panama_horizontal_color.svg`
    - `python_panama_icon_white.png`
- **Ubicación de archivos:**
  - Todos los logos y recursos visuales deben colocarse dentro del directorio `logos/` o en su subcarpeta correspondiente.

---

## Flujo de Trabajo (Git Workflow)

1. Haz un **Fork** del repositorio.
2. Clona tu fork localmente:
   ```bash
   git clone https://github.com/<tu-usuario>/logo.git
   cd logo
   ```
3. Crea una rama descriptiva para tus cambios:
   ```bash
   git checkout -b asset/agregar-logo-svg
   ```
4. Añade tus archivos y asegúrate de actualizar el [README.md](../README.md) si incorporas nuevas variantes.
5. Haz commit de tus cambios con un mensaje claro y conciso:
   ```bash
   git commit -m "feat(assets): agregar version vectorial SVG del logo principal"
   ```
6. Envía tu rama a tu repositorio remoto:
   ```bash
   git push origin asset/agregar-logo-svg
   ```
7. Abre un **Pull Request** detallando el propósito del cambio y adjunta vistas previas si aplica.

---

## Código de Conducta

Al participar en este proyecto, te comprometes a respetar y seguir nuestro [Código de Conducta](CODE_OF_CONDUCT.md).
