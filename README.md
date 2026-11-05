# Periodismo de precisión y visualización de datos

Cuaderno del módulo, publicado con GitHub Pages y el tema Just the Docs.

Sitio: https://nescolar.github.io/periodismo-de-precision/

## Estructura

- `index.md`: página única del cuaderno (todo el contenido publicado está aquí).
- `_config.yml`: configuración del sitio y menú lateral, que enlaza a las secciones de `index.md`.
- `assets/img/`: imágenes (las de `graficos/` se generan con el código de `notebooks/graficos.ipynb`).
- `assets/datos/colombia_departamentos.geojson`: mapa de departamentos que usan los ejemplos de mapas.
- `notebooks/graficos.ipynb`: cuaderno de Colab con los ejemplos de gráficos.
- Los demás `.md` son borradores guardados; no se publican (ver `exclude` en `_config.yml`).

## Cómo agregar una sección al menú

1. En `index.md`, ponga un identificador al título: `### 9. Nueva sección {#nueva-seccion}`.
2. En `_config.yml`, agregue un elemento a `nav_external_links` con `url: "https://nescolar.github.io/periodismo-de-precision/#nueva-seccion"`.

## Cajas disponibles

Se escribe la etiqueta en la línea anterior al párrafo: `{: .ojo }`, `{: .recordar }`, `{: .clase }`.
