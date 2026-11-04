# Periodismo de precisión y visualización de datos

Cuaderno del módulo, publicado con GitHub Pages y el tema Just the Docs.

## Estructura

```
index.md                      Inicio, ruta del módulo
antecedentes.md               Antecedentes (en construcción)
que-es.md                     ¿Qué es el periodismo de precisión? (en construcción)
precision-e-investigacion.md  Diferencia con el periodismo de investigación (en construcción)
estadistica.md                Relación con la estadística y el método estadístico
fundamentos/                  Pregunta problema, variables, población y muestra, unidad de análisis, parámetros, indicadores
eda/                          Frecuencias, tendencia central, dispersión, forma y atípicos, correlación, cambio en el tiempo
inferencia/                   Descriptiva e inferencial, error y sesgo, margen de error, significancia, tamaño del efecto, validez
del-hallazgo-al-grafico.md    Elegir el gráfico según la pregunta
talleres/                     Taller 1 (MetroArena) y Taller 2 (redes sociales y productividad)
referencias.md                Glosario y referencias
assets/img/                   Figuras
assets/datos/                 Archivos para los talleres
_config.yml                   Configuración del sitio
```

## Cómo editar una página

Abra el archivo `.md` en GitHub, pulse el lápiz (Edit), escriba y pulse **Commit changes**. El sitio se actualiza solo en uno o dos minutos.

Cajas disponibles (se escribe la etiqueta en la línea anterior al párrafo):

```
{: .idea }
Texto de la idea clave.

{: .historia }
Texto de la historia de Valeria.

{: .ojo }
Advertencia.

{: .puente }
Conexión con la visualización.
```

Respuesta oculta de un ejercicio:

```
<details markdown="1">
<summary>Ver respuesta</summary>

Texto de la respuesta.
</details>
```

Para agregar una página nueva dentro de una sección, copie una existente y cambie `title`, `parent` y `nav_order` en el encabezado.

## Publicación

En **Settings > Pages**, elija *Deploy from a branch*, rama `main`, carpeta `/ (root)`.

Si el repositorio no se llama `periodismo-de-precision`, cambie la línea `baseurl` de `_config.yml` por `"/nombre-del-repositorio"`.
