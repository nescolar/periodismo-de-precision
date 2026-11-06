---
title: Inicio
nav_order: 1
description: "Cuaderno del módulo de periodismo de precisión y visualización de datos"
permalink: /
---

# Periodismo de precisión y visualización de datos
{: .fs-9 }

> "La información es la gasolina del siglo XXI, y la analítica de datos, el motor de combustión."
>
> Peter Sondergaard (2011)

---

## ¿Qué es la visualización de datos? {#visualizacion}

La visualización de datos nos permite convertir la información en imágenes, gráficos y otros recursos visuales que facilitan su comprensión. En lugar de enfrentarnos a largas listas de números o tablas, podemos ver la información de una manera más clara, identificar patrones, comparar resultados, reconocer diferencias y descubrir situaciones que quizás pasarían desapercibidas. Visualizar datos es:

1. **Explorar** unos datos para responder preguntas o plantear nuevas cuestiones.
2. **Analizar** patrones, relaciones y valores atípicos entre los datos.
3. **Explicar** una historia con datos.

## ¿Qué es la estadística? {#estadistica}

La **estadística**, en singular, es la ciencia de recolectar, organizar, analizar e interpretar información. **Las estadísticas**, en plural, son números obtenidos de un conjunto o colección de informaciones.

Es, en síntesis, una herramienta que nos permite entender mejor lo que sucede a nuestro alrededor a partir de los datos. Así, nos ayuda a interpretar lo que ocurre, sacar conclusiones y tomar decisiones mejor fundamentadas y confiables.

| | Estadística descriptiva | Estadística inferencial |
|:--|:--|:--|
| Qué hace | **Resume lo que ocurrió.** Está formada por los métodos gráficos y numéricos que se utilizan para resumir y procesar los datos y transformarlos en información. | **Estima y generaliza.** Constituye la base para hacer predicciones, previsiones y estimaciones que se utilizan para transformar la información en conocimiento. |
| Ejemplo | Promedio de edad de los estudiantes de posgrado en Uninorte. | Satisfacción con la democracia estimada a partir de encuestas. |

## El método estadístico como columna vertebral {#metodo}

El método estadístico se organiza en siete etapas que forman un ciclo de mejoramiento continuo. Este mismo recorrido describe el trabajo de un reportaje de precisión, y coincide en lo esencial con la pirámide invertida del periodismo de datos propuesta por Paul Bradshaw, que López describe en cinco pasos: compilar, limpiar, contextualizar, combinar y comunicar.

| Etapa del método estadístico | Pregunta que orienta la etapa | Equivalente en el trabajo periodístico |
|:--|:--|:--|
| 1. Problema | ¿Qué situación afecta a la comunidad? | Identificar un asunto de relevancia pública, sea una sospecha, una percepción extendida o un vacío de información. |
| 2. Pregunta | ¿Cómo se formula de manera medible? | Convertir la intuición en una pregunta que nombre población, [indicador](#indicador) y periodo. |
| 3. Recolección | ¿De dónde salen los datos? | Compilar datos de fuentes primarias (encuesta propia) o secundarias (registros oficiales, portales de datos abiertos, solicitudes de información). |
| 4. Organización | ¿Los datos son confiables? | Limpiar y depurar: duplicados, faltantes, categorías inconsistentes, valores imposibles. |
| 5. Análisis | ¿Qué muestran los datos? | Análisis exploratorio, medidas descriptivas, tablas cruzadas y, cuando corresponde, inferencia. |
| 6. Interpretación | ¿Qué significa y qué no significa? | Contextualizar, contrastar con expertos y fuentes, y delimitar lo que los datos permiten afirmar. |
| 7. Decisión | ¿Qué se hace con el hallazgo? | Comunicar al público con transparencia metodológica, mediante texto, gráficos o aplicaciones. |

Correspondencia entre el método estadístico y el trabajo periodístico de precisión. Elaboración propia a partir de Salón (s. f.), Bradshaw (2012) y López (2016).
{: .fs-2 }

---

## Conocimientos previos de estadística {#conocimientos-previos}

### 1. Indicador: de lo que quiero contar a lo que voy a medir {#indicador}

Todo trabajo con datos empieza con un **problema** y una **pregunta**. Pero entre "quiero contar si la violencia intrafamiliar es más grave en unos departamentos que en otros" y la base de datos hay un paso que a menudo se salta: decidir **con qué número** se va a responder. Ese número es el **indicador**.

Un **indicador** es una medida cuantitativa que resume un aspecto de la realidad que nos interesa y permite compararlo entre lugares, grupos o momentos. Es el puente entre lo que queremos contar y lo que vamos a medir.

#### Variable e indicador no son lo mismo

La **variable** es el dato que se registra de cada caso: la edad de cada persona, el departamento donde ocurrió un hecho, si una víctima es hombre o mujer. El **indicador** resume esas variables para todo un grupo, casi siempre como una división entre dos cantidades: un **numerador** (lo que contamos) y un **denominador** (con respecto a qué lo contamos).

| Variable (de cada caso) | Indicador (del grupo) |
|:--|:--|
| Género de cada víctima | Porcentaje de víctimas mujeres = víctimas mujeres ÷ total de víctimas × 100 |
| Departamento donde se registró cada caso | Tasa por 100.000 habitantes = casos del departamento ÷ población del departamento × 100.000 |
| Horas de sueño de cada estudiante | Mediana de horas de sueño del grupo |

#### Del problema al indicador

El indicador se elige a partir de la pregunta, no al revés. Así se ve el recorrido en dos de los ejercicios del módulo:

| Paso | Ejercicio 2: clima y violencia | Ejercicio 3: violencia intrafamiliar |
|:--|:--|:--|
| **Problema** | Se repite que el calor pone de mal genio a la gente. | La violencia intrafamiliar es uno de los delitos más denunciados del país. |
| **¿Qué quiero contar?** | Si en Barranquilla los días más calientes son más violentos. | En qué departamentos el problema es más grave. |
| **Pregunta medible** | ¿Los días con mayor temperatura máxima registran más casos de violencia interpersonal? (Barranquilla, 2010-2016) | ¿Qué departamentos registraron más casos por habitante entre 2018 y 2020? |
| **Indicador** | Correlación entre la temperatura máxima y los casos de violencia del día | Tasa de casos registrados por cada 100.000 habitantes |
| **Fórmula** | *r* de Pearson entre dos variables diarias | Casos registrados ÷ población × 100.000 |
| **Fuentes** | Medicina Legal (casos) e IDEAM (temperatura) | Policía Nacional (numerador) y DANE (denominador) |

Fíjese en que la pregunta medible ya nombra la **población o el territorio**, el **indicador** y el **periodo**. Si a la pregunta le falta alguno de los tres, todavía no está lista para buscar datos.

#### Los indicadores más usados en el periodismo de datos

| Indicador | Qué responde | Ejemplo |
|:--|:--|:--|
| Conteo o volumen | ¿Cuántos casos hubo? | 15.559 casos de violencia intrafamiliar en Antioquia en 2020 |
| [Porcentaje o proporción](#frecuencias) | ¿Qué parte del total? El numerador está incluido en el denominador. | El 78,5 % de las víctimas fueron mujeres |
| Razón | ¿Cuántos de un grupo por cada tantos de otro? El numerador no está en el denominador. | 93 hombres atendidos por cada 100 mujeres |
| [Tasa](#volumen-tasa) | ¿Qué tan frecuente es, según el tamaño de la población? | 234 casos por cada 100.000 habitantes |
| [Promedio o mediana](#tendencia-central) | ¿Cuál es el valor típico? | La mediana de horas de sueño es 6,6 |
| Cambio | ¿Cuánto subió o bajó? | La confianza en estudiantes de otros colegios pasó de 22 % a 44 % |

{: .ojo }
> **Puntos porcentuales no es lo mismo que porcentaje.** Si un indicador pasa de 22 % a 44 %, subió **22 puntos porcentuales**, pero aumentó **100 %**, porque se duplicó. Las dos frases son correctas y dicen cosas distintas. Use "puntos porcentuales" para la diferencia entre dos porcentajes y "por ciento" para el cambio relativo.

#### Indicadores de estructura, proceso y resultado

En la gestión pública y en las organizaciones, los indicadores se suelen clasificar según qué parte del problema miden. La clasificación sirve también para hacer preguntas periodísticas más precisas:

| Tipo | Qué mide | Ejemplo en educación |
|:--|:--|:--|
| **Estructura** | Los recursos con que se cuenta | Número de docentes por cada 100 estudiantes |
| **Proceso** | Lo que se hace con esos recursos | Porcentaje de colegios con gobierno escolar activo |
| **Resultado** | Lo que se logra | Puntaje promedio en las pruebas Saber 11 |

Una historia es más sólida cuando no se queda en un solo tipo: si un resultado empeora, la pregunta siguiente es qué pasó con la estructura y con el proceso.

#### ¿Qué hace un buen indicador?

- **Es válido:** mide lo que queremos contar. Los casos *registrados* de violencia intrafamiliar miden denuncias, no toda la violencia que ocurre; hay que decirlo. Repase la [validez](#validez).
- **Es comparable:** se calcula igual en todos los lugares y periodos que comparamos. Si cambia la forma de registrar los datos, el indicador puede subir o bajar sin que cambie la realidad.
- **Declara su numerador y su denominador:** el lector debe poder saber qué se dividió entre qué y de dónde salió cada cifra.
- **Se puede repetir:** con las mismas fuentes y el mismo cálculo, otra persona llega al mismo número.
- **Se entiende:** "234 casos por cada 100.000 habitantes" se lee mejor que "0,00234 casos per cápita".

{: .clase }
> **Actividad rápida.** Para cada problema, escriba lo que quiere contar, una pregunta medible y un indicador con su numerador y su denominador.
>
> 1. "Los jóvenes no votan."
> 2. "Cada vez más estudiantes abandonan el colegio."
> 3. "En este barrio roban más que en el resto de la ciudad."

<details markdown="1">
<summary>Ver respuesta</summary>

Hay más de una respuesta correcta. Estas son algunas posibles:

1. **Qué quiero contar:** si los jóvenes votan menos que el resto. **Pregunta:** ¿qué porcentaje de las personas de 18 a 28 años habilitadas para votar lo hizo en la última elección, comparado con las mayores de 28? **Indicador:** participación electoral por grupo de edad = votantes del grupo ÷ habilitados del grupo × 100. Ojo: si solo se cuentan los votantes jóvenes, sin el denominador, no se sabe si son muchos o pocos.
2. **Qué quiero contar:** si la deserción escolar está aumentando. **Pregunta:** ¿cómo cambió la deserción en los colegios públicos de la ciudad en los últimos cinco años? **Indicador:** tasa de deserción = estudiantes que abandonaron en el año ÷ estudiantes matriculados ese año × 100, para cada año.
3. **Qué quiero contar:** si el riesgo de ser víctima de hurto es mayor en ese barrio. **Pregunta:** ¿cuántos hurtos se denunciaron por cada 10.000 habitantes en el barrio y en la ciudad el último año? **Indicador:** tasa de hurtos denunciados = hurtos denunciados ÷ habitantes × 10.000. Ojo: por ser denuncias, un barrio donde la gente denuncia más puede parecer más peligroso.

</details>

### 2. Variables y sus tipos {#variables}

Una **variable** es una característica que podemos observar, registrar o medir y que puede tomar diferentes valores según la persona, el objeto o el caso que estemos estudiando. En términos sencillos, una variable es aquello que queremos conocer.

| Pregunta | Variable |
|:--|:--|
| ¿Cuántas horas duerme un estudiante? | Horas de sueño |
| ¿Qué medio de transporte utiliza para ir a la universidad? | Medio de transporte |
| ¿Por quién piensa votar una persona? | Intención de voto |
| ¿Qué edad tienen los ciudadanos? | Edad |
| ¿Qué tan satisfechos están los ciudadanos con el Gobierno? | Nivel de satisfacción |
| ¿Cuántas noticias políticas consulta una persona al día? | Número de noticias consultadas |

Podemos distinguir dos grandes grupos: variables cualitativas y cuantitativas.

#### A. Variables cualitativas: describen características o categorías

Son aquellas que permiten clasificar personas, objetos o situaciones según una característica. No expresan una cantidad numérica, aunque algunas puedan codificarse con números en una base de datos.

| Variable | Posibles respuestas |
|:--|:--|
| Medio de transporte | Bus, carro, moto, bicicleta, caminar |
| Estado civil | Soltero, casado, divorciado, viudo |
| Partido político | Partido Liberal, Conservador, Pacto Histórico, otros |
| Nivel educativo | Primaria, secundaria, universitario, posgrado |
| Opinión sobre el Gobierno | A favor, en contra, ni a favor ni en contra |
| Departamento de residencia | Atlántico, Bolívar, Magdalena, Antioquia |

Hay dos tipos que vale la pena reconocer:

- **Nominales**: las categorías no tienen un orden establecido. Por ejemplo: ciudad de residencia, partido político o medio de transporte.
- **Ordinales**: las categorías tienen un orden. Por ejemplo: nivel de satisfacción (muy insatisfecho, insatisfecho, satisfecho, muy satisfecho) o nivel educativo.

#### B. Variables cuantitativas: expresan cantidades

Son aquellas que representan números y permiten responder preguntas como cuánto, cuántos o con qué frecuencia.

| Variable | Posibles valores |
|:--|:--|
| Edad | 18, 19, 20, 21 años |
| Horas de sueño | 5, 6, 7, 8 horas |
| Ingresos mensuales | $1.500.000, $2.000.000 |
| Número de hijos | 0, 1, 2, 3 |
| Tiempo de desplazamiento | 15, 30, 45 minutos |
| Número de publicaciones en redes sociales | 2, 5, 10 |

También podemos distinguir dos tipos:

- **Discretas**: expresan cantidades que se cuentan y generalmente toman valores enteros. Por ejemplo: número de hijos, número de estudiantes en un salón, cantidad de votos o número de noticias publicadas.
- **Continuas**: expresan cantidades que se miden y pueden tomar valores con decimales. Por ejemplo: estatura (1,65 m), peso (58,5 kg), tiempo de desplazamiento (32,5 minutos) o temperatura (28,4 °C).

Una forma sencilla de diferenciarlas:

| Discreta | Continua |
|:--:|:--:|
| **3** hijos | **1,65** m de estatura |
| No podemos tener 2,5 hijos en un conteo de personas. | Podemos medir 1,651 m o 1,652 m. |

{: .ojo }
> Una confusión frecuente: las variables cualitativas no son lo mismo que las discretas. Las primeras describen categorías; las discretas son cuantitativas y representan cantidades que contamos. Por eso, una clasificación correcta sería:
>
> - **Cualitativas**: nominales y ordinales.
> - **Cuantitativas**: discretas y continuas.

{: .clase }
> **Actividad rápida.** Clasifiquemos las siguientes variables.
>
> 1. Número de tintos que te tomas en el día.
> 2. Barrio donde vives.
> 3. Talla de camisa que usas (S, M, L, XL).
> 4. Minutos que pasas en el trancón para llegar a la universidad.
> 5. Marca de tu celular.
> 6. Número de mensajes de WhatsApp sin leer que tienes ahora mismo.
> 7. Cómo calificas el almuerzo de la cafetería (malo, regular, bueno, excelente).
> 8. Temperatura en Barranquilla al mediodía.

<details markdown="1">
<summary>Ver respuesta</summary>

| Variable | Tipo | Por qué |
|:--|:--|:--|
| 1. Número de tintos al día | Cuantitativa discreta | Se cuenta: 0, 1, 2, 3 tintos. No hay 2,5 tintos en el conteo. |
| 2. Barrio donde vives | Cualitativa nominal | Son categorías sin orden: ningún barrio va "antes" que otro. |
| 3. Talla de camisa | Cualitativa ordinal | Son categorías con un orden claro: S < M < L < XL. |
| 4. Minutos en el trancón | Cuantitativa continua | Se mide y admite decimales: 32,5 minutos. |
| 5. Marca del celular | Cualitativa nominal | Son categorías sin orden. |
| 6. Mensajes de WhatsApp sin leer | Cuantitativa discreta | Se cuenta: 0, 1, 2, 3 mensajes. |
| 7. Calificación del almuerzo | Cualitativa ordinal | Las categorías tienen orden (malo < regular < bueno < excelente), pero no son cantidades. |
| 8. Temperatura al mediodía | Cuantitativa continua | Se mide y admite decimales: 33,4 °C. |

</details>

### 3. Unidad de análisis: ¿sobre quién o sobre qué recogemos información? {#unidad-analisis}

Es el elemento concreto que estamos estudiando, es decir, aquello sobre lo que registramos información. Por ejemplo:

- En una encuesta sobre intención de voto, cada ciudadano es una unidad de análisis.
- En un estudio sobre desigualdad entre países, cada país es una unidad de análisis.
- En una investigación sobre noticias falsas, cada publicación analizada puede ser una unidad de análisis.
- En un estudio sobre universidades, cada universidad puede ser una unidad de análisis.

**Ejemplo práctico.** Queremos investigar la confianza de los jóvenes en las instituciones políticas.

| Persona (unidad de análisis) | Edad (variable) | Confianza en el Congreso (variable) |
|:--|:--:|:--|
| Ana | 19 | Baja |
| Juan | 22 | Media |
| María | 20 | Alta |
| Pedro | 24 | Baja |

Cada fila representa una unidad de análisis (una persona). Las columnas contienen las variables que queremos estudiar.

#### ¿Y qué es un dato?

Es el valor específico que encontramos cuando observamos una variable en una unidad de análisis.

| Unidad de análisis | Variable | Dato |
|:--|:--|:--|
| Ana | Edad | 19 años |
| Colombia | Tasa de desempleo | El porcentaje registrado en un periodo determinado |

En otras palabras, una variable es lo que queremos conocer y un dato es el valor que encontramos.

### 4. Población y muestra: ¿a quiénes estamos estudiando? {#poblacion-muestra}

Cuando queremos investigar un fenómeno, generalmente nos interesa conocer algo sobre un grupo de personas, países, instituciones o situaciones. Sin embargo, no siempre podemos estudiar a todos los integrantes de ese grupo. Por eso, utilizamos los conceptos de población y muestra.

#### A. Población

Es el conjunto completo de personas, objetos o casos sobre los que queremos obtener información y sacar conclusiones. Por ejemplo:

- Si queremos conocer la opinión de los universitarios sobre la educación pública, la población serían los estudiantes universitarios que definamos como objeto de estudio.
- Si queremos conocer la intención de voto para las elecciones presidenciales en Colombia, la población serían los ciudadanos habilitados para votar.
- Si queremos estudiar la confianza en las instituciones democráticas de América Latina, la población serían las personas de los países incluidos en el estudio.
- Si queremos conocer el nivel de satisfacción de los estudiantes de una universidad, la población serían todos sus estudiantes.

#### B. Muestra

Es una parte de esa población que seleccionamos para recoger información y realizar el estudio. Imaginemos que queremos conocer qué piensan los estudiantes de la Universidad del Norte sobre el uso de la inteligencia artificial en sus clases.

- **Población**: los 14.000 estudiantes de la universidad (cifra hipotética).
- **Muestra**: 400 estudiantes seleccionados para responder una encuesta.

**Tres ideas para entender qué es una muestra**

1. Una muestra es una fotografía de la población: un grupo más pequeño que estudiamos para conocer las características del conjunto.
2. Para que sea representativa, sus participantes deben seleccionarse mediante un método aleatorio, de modo que todos los integrantes de la población tengan una probabilidad conocida de ser elegidos y se reduzca el sesgo de selección.
3. Si la población tiene grupos con características diferentes, conviene que la muestra refleje su composición: por ejemplo, la proporción de hombres y mujeres, de habitantes por estrato socioeconómico o de personas por región.

**Una precisión.** Si en una población el 60 % son mujeres y el 40 % hombres, una muestra que busca reflejar esa composición debería mantener proporciones similares: en una muestra de 400 personas, unas 240 mujeres y 160 hombres. Esto se conoce como **muestreo estratificado** cuando se seleccionan participantes al azar dentro de cada grupo. Cuadrar las proporciones no basta: si dentro de cada grupo las personas se eligen a conveniencia, la muestra puede seguir sesgada. Y cuando una muestra no queda con la composición de la población, las encuestas corrigen esa diferencia mediante la **ponderación**.

| Investigación | Población | Muestra |
|:--|:--|:--|
| Intención de voto presidencial | Ciudadanos habilitados para votar | 1.500 ciudadanos encuestados |
| Opinión sobre el transporte público en Barranquilla | Usuarios del transporte público | 600 usuarios |
| Confianza en el Congreso | Ciudadanos colombianos | 2.000 ciudadanos |
| Hábitos de consumo de noticias | Jóvenes colombianos de 18 a 28 años | 500 jóvenes |

**Visualicemos la diferencia.** La muestra es una parte de la población que seleccionamos para estudiarla.

![La muestra es una parte de la población que seleccionamos para estudiarla]({{ '/assets/img/poblacion_muestra.svg' | relative_url }})

{: .recordar }
No se trata simplemente de tener muchos participantes, sino de seleccionar a las personas adecuadas y de una manera que permita que la muestra se parezca a la población que queremos estudiar. Si encuestamos a 1.000 personas que siguen una misma cuenta política en Instagram, no podemos afirmar que sus opiniones representan a todos los colombianos.

{: .clase }
> **Actividad rápida.** En cada caso, identifica la población y la muestra.
>
> 1. La tienda de la esquina quiere saber si sus clientes están contentos con la atención y le pregunta a 50 personas que compran durante una semana.
> 2. Un colegio de 1.200 estudiantes quiere saber cuántas horas al día ven series sus alumnos y encuesta a 120 de ellos.
> 3. Una emisora quiere saber qué canción de champeta prefieren sus oyentes en Barranquilla y llama a 300 oyentes elegidos al azar.
> 4. Una cuenta de Instagram pregunta "¿Estás de acuerdo con el pico y placa?" y responden 2.000 personas. ¿Sirven esas respuestas para saber qué piensan todos los conductores de la ciudad?

<details markdown="1">
<summary>Ver respuesta</summary>

| Caso | Población | Muestra |
|:--|:--|:--|
| 1. Tienda de la esquina | Todos los clientes de la tienda | Los 50 clientes consultados durante la semana |
| 2. Colegio | Los 1.200 estudiantes del colegio | Los 120 estudiantes encuestados |
| 3. Emisora | Todos los oyentes de la emisora en Barranquilla | Los 300 oyentes elegidos al azar |
| 4. Encuesta en Instagram | Todos los conductores de la ciudad | Las 2.000 personas que respondieron |

En el caso 4, la respuesta es no: aunque son muchas respuestas, solo participaron quienes siguen esa cuenta y quisieron opinar, y no todos son necesariamente conductores. Es una muestra grande, pero no representa a la población.

</details>

### 5. Estadísticos de la población y de la muestra {#parametros}

Aquí aparece una distinción importante: no es lo mismo conocer una característica de toda la población que calcularla utilizando solamente una muestra.

#### A. Parámetros poblacionales

Son valores que describen una característica de toda la población. Por ejemplo:

- La edad promedio de todos los estudiantes de una universidad.
- El porcentaje de todos los ciudadanos colombianos que confía en el Congreso.
- La proporción de todos los electores que apoya a un candidato.

El problema es que muchas veces no conocemos estos valores porque no podemos estudiar a toda la población.

#### B. Estadísticos muestrales

Son valores calculados con los datos de la muestra. Como casi nunca conocemos los parámetros, usamos los estadísticos para estimarlos.

La teoría del muestreo estadístico nos permite hacer afirmaciones probables sobre los valores de la población, llamados parámetros (θ), a partir de una muestra aleatoria lo suficientemente representativa. Se busca que la estimación que procede del estimador esté lo más cerca posible del valor del parámetro, con un mínimo de variabilidad.

Ejemplos de estadísticos muestrales:

- La edad promedio de los 400 estudiantes encuestados.
- El porcentaje de los 1.500 ciudadanos que manifiesta apoyar a un candidato.
- La proporción de los 600 usuarios encuestados que está satisfecha con el transporte público.

**Ejemplo para entenderlo.** Imaginemos que queremos conocer cuánto tiempo tardan los estudiantes de una universidad en llegar a clase.

- **Población**: 14.000 estudiantes.
- **Parámetro poblacional**: el tiempo promedio que tardan los 14.000 estudiantes.
- **Muestra**: 400 estudiantes.
- **Estadístico muestral**: el tiempo promedio calculado a partir de esos 400 estudiantes.

Supongamos que los resultados son:

| Parámetro poblacional | Estadístico muestral |
|:--:|:--:|
| **?** | **35 minutos** |
| Desconocido. El promedio real de los 14.000 estudiantes. | Promedio encontrado entre los 400 encuestados. |

¿Podemos afirmar que todos los estudiantes tardan en promedio 35 minutos? No exactamente. Lo que podemos decir es que, según la muestra, el tiempo promedio estimado es de 35 minutos. El valor real de toda la población podría ser ligeramente diferente.

{: .recordar }
El parámetro describe a toda la población; el estadístico describe a la muestra y nos ayuda a estimar el parámetro.

### 6. Estadística descriptiva e inferencial {#descriptiva-inferencial}

Son dos formas de trabajar con los datos que responden a preguntas diferentes.

#### A. Estadística descriptiva

Nos permite organizar, resumir y presentar la información que tenemos. Su propósito es describir qué encontramos en los datos observados. Por ejemplo:

- Calcular la edad promedio de los estudiantes encuestados.
- Identificar qué porcentaje de los ciudadanos consultados apoya al Gobierno.
- Mostrar en un gráfico qué medios de transporte utilizan los estudiantes.
- Comparar los niveles de desempleo de cinco departamentos.
- Identificar cuál candidato obtuvo más votos en una elección.

Si encuestamos a 100 estudiantes y encontramos que 65 utilizan transporte público, podemos decir que el 65 % de los estudiantes encuestados utiliza este medio. Eso es estadística descriptiva: estamos describiendo los resultados obtenidos.

#### B. Estadística inferencial

Nos permite utilizar los datos de una muestra para estimar o sacar conclusiones sobre una población más grande. Por ejemplo:

- Encuestar a 1.500 colombianos para estimar la intención de voto de los electores del país.
- Consultar a 800 ciudadanos para estimar el nivel de confianza en el Congreso.
- Entrevistar a 500 jóvenes para conocer las tendencias de consumo de noticias entre los jóvenes de una población determinada.

La diferencia es que no nos quedamos en describir las respuestas de las personas encuestadas, sino que buscamos aproximarnos a lo que sucede en el conjunto de la población.

**La diferencia en una pregunta**

| | Descriptiva | Inferencial |
|:--|:--|:--|
| Pregunta | ¿Qué encontramos en las 1.500 personas encuestadas? | ¿Qué podemos estimar sobre todos los electores? |
| Respuesta | El 42 % manifestó su intención de votar por el candidato A. | Si la muestra fue seleccionada adecuadamente, podemos estimar que alrededor del 42 % de la población electoral apoya al candidato A, teniendo en cuenta la incertidumbre del estudio. |

{: .clase }
Cuando un titular dice «El 60 % de los colombianos desconfía del Congreso», debemos preguntarnos: ¿se encuestó a todos los colombianos o a una muestra? ¿Cuántas personas participaron? ¿Cómo fueron seleccionadas?

### 7. Error y sesgo: ¿qué puede salir mal en una encuesta? {#error-sesgo}

Este es uno de los conceptos más importantes para el periodismo de precisión. No basta con encontrar una cifra y publicarla. También necesitamos saber qué tan confiable es y qué problemas puede tener.

Una encuesta puede presentar resultados diferentes a la realidad por distintas razones. Dos conceptos fundamentales son el error muestral y el sesgo.

#### A. Error muestral o aleatorio

Es la diferencia que puede existir entre el resultado que obtenemos al estudiar una muestra y el resultado real de toda la población. ¿Por qué ocurre? Porque estamos preguntándole a una parte de la población, no a todos.

**Ejemplo.** Queremos conocer el porcentaje de ciudadanos que aprueba la gestión del presidente. Realizamos una encuesta a 1.000 personas y encontramos que el 50 % aprueba su gestión. Pero si pudiéramos preguntarle a todos los ciudadanos, el resultado podría ser del 48 %, del 51 % o del 49 %. La diferencia se debe, en parte, a que nuestra muestra es solo una representación de la población.

Aquí aparece el famoso **margen de error**. Imaginemos que la encuesta reporta un margen de error de ±3 puntos porcentuales:

| Límite inferior | Aprobación registrada en la muestra | Límite superior |
|:--:|:--:|:--:|
| 47 % | **50 %** | 53 % |

El resultado estimado es 50 %, pero existe incertidumbre asociada al muestreo: el intervalo ilustrativo va de 47 % a 53 %. Técnicamente, su interpretación también depende del nivel de confianza utilizado y de los supuestos del diseño muestral.

**¿Qué pasa si aumentamos el tamaño de la muestra?** En condiciones comparables, una muestra más grande suele reducir el error muestral:

- Encuestar a 100 personas puede producir un margen de error mayor.
- Encuestar a 1.000 personas puede reducirlo.
- Encuestar a 5.000 personas puede reducirlo todavía más.

{: .ojo }
Aumentar la muestra no garantiza que la encuesta sea confiable. Para eso también debemos revisar cómo se seleccionaron los participantes.

#### B. Sesgo o error sistemático

El sesgo ocurre cuando la forma de seleccionar a las personas o de recoger la información produce resultados distorsionados de manera sistemática. En otras palabras, no es simplemente que el resultado varíe un poco por azar, sino que existe un problema que empuja los resultados en una dirección determinada.

**Ejemplo cotidiano.** Queremos conocer qué piensan los estudiantes universitarios sobre la calidad de la educación virtual. Decidimos publicar una encuesta en un grupo de WhatsApp conformado exclusivamente por estudiantes que están inconformes con sus clases virtuales. ¿Qué podría ocurrir? Es probable que encontremos un nivel de inconformidad mucho mayor al que realmente existe entre todos los estudiantes. El problema no es necesariamente el número de respuestas. El problema es a quiénes les preguntamos.

{: .ojo }
El sesgo no desaparece por aumentar el número de encuestados. Podemos tener 10.000 respuestas y seguir obteniendo resultados equivocados si seleccionamos mal a las personas.

#### Tipos de sesgo

**1. Sesgo de selección.** Ocurre cuando la manera de elegir a los participantes deja por fuera a determinados grupos o favorece la participación de otros. Por ejemplo:

- Consultar únicamente a los seguidores de un candidato para conocer la intención de voto de toda la ciudad.
- Realizar una encuesta sobre transporte público únicamente entre personas que utilizan carro particular.
- Preguntar por la satisfacción con la universidad solamente a los estudiantes que participan en actividades institucionales.
- Hacer una encuesta digital sobre acceso a internet sin considerar a quienes tienen dificultades de conectividad.

**2. Sesgo de información.** Ocurre cuando la información que recogemos no refleja adecuadamente la realidad, por errores en las preguntas, las respuestas o los mecanismos de medición. Por ejemplo:

- Preguntar: «¿Está de acuerdo con que el Gobierno continúe desperdiciando recursos públicos?». La pregunta está formulada para inducir una respuesta negativa.
- Preguntarle a una persona cuánto gastó exactamente en alimentación durante los últimos doce meses. Puede que no recuerde la cifra.
- Preguntar por un comportamiento socialmente sensible, como el consumo de sustancias, y obtener respuestas inexactas por temor al juicio de los demás.
- Registrar incorrectamente la edad de los encuestados.

**3. Sesgo de no respuesta.** Ocurre cuando las personas seleccionadas para participar no responden y quienes no lo hacen tienen características u opiniones diferentes de quienes sí participan. Por ejemplo, una encuesta telefónica sobre confianza en las instituciones tiene dificultades para contactar a personas jóvenes porque estas casi no contestan llamadas de números desconocidos. Si los jóvenes tienen opiniones diferentes a las de los adultos, los resultados podrían representar de manera inadecuada a la población.

### 8. Error muestral frente a sesgo: no son lo mismo {#error-vs-sesgo}

Esta diferencia es fundamental para evaluar una encuesta o una investigación.

| Error muestral | Sesgo |
|:--|:--|
| Se produce por estudiar una muestra y no toda la población. | Se produce por problemas en la selección o medición. |
| Es aleatorio. | Es sistemático. |
| Puede reducirse aumentando la muestra, en condiciones comparables. | No se corrige simplemente aumentando la muestra. |
| Se relaciona con la precisión. | Se relaciona con la validez. |
| Se refleja en el margen de error. | Puede no ser visible en el margen de error. |

**Ejemplo para cerrar.** Imaginemos dos encuestas electorales:

- **Encuesta A**: consulta a 1.000 personas seleccionadas mediante un diseño probabilístico adecuado.
- **Encuesta B**: consulta a 10.000 personas que voluntariamente respondieron una encuesta publicada en redes sociales.

¿Cuál es más confiable? Aunque la encuesta B tiene diez veces más respuestas, la encuesta A puede ofrecer resultados más representativos si su diseño muestral es adecuado.

{: .recordar }
La cantidad de respuestas no garantiza por sí sola la calidad de una encuesta.

### 9. Validez, confiabilidad y reproducibilidad {#validez}

En el lenguaje de la medición, la **validez** es el grado en que un dato representa realmente lo que pretende representar, y equivale a la ausencia de error sistemático.

La **confiabilidad** o precisión es el grado en que mediciones repetidas de un fenómeno estable producen resultados similares, y equivale a la ausencia de error aleatorio. Una medición puede ser precisa sin ser válida, como una báscula que siempre marca dos kilos de más, y por ello el investigador no debe confundir la exactitud aparente de una cifra con decimales con su correspondencia con la realidad.

La metodología de la visualización de datos nos obliga a pensar qué se quiere comunicar con ellos, qué es importante y cómo se tiene que hacer.

### 10. Frecuencias y porcentajes {#frecuencias}

A partir de aquí veremos las medidas que usamos para **describir** los datos. Son las que aparecen, de forma explícita o implícita, en casi todos los gráficos.

La **frecuencia** es cuántas veces aparece cada categoría. El **porcentaje** es esa frecuencia dividida por el total y multiplicada por 100. Los porcentajes permiten comparar grupos de distinto tamaño; por eso, casi siempre dicen más que los conteos. Al publicar un porcentaje, conviene decir sobre cuántos casos se calculó.

**Ejemplo.** Preguntamos a 200 estudiantes cómo llegan a la universidad:

| Medio | Frecuencia | Porcentaje |
|:--|:--:|:--:|
| Bus | 90 | 45 % |
| Moto | 50 | 25 % |
| Carro | 30 | 15 % |
| Bicicleta o a pie | 30 | 15 % |
| **Total** | **200** | **100 %** |

**En Excel:** `=CONTAR.SI(rango;"Bus")` cuenta cuántas veces aparece una categoría. Una tabla dinámica (Insertar > Tabla dinámica) lo hace para todas las categorías a la vez y puede mostrar el resultado como porcentaje del total.

**En el gráfico:** se muestran con un [gráfico de barras](#barras).

### 11. Tablas cruzadas {#tablas-cruzadas}

Una **tabla cruzada** muestra cómo se combinan dos variables cualitativas. Responde preguntas como "¿el porcentaje de X es distinto según el grupo Y?". Lo importante es calcular el porcentaje **dentro de cada grupo**, no sobre el total.

**Ejemplo.** ¿Trabajan más los estudiantes de la jornada nocturna?

| Jornada | Estudiantes | Trabajan | Porcentaje que trabaja |
|:--|:--:|:--:|:--:|
| Diurna | 80 | 20 | 25 % |
| Nocturna | 40 | 28 | 70 % |

En números absolutos la diferencia parece pequeña (20 frente a 28), pero en porcentaje es enorme: en la jornada nocturna trabaja casi tres de cada cuatro estudiantes.

**En Excel:** en una tabla dinámica, ponga una variable en filas y otra en columnas, y en Valores elija *Mostrar valores como > % del total de filas*.

**En el gráfico:** se muestran con [barras agrupadas](#barras-agrupadas) o barras apiladas al 100 %.

### 12. Tendencia central: media, mediana y moda {#tendencia-central}

Son medidas que resumen en un solo número el valor "típico" de una variable.

- La **media** (o promedio) es la suma de todos los valores dividida por cuántos son.
- La **mediana** es el valor del centro cuando ordenamos los datos de menor a mayor: la mitad queda por debajo y la otra mitad por encima.
- La **moda** es el valor o la categoría que más se repite. Es la única que sirve para variables nominales.

La media se deja arrastrar por los valores extremos; la mediana no. Cuando hay unos pocos valores muy altos, como en salarios o precios de vivienda, la mediana describe mejor la situación típica.

**Ejemplo.** En una empresa de 10 personas, nueve ganan 2 millones de pesos y el gerente gana 20 millones. La media es (9 × 2 + 20) ÷ 10 = **3,8 millones**, pero nadie en la empresa gana eso. La mediana es **2 millones**, que sí describe a la mayoría. Y si en una tienda de ropa la talla más vendida es la M, la moda es M.

**En Excel:** `=PROMEDIO(rango)`, `=MEDIANA(rango)` y `=MODA.UNO(rango)`.

**En el gráfico:** la media o la mediana se pueden agregar como una línea de referencia sobre barras o histogramas.

### 13. Dispersión: qué tan distintos son los datos entre sí {#dispersion-datos}

Dos grupos pueden tener el mismo promedio y ser muy distintos. La **dispersión** mide qué tan separados están los valores.

- El **rango** es la diferencia entre el valor más alto y el más bajo.
- La **desviación estándar** indica, aproximadamente, cuánto se aleja un valor típico del promedio. Cuanto más grande, más dispersos están los datos.
- Los **cuartiles** dividen los datos ordenados en cuatro partes iguales. El primer cuartil (Q1) deja por debajo el 25 % de los datos y el tercer cuartil (Q3) deja por debajo el 75 %.
- El **rango intercuartílico (RIC)** es Q3 menos Q1: el ancho de la mitad central de los datos. A diferencia del rango, no lo afectan los valores extremos.

**Ejemplo.** Dos rutas de bus tienen una espera promedio de 12 minutos. En la ruta A siempre se espera entre 11 y 13 minutos; en la ruta B, a veces 2 minutos y a veces 23. El promedio es igual, pero la ruta A es predecible y la B no.

Si medimos nueve esperas en un paradero, ordenadas: 6, 7, 8, 9, 10, 11, 12, 13 y 15 minutos, el rango es 15 − 6 = 9 minutos, Q1 es 8, la mediana es 10 y Q3 es 12. El RIC es 12 − 8 = 4: **la mitad central de las esperas está entre 8 y 12 minutos**.

**En Excel:** `=MIN(rango)`, `=MAX(rango)`, `=DESVEST.M(rango)`, `=CUARTIL.INC(rango;1)` para Q1 y `=CUARTIL.INC(rango;3)` para Q3.

**En el gráfico:** la dispersión se ve en el [histograma](#histograma) y en el [diagrama de caja](#caja), cuya caja es justamente el rango intercuartílico.

### 14. Forma de los datos y valores atípicos {#forma-atipicos}

La **forma** de una variable describe cómo se reparten sus valores. Es **simétrica** si se parece a ambos lados del centro, y **asimétrica** si tiene una cola larga hacia un lado. Por ejemplo, los ingresos tienen una cola hacia la derecha: muchos ingresos modestos y pocos muy altos. En ese caso, la media queda por encima de la mediana.

Un **valor atípico** es un dato muy alejado del resto. Una regla común lo define así: es atípico todo valor mayor que **Q3 + 1,5 × RIC** o menor que **Q1 − 1,5 × RIC**.

**Ejemplo.** En las nueve esperas del punto anterior, Q3 = 12 y RIC = 4, así que el límite superior es 12 + 1,5 × 4 = **18 minutos**. Si un día alguien espera 30 minutos, ese valor es atípico.

{: .ojo }
Un atípico puede ser un error de digitación o un caso real y excepcional, que a veces es la historia más interesante de la base. Por eso se verifica antes de decidir qué hacer con él: nunca se borra sin revisarlo.

**En el gráfico:** el [histograma](#histograma) muestra la forma completa; el [diagrama de caja](#caja) muestra los atípicos como puntos sueltos.

### 15. Relación entre variables: la correlación {#correlacion}

La **correlación** mide si dos variables cuantitativas se mueven juntas. Se resume con el coeficiente **r**, que va de −1 a 1:

- Cerca de **1**: relación positiva fuerte. Cuando una sube, la otra también (horas de estudio y nota).
- Cerca de **−1**: relación negativa fuerte. Cuando una sube, la otra baja (precio de un producto y cantidad que se compra).
- Cerca de **0**: no hay relación lineal (talla de zapato y nota de matemáticas en adultos).

{: .ojo }
**Correlación no es causalidad.** Que dos cosas se muevan juntas no significa que una cause la otra. Las ventas de helado y los ahogamientos en la playa suben juntos en verano, pero el helado no causa ahogamientos: los dos aumentan por el calor.

**En Excel:** `=COEF.DE.CORREL(rango1;rango2)`.

**En el gráfico:** se muestra con un [gráfico de dispersión](#dispersion), o con uno de [burbujas](#burbujas) si se quiere agregar una tercera variable.

### 16. Volumen frente a tasa {#volumen-tasa}

Un **volumen** es una cifra absoluta (número de casos). Una **tasa** es esa cifra dividida por el tamaño del grupo, para poder comparar grupos de distinto tamaño (casos por cada 100 personas, por cada 10.000 habitantes). Comparar volúmenes entre grupos de distinto tamaño es uno de los errores más frecuentes del periodismo con datos.

**Ejemplo.** El municipio X tuvo 45 casos de dengue y tiene 30.000 habitantes. El municipio Y tuvo 120 casos y tiene 400.000 habitantes. En volumen, Y parece estar peor. En tasa, X tiene 15 casos por cada 10.000 habitantes e Y tiene 3: **el problema es cinco veces más grave en X**.

**En el gráfico:** los [mapas de coropletas](#coropletas) siempre deben usar tasas o porcentajes. Un mapa de volúmenes solo muestra dónde vive más gente.

{: .clase }
> **Actividad rápida.** Un restaurante registró cuánto tardaron siete domicilios, en minutos: 20, 25, 25, 30, 35, 40 y 90.
>
> 1. Calcula la media, la mediana y la moda.
> 2. ¿Cuál de las tres describe mejor el tiempo típico de un domicilio? ¿Por qué?
> 3. Con Q1 = 25 y Q3 = 37,5, ¿hay algún valor atípico?
> 4. En el barrio A hubo 30 robos y viven 10.000 personas; en el barrio B hubo 12 robos y viven 2.000. ¿Dónde es más grave el problema?

<details markdown="1">
<summary>Ver respuesta</summary>

1. Media: 265 ÷ 7 ≈ **37,9 minutos**. Mediana: el cuarto valor ordenado, **30 minutos**. Moda: **25 minutos** (aparece dos veces).
2. La **mediana**. El domicilio de 90 minutos arrastra la media hacia arriba; la mediana no se ve afectada.
3. Sí. El RIC es 37,5 − 25 = 12,5 y el límite superior es 37,5 + 1,5 × 12,5 = 56,25 minutos. El domicilio de **90 minutos es atípico**: vale la pena averiguar qué pasó.
4. En el **barrio B**. Aunque tiene menos robos, su tasa es de 60 por cada 10.000 habitantes, frente a 30 en el barrio A.

</details>

---

## Ejercicio práctico 1: redes sociales y productividad {#ejercicio-1}

### Contexto {#ejercicio-1-contexto}

Existe una percepción muy repetida en conversaciones, columnas de opinión y redes: **pasar mucho tiempo en redes sociales nos hace menos productivos**. Antes de escribir sobre eso, un periodista de precisión se pregunta qué dicen los datos.

Para practicar vamos a usar una base publicada en Kaggle, *Social Media vs Productivity: Realistic Behavioral Dataset*, con 30.000 registros de personas y 19 variables sobre su uso de redes sociales, su trabajo, su descanso y su productividad. De esa base tomamos una **muestra aleatoria de 500 registros completos**.

[Descargar la base en Excel]({{ '/assets/datos/Dataset_redes_sociales_productividad_muestra500.xlsx' | relative_url }}){: .btn .btn-primary }

El archivo tiene tres hojas: **Leeme** (origen de los datos, cómo se tomó la muestra y diccionario de variables), **Datos** (los 500 registros, en formato de tabla) y **Resumen** (medidas descriptivas ya calculadas, para comprobar resultados).

{: .ojo }
> Los datos son **simulados**. Según su ficha en Kaggle, los registros imitan patrones de comportamiento y su autor les agregó a propósito datos faltantes, ruido y valores atípicos para que sirvan de práctica. No describen a personas reales: los usamos para entrenar el método, no para sacar conclusiones sobre la población.

Estas son las variables principales:

| Variable | Qué mide | Tipo |
|:--|:--|:--|
| edad | Edad en años | Cuantitativa discreta |
| genero | Hombre, Mujer, Otro | Cualitativa nominal |
| sector_laboral | Estudiante, Educación, Salud, Finanzas, Tecnología, Desempleado | Cualitativa nominal |
| horas_redes_dia | Horas diarias en redes sociales | Cuantitativa continua |
| red_preferida | Facebook, Instagram, TikTok, Telegram, Twitter | Cualitativa nominal |
| notificaciones_dia | Notificaciones recibidas al día | Cuantitativa discreta |
| productividad_percibida | Qué tan productiva se cree la persona (0 a 10) | Cuantitativa continua |
| productividad_real | Productividad medida (0 a 10) | Cuantitativa continua |
| nivel_estres | Estrés autorreportado (1 a 10) | Cualitativa ordinal codificada con números |
| horas_sueno | Horas de sueño por noche | Cuantitativa continua |
| usa_apps_concentracion | Usa aplicaciones de concentración (Sí o No) | Cualitativa nominal |

### ¿Qué vamos a hacer? {#ejercicio-1-tareas}

Vamos a hacer un **análisis exploratorio de datos (EDA)**: resumir y graficar las variables para conocer los datos **antes** de afirmar algo. La pregunta que guía el ejercicio es:

> ¿Las personas que pasan más horas al día en redes sociales tienen una productividad real menor?

Trabaje en Excel, en la hoja **Datos**. Como los datos están en formato de tabla, puede usar el nombre de cada columna dentro de las fórmulas, por ejemplo `=PROMEDIO(Datos[horas_redes_dia])`.

#### Paso 1. Reconocer la base

1. ¿Cuántas filas y cuántas variables tiene la hoja Datos?
2. ¿Cuál es la unidad de análisis?
3. Clasifique cada variable de la tabla anterior según su tipo y compare con la columna *Tipo*. ¿Está de acuerdo con que `nivel_estres` se trate como ordinal?

<details markdown="1">
<summary>Ver respuesta</summary>

1. 500 filas y 20 columnas: 19 variables más `fila_original`, que solo sirve para ubicar el registro en el archivo de Kaggle.
2. Cada persona (simulada). Cada fila es una persona.
3. Es discutible, y vale la pena discutirlo: el estrés tiene números del 1 al 10, pero son categorías ordenadas de una escala de autorreporte. La distancia entre 2 y 3 no es necesariamente igual a la distancia entre 8 y 9.

</details>

#### Paso 2. Frecuencias: ¿cuántos hay en cada categoría?

1. Con una tabla dinámica (Insertar > Tabla dinámica), calcule el porcentaje de personas por `red_preferida`, por `sector_laboral` y por `usa_apps_concentracion`. En Valores, elija *Mostrar valores como > % del total general*.
2. Haga un gráfico de barras de `red_preferida`, ordenado de mayor a menor y con el eje desde cero.

<details markdown="1">
<summary>Valores para comprobar</summary>

| red_preferida | % | sector_laboral | % |
|:--|:--:|:--|:--:|
| Facebook | 25,2 | Estudiante | 18,0 |
| TikTok | 20,8 | Educación | 18,0 |
| Instagram | 19,4 | Desempleado | 17,6 |
| Telegram | 19,4 | Tecnología (TI) | 16,2 |
| Twitter | 15,2 | Salud | 16,0 |
| | | Finanzas | 14,2 |

El 30,6 % usa aplicaciones de concentración.

</details>

#### Paso 3. Resumen numérico: valor típico y dispersión

Para `horas_redes_dia`, `productividad_real`, `horas_sueno` y `notificaciones_dia`, calcule:

| Medida | Fórmula en Excel |
|:--|:--|
| Media | `=PROMEDIO(Datos[horas_redes_dia])` |
| Mediana | `=MEDIANA(Datos[horas_redes_dia])` |
| Desviación estándar | `=DESVEST.M(Datos[horas_redes_dia])` |
| Mínimo y máximo | `=MIN(...)` y `=MAX(...)` |
| Primer y tercer cuartil | `=CUARTIL.INC(Datos[horas_redes_dia];1)` y `=CUARTIL.INC(Datos[horas_redes_dia];3)` |

Luego responda: ¿en qué variables la media y la mediana se parecen? ¿Qué le dice eso sobre la presencia de valores extremos?

<details markdown="1">
<summary>Valores para comprobar</summary>

| Variable | Media | Mediana | Desv. estándar | Mín. | Máx. | Q1 | Q3 |
|:--|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| horas_redes_dia | 3,20 | 3,16 | 1,96 | 0 | 15,04 | 1,75 | 4,47 |
| productividad_real | 5,05 | 5,06 | 1,86 | 0,60 | 9,15 | 3,49 | 6,57 |
| horas_sueno | 6,59 | 6,62 | 1,47 | 3 | 10 | 5,51 | 7,66 |
| notificaciones_dia | 60,33 | 60 | 8,21 | 36 | 88 | 55 | 66 |

En las cuatro variables la media y la mediana son casi iguales: hay pocos valores extremos o están compensados. La hoja **Resumen** del archivo trae estos mismos cálculos.

</details>

#### Paso 4. Forma y valores atípicos

1. Haga un histograma de `horas_redes_dia` y otro de `notificaciones_dia` (Insertar > Gráfico estadístico > Histograma). Describa su forma.
2. Con Q1, Q3 y la regla de 1,5 × RIC, calcule los límites a partir de los cuales un valor es atípico: `Q1 − 1,5 × (Q3 − Q1)` y `Q3 + 1,5 × (Q3 − Q1)`.
3. ¿Cuántos valores atípicos hay en cada variable? ¿Los eliminaría? ¿Por qué?

<details markdown="1">
<summary>Ver respuesta</summary>

- **horas_redes_dia:** el límite superior es 4,47 + 1,5 × 2,72 ≈ 8,6 horas. Hay **1** valor atípico: una persona con 15,04 horas diarias.
- **notificaciones_dia:** los límites son 38,5 y 82,5. Hay **8** valores atípicos.
- No se eliminan sin verificarlos. Con datos reales habría que consultar la fuente; aquí, además, la ficha de Kaggle advierte que se agregaron atípicos a propósito en el uso de redes y en las notificaciones.

</details>

#### Paso 5. Comparar grupos

1. Con una tabla dinámica, calcule el promedio de `productividad_real` según `usa_apps_concentracion` y según `sector_laboral`.
2. Haga un diagrama de caja de `productividad_real` por `sector_laboral` (Insertar > Gráfico estadístico > Cuadro y bigotes).
3. ¿Qué grupo tiene la productividad más baja? ¿La diferencia le parece grande?

<details markdown="1">
<summary>Valores para comprobar</summary>

- Usa apps de concentración: 5,03. No usa: 5,06.
- Por sector, los promedios van de 4,75 (Tecnología) a 5,17 (Estudiante y Desempleado).
- Las diferencias son pequeñas frente a una desviación estándar de 1,86. Con grupos de 71 a 90 personas, pueden deberse al azar de la muestra.

</details>

#### Paso 6. Relaciones entre variables

1. Haga un gráfico de dispersión con `horas_redes_dia` en el eje horizontal y `productividad_real` en el vertical. Calcule la correlación con `=COEF.DE.CORREL(Datos[horas_redes_dia];Datos[productividad_real])`.
2. Repita con `productividad_percibida` y `productividad_real`.
3. Cree una columna nueva, `brecha`, con la fórmula `=[@productividad_percibida]-[@productividad_real]`. ¿Qué porcentaje de personas tiene una brecha positiva, es decir, se cree más productiva de lo que es?

<details markdown="1">
<summary>Valores para comprobar</summary>

- Horas en redes y productividad real: r = −0,004, prácticamente cero. Los puntos forman una nube sin dirección.
- Productividad percibida y real: r = 0,96, una relación muy fuerte.
- El 84,6 % de las personas tiene una brecha positiva; en promedio, se califican 0,56 puntos por encima de su productividad real.

</details>

#### Paso 7. Concluir

1. Escriba los tres hallazgos más importantes de su exploración.
2. Responda la pregunta guía con los datos.
3. Proponga un titular honesto y el gráfico que usaría para acompañarlo.

<details markdown="1">
<summary>Ver respuesta</summary>

1. Las horas en redes no se relacionan con la productividad real; las personas se califican por encima de su productividad real; hay pocos valores atípicos, concentrados en horas en redes y notificaciones.
2. En estos datos, **no**: quienes pasan más horas en redes no tienen una productividad real menor. La sospecha no se confirma, y eso también es un hallazgo. Como los datos son simulados, el resultado refleja cómo se construyó la simulación, no cómo se comporta la gente.
3. Por ejemplo: "En 500 registros simulados, pasar más horas en redes no se asocia con menor productividad", acompañado de un gráfico de dispersión con una nota que aclare que los datos son simulados.

</details>

### El mismo ejercicio en Google Colab {#ejercicio-1-colab}

Después de hacer el ejercicio en Excel, repita el análisis con Python en Google Colab. El cuaderno lee la base directamente desde este sitio, así que no necesita descargar nada ni instalar programas. Tiene dos partes:

1. **Variable por variable:** frecuencias y gráficos de barras para las variables cualitativas; media, mediana, desviación estándar, cuartiles, asimetría, valores atípicos, histograma y diagrama de caja para cada variable cuantitativa.
2. **Relaciones entre variables:** matriz de correlaciones, las correlaciones más fuertes, diagramas de dispersión para la pregunta guía, una comprobación con la correlación de Spearman y la comparación de la productividad por grupos.

Cada resultado viene con una pregunta para comentar y, al final, un espacio para escribir las conclusiones.

[Abrir el EDA en Google Colab](https://colab.research.google.com/github/nescolar/periodismo-de-precision/blob/main/notebooks/eda_redes_productividad.ipynb){: .btn .btn-primary }

---

## Gráficos: ¿cuál usar? {#graficos}

Para visualizar datos, ya sea para explorarlos, analizarlos o explicarlos, hay múltiples opciones. Sin embargo, para cada tipo de variable y acorde a lo que se pretende contar, hay gráficos sugeridos. A continuación se presentan los más utilizados, en función de: comparar, mostrar tendencias, distribuciones, correlaciones y mapas.

Cada gráfico se presenta con una descripción sencilla, el tipo de variable para el que es más común, una recomendación y un ejemplo con su código. El código funciona en Google Colab: puede copiar cada ejemplo en una celda o abrir el cuaderno con todos los ejemplos.

[Abrir todos los ejemplos en Google Colab](https://colab.research.google.com/github/nescolar/periodismo-de-precision/blob/main/notebooks/graficos.ipynb){: .btn .btn-primary }

### Comparar {#comparar}

Sirven para poner lado a lado los valores de varias categorías y ver cuál es mayor, cuál es menor y por cuánto.

#### Gráfico de barras {#barras}

Cuando se quiere comparar un conjunto de valores y establecer un ranking. Como el ojo humano es muy bueno comparando distancias de elementos que están situados sobre un mismo eje, el gráfico de barras no solo descubre los valores más altos y los más bajos, sino que también ayuda a tener una intuición bastante acertada de la diferencia existente entre unos valores y otros.

**Es más común para:** una variable **cualitativa** (nominal u ordinal), que va en un eje, y una **cuantitativa** (un conteo, un porcentaje o un promedio), que define la longitud de cada barra.

{: .recordar }
El eje cuantitativo debe empezar siempre en 0; si no, las diferencias se magnifican y confunden al lector. Ordene las barras de mayor a menor para comunicar el ranking y use barras horizontales cuando los nombres de las categorías sean largos.

**Ejemplo.** Medio principal por el que se informan 200 estudiantes (datos ilustrativos).

![Gráfico de barras: Medio principal por el que se informan 200 estudiantes (datos ilustrativos).]({{ '/assets/img/graficos/01_barras.png' | relative_url }})

<details markdown="1">
<summary>Ver el código para Colab</summary>

```python
import matplotlib.pyplot as plt

# Datos ilustrativos: medio principal por el que se informan 200 estudiantes
medios = ["Instagram", "TikTok", "WhatsApp", "Televisión", "X (Twitter)", "Radio", "Prensa digital"]
estudiantes = [62, 48, 35, 22, 15, 10, 8]

# Ordenamos de menor a mayor para que la barra más larga quede arriba
datos = sorted(zip(estudiantes, medios))
valores = [v for v, m in datos]
nombres = [m for v, m in datos]

fig, ax = plt.subplots(figsize=(7, 4))
ax.barh(nombres, valores, color="#2a78d6")
ax.set_xlim(0, 70)                       # el eje cuantitativo empieza en 0
for i, v in enumerate(valores):
    ax.text(v + 1, i, v, va="center")    # etiqueta con el valor de cada barra
ax.set_title("Medio principal para informarse (200 estudiantes)", loc="left")
ax.set_xlabel("Número de estudiantes")
ax.spines[["top", "right"]].set_visible(False)
plt.show()
```

</details>

#### Gráfico de barras agrupadas {#barras-agrupadas}

Es una versión del gráfico de barras en la que, para cada categoría, se ponen varias barras una al lado de la otra. Permite comparar cómo se reparte cada categoría entre distintos grupos y, al mismo tiempo, comparar los grupos entre sí.

**Es más común para:** dos variables **cualitativas** (por ejemplo, fuente de noticias y grupo de edad) y una **cuantitativa** (el porcentaje o el conteo).

{: .recordar }
No lo sobrecargue: con más de tres o cuatro grupos por categoría se vuelve difícil de leer. En ese caso es mejor hacer varios gráficos de barras separados.

**Ejemplo.** Fuente principal de noticias según la edad (datos ilustrativos).

![Gráfico de barras agrupadas: Fuente principal de noticias según la edad (datos ilustrativos).]({{ '/assets/img/graficos/02_barras_agrupadas.png' | relative_url }})

<details markdown="1">
<summary>Ver el código para Colab</summary>

```python
import matplotlib.pyplot as plt
import numpy as np

# Datos ilustrativos: fuente principal de noticias por grupo de edad (%)
fuentes = ["Redes sociales", "Televisión", "Radio", "Prensa"]
jovenes = [64, 18, 8, 10]    # 18 a 29 años
mayores = [30, 40, 15, 15]   # 30 años o más

x = np.arange(len(fuentes))  # posición de cada grupo de barras
ancho = 0.38

fig, ax = plt.subplots(figsize=(7, 4))
ax.bar(x - ancho/2, jovenes, ancho, label="18 a 29 años", color="#2a78d6")
ax.bar(x + ancho/2, mayores, ancho, label="30 años o más", color="#eb6834")
ax.set_xticks(x, fuentes)
ax.set_ylim(0, 75)                       # el eje empieza en 0
ax.set_ylabel("Porcentaje de encuestados")
ax.set_title("Fuente principal de noticias según la edad", loc="left")
ax.legend(frameon=False)
ax.spines[["top", "right"]].set_visible(False)
plt.show()
```

</details>

### Mostrar tendencias {#tendencias}

Sirven para ver cómo cambia una variable cuantitativa a lo largo del tiempo.

#### Gráfico de líneas {#lineas}

Representa el cambio de una variable a lo largo del tiempo: el tiempo va en el eje horizontal y una línea une los valores de cada momento. Puede tener una o varias líneas para comparar la evolución de distintas categorías.

**Es más común para:** una variable de **tiempo** (días, meses, años) y una o más variables **cuantitativas**.

{: .recordar }
Cuide el rango del eje vertical: si no empieza en 0, las pendientes se exageran y los cambios parecen más grandes de lo que son. Evite poner demasiadas líneas; con más de cuatro o cinco el gráfico pierde legibilidad.

**Ejemplo.** Visitas mensuales a un medio digital, por canal (datos ilustrativos).

![Gráfico de líneas: Visitas mensuales a un medio digital, por canal (datos ilustrativos).]({{ '/assets/img/graficos/03_lineas.png' | relative_url }})

<details markdown="1">
<summary>Ver el código para Colab</summary>

```python
import matplotlib.pyplot as plt

# Datos ilustrativos: visitas mensuales a un medio digital (miles)
meses = ["Ene", "Feb", "Mar", "Abr", "May", "Jun", "Jul", "Ago", "Sep", "Oct", "Nov", "Dic"]
web = [120, 118, 125, 130, 128, 135, 140, 138, 145, 150, 148, 155]
app = [40, 45, 50, 58, 63, 70, 78, 85, 90, 98, 105, 112]

fig, ax = plt.subplots(figsize=(7, 4))
ax.plot(meses, web, color="#2a78d6", linewidth=2, marker="o")
ax.plot(meses, app, color="#eb6834", linewidth=2, marker="o")
ax.text(11.3, web[-1], "Sitio web", va="center")    # etiquetas directas al final
ax.text(11.3, app[-1], "Aplicación", va="center")
ax.set_ylim(0, 180)                     # rango honesto del eje y
ax.set_xlim(-0.5, 13)
ax.set_ylabel("Visitas (miles)")
ax.set_title("Visitas mensuales al medio, por canal", loc="left")
ax.grid(axis="y", alpha=0.3)
ax.spines[["top", "right"]].set_visible(False)
plt.show()
```

</details>

#### Gráfico de pendientes {#pendientes}

Es un gráfico de líneas con solo dos puntos: el antes y el después. Muestra de un vistazo qué categorías subieron, cuáles bajaron y cuánto.

**Es más común para:** una variable **cualitativa** (las categorías) y una **cuantitativa** medida en **dos momentos**.

{: .recordar }
Los dos ejes, el del antes y el del después, deben tener el mismo mínimo y el mismo máximo; si no, la comparación es engañosa.

**Ejemplo.** Porcentaje de hogares con internet en cinco municipios, 2020 y 2025 (datos ilustrativos).

![Gráfico de pendientes: Porcentaje de hogares con internet en cinco municipios, 2020 y 2025 (datos ilustrativos).]({{ '/assets/img/graficos/04_pendientes.png' | relative_url }})

<details markdown="1">
<summary>Ver el código para Colab</summary>

```python
import matplotlib.pyplot as plt

# Datos ilustrativos: hogares con internet (%) en cinco municipios
municipios = ["Municipio A", "Municipio B", "Municipio C", "Municipio D", "Municipio E"]
antes = [35, 42, 60, 25, 55]    # 2020
despues = [58, 52, 72, 40, 47]  # 2025

fig, ax = plt.subplots(figsize=(5.5, 4.5))
for nombre, a, d in zip(municipios, antes, despues):
    color = "#2a78d6" if d > a else "#eb6834"   # azul si sube, naranja si baja
    ax.plot([0, 1], [a, d], color=color, linewidth=2, marker="o")
    ax.text(-0.05, a, f"{nombre}  {a} %", ha="right", va="center")
    ax.text(1.05, d, f"{d} %", ha="left", va="center")
ax.set_xticks([0, 1], ["2020", "2025"])
ax.set_xlim(-0.8, 1.3)
ax.set_ylim(0, 100)                     # mismo rango para el antes y el después
ax.set_yticks([])
ax.set_title("Hogares con internet: antes y después", loc="left")
for lado in ["top", "right", "left"]:
    ax.spines[lado].set_visible(False)
plt.show()
```

</details>

### Distribuciones {#distribuciones}

Sirven para entender cómo se reparten los valores de una variable: dónde se concentran, qué tan dispersos están y si hay valores atípicos. Es un paso previo a cualquier análisis.

#### Histograma {#histograma}

Es un gráfico de barras que muestra cuántas veces aparecen los valores de una variable dentro de cada intervalo. Permite ver si la distribución es simétrica (en forma de campana) o asimétrica (con una cola larga hacia un lado).

**Es más común para:** una variable **cuantitativa continua**, o discreta con muchos valores posibles.

{: .recordar }
Por convención, las barras de un histograma no se separan. La forma cambia según el ancho de los intervalos: pruebe varios antes de sacar conclusiones.

**Ejemplo.** Minutos que tardan 300 estudiantes en llegar a la universidad (datos simulados).

![Histograma: Minutos que tardan 300 estudiantes en llegar a la universidad (datos simulados).]({{ '/assets/img/graficos/05_histograma.png' | relative_url }})

<details markdown="1">
<summary>Ver el código para Colab</summary>

```python
import matplotlib.pyplot as plt
import numpy as np

# Datos simulados: minutos que tardan 300 estudiantes en llegar a la universidad
rng = np.random.default_rng(7)
minutos = rng.gamma(shape=4, scale=10, size=300)

fig, ax = plt.subplots(figsize=(7, 4))
ax.hist(minutos, bins=range(0, 130, 10), color="#2a78d6", edgecolor="white")
ax.axvline(np.median(minutos), color="black", linewidth=1.5)   # línea de la mediana
ax.set_ylim(0, 100)
ax.text(np.median(minutos) + 2, 92, f"Mediana: {np.median(minutos):.0f} min")
ax.set_xlabel("Minutos de desplazamiento")
ax.set_ylabel("Número de estudiantes")
ax.set_title("¿Cuánto tardan los estudiantes en llegar?", loc="left")
ax.spines[["top", "right"]].set_visible(False)
plt.show()
```

</details>

#### Diagrama de caja {#caja}

Resume la distribución en pocos elementos: la línea central es la mediana, los bordes de la caja son el primer y el tercer cuartil, los bigotes marcan el rango habitual y los puntos sueltos son valores atípicos. Es ideal para comparar la distribución de una variable entre varias categorías.

**Es más común para:** una variable **cuantitativa** comparada entre las categorías de una variable **cualitativa**.

{: .recordar }
Exige que el lector conozca la mediana y los cuartiles, así que no es adecuado para todos los públicos sin una breve explicación. Si los nombres de las categorías son largos, póngalo en horizontal.

**Ejemplo.** Minutos de desplazamiento según el medio de transporte (datos simulados).

![Diagrama de caja: Minutos de desplazamiento según el medio de transporte (datos simulados).]({{ '/assets/img/graficos/06_caja.png' | relative_url }})

<details markdown="1">
<summary>Ver el código para Colab</summary>

```python
import matplotlib.pyplot as plt
import numpy as np

# Datos simulados: minutos de desplazamiento según el medio de transporte
rng = np.random.default_rng(3)
medios = ["Bus", "Moto", "Carro", "Bicicleta", "A pie"]
datos = [rng.gamma(6, 9, 80),    # bus
         rng.gamma(8, 3, 80),    # moto
         rng.gamma(6, 5, 80),    # carro
         rng.gamma(9, 3, 40),    # bicicleta
         rng.gamma(5, 3, 40)]    # a pie

fig, ax = plt.subplots(figsize=(7, 4))
ax.boxplot(datos, patch_artist=True,
           boxprops=dict(facecolor="#cfe0f6", color="#2a78d6"),
           medianprops=dict(color="black", linewidth=2))
ax.set_xticks(range(1, len(medios) + 1), medios)
ax.set_ylabel("Minutos de desplazamiento")
ax.set_title("Tiempo de desplazamiento según el medio de transporte", loc="left")
ax.spines[["top", "right"]].set_visible(False)
plt.show()
```

</details>

### Correlaciones {#correlaciones}

Sirven para ver si dos o más variables se mueven juntas. Conviene recordar siempre que la correlación entre dos variables no implica que una sea causa de la otra.

#### Gráfico de dispersión {#dispersion}

Cada elemento es un punto ubicado según su valor en dos variables, una en cada eje. Permite ver si existe relación entre ellas, si es positiva o negativa, si hay grupos de puntos parecidos y si hay casos que se salen del patrón.

**Es más común para:** dos variables **cuantitativas**.

{: .recordar }
Observe la forma (si los puntos siguen una recta hacia arriba o hacia abajo), las agrupaciones y los valores atípicos. Y no confunda correlación con causalidad.

**Ejemplo.** Horas de estudio a la semana y nota final de 40 estudiantes (datos simulados).

![Gráfico de dispersión: Horas de estudio a la semana y nota final de 40 estudiantes (datos simulados).]({{ '/assets/img/graficos/07_dispersion.png' | relative_url }})

<details markdown="1">
<summary>Ver el código para Colab</summary>

```python
import matplotlib.pyplot as plt
import numpy as np

# Datos simulados: horas de estudio a la semana y nota final de 40 estudiantes
rng = np.random.default_rng(11)
horas = rng.uniform(1, 20, 40)
nota = np.clip(2.2 + 0.12 * horas + rng.normal(0, 0.45, 40), 0, 5)

r = np.corrcoef(horas, nota)[0, 1]       # coeficiente de correlación

fig, ax = plt.subplots(figsize=(6, 4.5))
ax.scatter(horas, nota, s=60, color="#2a78d6", edgecolor="white")
ax.set_xlabel("Horas de estudio a la semana")
ax.set_ylabel("Nota final (0 a 5)")
ax.set_title(f"Más horas de estudio, mejores notas (r = {r:.2f})", loc="left")
ax.grid(alpha=0.3)
ax.spines[["top", "right"]].set_visible(False)
plt.show()
```

</details>

#### Gráfico de burbujas {#burbujas}

Es un gráfico de dispersión en el que el tamaño (y a veces el color) de cada punto representa una variable adicional. Permite mostrar tres o cuatro variables a la vez.

**Es más común para:** tres variables **cuantitativas**: dos en los ejes y una en el tamaño de la burbuja.

{: .recordar }
El valor debe ser proporcional al área de la burbuja, no a su diámetro. Use transparencia para que se vean las burbujas que quedan unas sobre otras.

**Ejemplo.** Paraderos, espera promedio y usuarios diarios en ocho barrios (datos ilustrativos).

![Gráfico de burbujas: Paraderos, espera promedio y usuarios diarios en ocho barrios (datos ilustrativos).]({{ '/assets/img/graficos/08_burbujas.png' | relative_url }})

<details markdown="1">
<summary>Ver el código para Colab</summary>

```python
import matplotlib.pyplot as plt

# Datos ilustrativos: paraderos, espera y usuarios en ocho barrios
barrios = ["Barrio A", "Barrio B", "Barrio C", "Barrio D", "Barrio E", "Barrio F", "Barrio G", "Barrio H"]
paraderos = [12, 8, 16, 5, 10, 4, 7, 14]                # eje x
espera = [9, 14, 5, 22, 12, 25, 16, 8]                  # eje y (minutos)
usuarios = [5200, 3100, 7800, 2500, 4300, 1800, 3600, 6900]  # tamaño de la burbuja

fig, ax = plt.subplots(figsize=(7, 4.5))
ax.scatter(paraderos, espera, s=[u / 12 for u in usuarios],
           color="#2a78d6", alpha=0.5, edgecolor="#2a78d6")
for b, x, y in zip(barrios, paraderos, espera):
    ax.text(x, y, b, ha="center", va="center", fontsize=8)
ax.set_xlabel("Número de paraderos")
ax.set_ylabel("Espera promedio (minutos)")
ax.set_title("Menos paraderos, más espera (tamaño = usuarios diarios)", loc="left")
ax.set_xlim(0, 18); ax.set_ylim(0, 30)
ax.grid(alpha=0.3)
ax.spines[["top", "right"]].set_visible(False)
plt.show()
```

</details>

### Mapas {#mapas}

Sirven para encontrar patrones geográficos en los datos. Se deben usar para responder preguntas de tipo geográfico, no para mostrar un ranking.

#### Mapa de coropletas {#coropletas}

Pinta cada región (departamento, municipio, barrio) con un color cuya intensidad representa el valor de una variable. Cuanto más oscuro, mayor el valor.

**Es más común para:** una variable **cuantitativa** (preferiblemente una tasa o un porcentaje) o **cualitativa** asociada a regiones.

{: .recordar }
Use tasas o porcentajes, no totales: un mapa de totales solo muestra dónde vive más gente. Si lo que interesa es el ranking de regiones, es mejor un gráfico de barras.

**Ejemplo.** Cobertura de internet por departamento (valores simulados al azar, solo para practicar).

![Mapa de coropletas: Cobertura de internet por departamento (valores simulados al azar, solo para practicar).]({{ '/assets/img/graficos/09_coropletas.png' | relative_url }})

<details markdown="1">
<summary>Ver el código para Colab</summary>

```python
import geopandas as gpd
import matplotlib.pyplot as plt
import numpy as np

# Mapa de departamentos de Colombia (archivo del repositorio del módulo)
url = "https://raw.githubusercontent.com/nescolar/periodismo-de-precision/main/assets/datos/colombia_departamentos.geojson"
mapa = gpd.read_file(url)

# Valores SIMULADOS solo para practicar: cobertura de internet (%)
rng = np.random.default_rng(5)
mapa["cobertura"] = rng.integers(20, 90, len(mapa))

fig, ax = plt.subplots(figsize=(6, 7))
mapa.plot(column="cobertura", cmap="Blues", edgecolor="white", linewidth=0.5,
          legend=True, legend_kwds={"label": "Hogares con internet (%)", "shrink": 0.6}, ax=ax)
ax.set_title("Cobertura de internet por departamento (datos simulados)", loc="left")
ax.axis("off")
plt.show()
```

</details>

#### Mapa de símbolos proporcionales {#simbolos}

Ubica un círculo sobre cada lugar, con un tamaño proporcional al valor de la variable. A diferencia de las coropletas, no necesita áreas: basta con la latitud y la longitud de cada punto.

**Es más común para:** una variable **cuantitativa** asociada a **puntos geográficos** (latitud y longitud).

{: .recordar }
Use transparencia, porque los círculos suelen superponerse. Igual que las coropletas, sirve para ver patrones geográficos, no para ordenar lugares.

**Ejemplo.** Medios de comunicación locales por ciudad (datos ilustrativos).

![Mapa de símbolos proporcionales: Medios de comunicación locales por ciudad (datos ilustrativos).]({{ '/assets/img/graficos/10_simbolos.png' | relative_url }})

<details markdown="1">
<summary>Ver el código para Colab</summary>

```python
import geopandas as gpd
import matplotlib.pyplot as plt

# Mapa base de Colombia
url = "https://raw.githubusercontent.com/nescolar/periodismo-de-precision/main/assets/datos/colombia_departamentos.geojson"
mapa = gpd.read_file(url)

# Datos ilustrativos: medios de comunicación locales por ciudad (latitud y longitud aproximadas)
ciudades = ["Bogotá", "Medellín", "Cali", "Barranquilla", "Cartagena", "Bucaramanga", "Cúcuta", "Pereira", "Santa Marta", "Pasto"]
lat = [4.71, 6.24, 3.45, 10.96, 10.39, 7.12, 7.89, 4.81, 11.24, 1.21]
lon = [-74.07, -75.58, -76.53, -74.80, -75.48, -73.12, -72.51, -75.69, -74.20, -77.28]
medios = [120, 75, 60, 45, 30, 28, 22, 18, 15, 14]

fig, ax = plt.subplots(figsize=(6, 7))
mapa.plot(color="#e9e8e4", edgecolor="white", linewidth=0.5, ax=ax)
ax.scatter(lon, lat, s=[m * 8 for m in medios], color="#eb6834",
           alpha=0.6, edgecolor="white")          # transparencia para ver superposiciones
for c, x, y in zip(ciudades, lon, lat):
    ax.text(x + 0.4, y, c, fontsize=8, va="center")
ax.set_title("Medios de comunicación locales por ciudad (ilustrativo)", loc="left")
ax.axis("off")
plt.show()
```

</details>

Mapas: elaboración propia a partir del mapa de departamentos de Castañeda (2023), basado en el Marco Geoestadístico Nacional del DANE (licencia MIT). Para facilitar la lectura, el archipiélago de San Andrés, Providencia y Santa Catalina aparece desplazado hacia la costa.
{: .fs-2 }

---

## Ejercicio práctico 2: clima y violencia en Barranquilla {#ejercicio-2}

### Contexto {#ejercicio-2-contexto}

"Con este calor, la gente anda de mal genio." En una ciudad como Barranquilla, la frase se oye a menudo, y algunas notas de prensa sugieren que los días más calientes son también los más violentos. Antes de repetirlo, un periodista de precisión se pregunta qué dicen los datos.

Para comprobarlo vamos a usar una base publicada por Juan C. Trujillo y Peter Howley en Mendeley Data: *Dataset for weather and crime in Barranquilla, Colombia*. Tiene **2.557 días seguidos**, del 1 de enero de 2010 al 31 de diciembre de 2016, sin valores faltantes. Cada fila es **un día** en Barranquilla, con el número de casos de violencia y de homicidios, el clima de ese día, la fase de la luna y otras variables del calendario y de la ciudad.

{: .recordar }
> A diferencia del ejercicio 1, estos datos son **reales**. Los autores los reunieron de cinco fuentes oficiales: Medicina Legal (violencia y homicidios), el IDEAM (clima), la Organización de Aviación Civil Internacional (luna), el calendario oficial de Colombia (festivos y fines de semana) y la Secretaría Distrital de Movilidad (comparendos y matrículas). La base tiene licencia CC BY 4.0: se puede usar citando la fuente. Los datos llegan hasta 2016, así que no describen la situación actual de la ciudad.

Estas son las variables principales:

| Variable | Qué mide | Tipo |
|:--|:--|:--|
| fecha, dia_semana, mes, anio | Cuándo ocurrió el registro | Tiempo |
| tipo_dia | Entre semana, Fin de semana o Festivo | Cualitativa nominal |
| festivo, fin_de_semana | 1 si el día es festivo (o fin de semana), 0 si no | Cualitativa dicotómica codificada |
| violencia_interpersonal | Casos de violencia no letal en el día. El 86 % son riñas | Cuantitativa discreta |
| homicidios | Homicidios en el día | Cuantitativa discreta |
| temp_max | Temperatura máxima (°C) | Cuantitativa continua |
| indice_calor | Sensación de calor, combinando temperatura y humedad (°C) | Cuantitativa continua |
| humedad | Humedad relativa promedio (%) | Cuantitativa continua |
| lluvia | Precipitación total (mm) | Cuantitativa continua |
| viento | Velocidad promedio del viento | Cuantitativa continua |
| luna_iluminada | Proporción de la Luna iluminada (0 = luna nueva, 1 = luna llena) | Cuantitativa continua |
| comparendos_embriaguez | Comparendos por conducir embriagado. Los autores la usan como aproximación al consumo de alcohol | Cuantitativa discreta |
| matriculas_vehiculos | Matrículas de vehículos particulares. Los autores la usan como aproximación a la economía | Cuantitativa discreta |

### ¿Qué vamos a hacer? {#ejercicio-2-tareas}

En el ejercicio 1 practicamos la exploración variable por variable. Ahora nos concentramos en las **relaciones entre variables**: la [correlación](#correlacion), los diagramas de dispersión y las comparaciones entre grupos. La pregunta que guía el ejercicio es:

> ¿En Barranquilla hay más violencia los días más calientes?

Todo el ejercicio se hace en **Google Colab**. El cuaderno lee la base directamente desde este sitio, así que no necesita descargar nada ni instalar programas. Ejecute las celdas en orden, de arriba hacia abajo, y responda las preguntas *Para comentar* que aparecen después de cada resultado.

[Abrir el ejercicio 2 en Google Colab](https://colab.research.google.com/github/nescolar/periodismo-de-precision/blob/main/notebooks/clima_violencia_barranquilla.ipynb){: .btn .btn-primary }

El cuaderno tiene cuatro partes. Después de trabajar cada una, compare sus respuestas con las de abajo.

#### Parte 1. Variable por variable

Un repaso rápido de cada variable, con las mismas herramientas del ejercicio 1: frecuencias, medidas resumen, histograma, diagrama de caja y valores atípicos. Además, los diez días más violentos y la serie de tiempo mensual.

<details markdown="1">
<summary>Ver respuesta</summary>

- **Violencia interpersonal:** en un día típico hay unos 10 casos (media 9,96, mediana 9). La distribución tiene una cola a la derecha (asimetría 1,68). Con la regla de 1,5 × RIC, todo día con más de 21 casos es atípico: hay 107.
- **Homicidios:** 1 por día en promedio. El valor más frecuente es 0 (1.021 días).
- **Temperatura máxima:** casi simétrica, con media de 33,25 °C y una desviación estándar de solo 1,67 °C. En Barranquilla, el calor varía poco de un día a otro.
- **Lluvia:** la mediana es 0 porque el 82 % de los días no llueve. Es muy asimétrica (5,78); para reportarla conviene decir en cuántos días llovió o usar promedios mensuales.
- **Viento:** el máximo es 81, cuando el 75 % de los días está por debajo de 15,9. Antes de publicar, habría que verificar ese dato con el IDEAM.
- **Luna:** hay más días en los extremos (cerca de 0 y de 1) porque la luna cambia rápido en cuarto creciente y menguante, y despacio cerca de la luna llena y la nueva.
- **Comparendos:** la media (4,32) es mucho mayor que la mediana (1): la mayoría de los días hay pocos, y unos pocos días (fines de semana) hay muchos.
- **Matrículas:** hay 552 días sin matrículas; 363 son domingos.
- **Los días más violentos** son festivos: el 8 de diciembre de 2010 (52 casos), el 25 de diciembre de 2011 (48), el 8 de diciembre de 2013 (44), el 1 de enero de 2011 (41) y el 8 de diciembre de 2015 (39). El 8 de diciembre es el Día de las Velitas. No fueron días especialmente calientes. Un valor atípico no es un error: a veces es la noticia.
- **En el tiempo,** el promedio diario sube de 8,4 casos en 2010 a 10,7 en 2015 y 2016.

</details>

#### Parte 2. Correlaciones

La matriz de correlaciones, las correlaciones más fuertes, la pregunta guía con diagramas de dispersión y la comparación entre Pearson y Spearman.

<details markdown="1">
<summary>Ver respuesta</summary>

**Las correlaciones más fuertes:**

| Variable 1 | Variable 2 | r |
|:--|:--|:--:|
| fin_de_semana | comparendos_embriaguez | 0,70 |
| temp_max | indice_calor | 0,68 |
| humedad | viento | −0,60 |
| fin_de_semana | matriculas_vehiculos | −0,52 |
| comparendos_embriaguez | matriculas_vehiculos | −0,43 |

Algunas son obvias: el índice de calor se calcula con la temperatura, así que es lógico que se parezcan.

**Con qué se relaciona la violencia:** con el fin de semana (0,38), los comparendos por embriaguez (0,37), las matrículas (−0,32), los homicidios (0,23) y los festivos (0,20). Con el clima y con la luna, ninguna correlación supera |0,08|.

**La pregunta guía:** temperatura máxima y violencia, r = 0,04; índice de calor y violencia, r = 0,04; temperatura y homicidios, r = 0,00. Las tres son prácticamente nulas. Entre 30 °C y 36 °C, que son casi todos los días, el promedio se mantiene cerca de 10 casos. Las barras de 28 °C y 39 °C cambian más, pero se calcularon con 9 días y con 1 día: no son confiables.

**Pearson y Spearman** dan resultados parecidos. Las mayores diferencias están en los festivos (0,20 frente a 0,12) y los homicidios (0,23 frente a 0,16), porque los pocos días muy atípicos pesan más en Pearson. Ninguna conclusión cambia de sentido.

</details>

#### Parte 3. ¿Una tercera variable?

La violencia se correlaciona **positivamente** con los comparendos por embriaguez y **negativamente** con las matrículas de vehículos. ¿Comprar carro calma a la gente? El cuaderno compara las tres variables por día de la semana y calcula las correlaciones dentro de cada tipo de día.

<details markdown="1">
<summary>Ver respuesta</summary>

| tipo_dia | Violencia | Comparendos | Matrículas |
|:--|:--:|:--:|:--:|
| Entre semana | 8,3 | 0,9 | 32,8 |
| Fin de semana | 13,1 | 11,8 | 7,8 |
| Festivo | 14,4 | 9,1 | 6,5 |

- Los domingos la violencia sube a 16,4 casos (entre martes y viernes ronda 8,4), los comparendos llegan a 11,4 y las matrículas caen a 0,2: la oficina casi no matricula ese día.
- El calendario es la **tercera variable**: mueve a las tres al mismo tiempo. Los fines de semana y festivos hay más reuniones, más alcohol y más riñas; también hay más operativos de alcoholemia y las oficinas de matrícula están cerradas.
- Solo con los días entre semana, la correlación entre comparendos y violencia baja de 0,37 a 0,12, y la de matrículas y violencia, de −0,32 a −0,03. Buena parte de esas relaciones venía del calendario.
- Dentro del fin de semana, las matrículas siguen en −0,28 por la misma razón, a menor escala: el sábado se matricula y el domingo no, y el domingo hay más violencia.
- Las matrículas no "calman" a nadie. Es un buen ejemplo de que **correlación no es causalidad**.

</details>

#### Parte 4. La escala importa: de días a meses

El cuaderno promedia la violencia y la lluvia por mes (84 meses) y compara la correlación con la que se obtiene día por día.

<details markdown="1">
<summary>Ver respuesta</summary>

- Por día, lluvia y violencia tienen r = −0,07. Por mes, r = −0,26: una relación negativa débil, pero más clara. La temperatura, en cambio, sigue casi en cero (0,09 por mes).
- Como el 82 % de los días no llueve, la variable diaria es casi siempre cero. Al promediar por mes se reduce el ruido del día a día y aparece un patrón: los meses más lluviosos tienden a ser un poco menos violentos.
- La lección: la correlación depende de la escala a la que se mide. Cuando una nota cite una correlación, conviene preguntar si es por día, por mes o por año.

</details>

#### Conclusiones

Al final del cuaderno hay un espacio para escribir la respuesta a la pregunta guía, tres hallazgos, un ejemplo de tercera variable, un titular honesto y una limitación del análisis.

<details markdown="1">
<summary>Ver respuesta</summary>

1. **No**: la correlación entre temperatura máxima y violencia es 0,04, prácticamente nula.
2. La violencia se concentra en domingos y festivos, sobre todo en fechas como el Día de las Velitas, Navidad y Año Nuevo. Los comparendos por embriaguez se mueven con la violencia, pero buena parte de esa relación viene del calendario. El clima y la luna casi no se relacionan con la violencia; la lluvia muestra una relación débil cuando se mira por meses.
3. Las matrículas parecen "reducir" la violencia, pero es el calendario: los domingos no se matricula y hay más riñas.
4. Por ejemplo: "No es el calor: en Barranquilla, la violencia sube los domingos y festivos", con un gráfico de barras del promedio de casos por día de la semana.
5. Los datos llegan hasta 2016. Además, los comparendos y las matrículas dependen de cuándo trabajan las instituciones, no solo del consumo de alcohol o de la economía.

</details>

---

## Ejercicio práctico 3: del mapa a la noticia {#ejercicio-3}

### Contexto {#ejercicio-3-contexto}

La violencia intrafamiliar es uno de los delitos que más se denuncian en Colombia. Cada año, las cifras de la Policía aparecen en titulares como "Antioquia, uno de los departamentos con más casos" o "Bogotá encabeza la lista". Pero ¿qué tan justa es esa comparación entre departamentos con poblaciones tan distintas?

En este ejercicio vamos a hacer un **mapa** con esas cifras y luego a **escribir una noticia** a partir de él. Usaremos dos fuentes oficiales:

- **Policía Nacional de Colombia.** *Reporte Delito Violencia Intrafamiliar*, publicado como datos abiertos. Cada registro dice dónde y cuándo ocurrió el hecho, con qué arma o medio, y el género y grupo de edad de la víctima.
- **DANE.** *Proyecciones de población departamental por área, 2018-2050* (actualizadas el 30 de julio de 2025). De aquí sale la población de cada departamento, que necesitamos para calcular tasas.

[Descargar la base en Excel]({{ '/assets/datos/Violencia_intrafamiliar_Colombia_2018_2021.xlsx' | relative_url }}){: .btn .btn-primary }

El archivo tiene cinco hojas: **Leeme** (fuentes, depuración y advertencias), **Datos** (cada registro depurado, de enero de 2018 a mayo de 2021), **Mapa_departamentos** (una fila por departamento, lista para el mapa), **Municipios** y **Serie_mensual** (casos por mes en todo el país).

### Cómo se prepararon los datos {#ejercicio-3-datos}

Antes de hacer un mapa hay que **depurar** los datos. Estas fueron las decisiones que tomamos con la base original de la Policía:

- **Bogotá venía dentro de Cundinamarca.** La separamos como Bogotá, D.C., porque es una entidad territorial propia y los mapas de Colombia la dibujan aparte.
- **Códigos.** El código DANE del departamento quedó con 2 dígitos y el del municipio con 5, como texto, para no perder el cero inicial (05 = Antioquia). Agregamos el código ISO de cada departamento (CO-ATL), que usan las herramientas de mapas.
- **Categorías.** Unificamos categorías equivalentes. Por ejemplo, "cortopunzantes", "cortantes" y "punzantes" pasan a "Arma blanca / cortopunzante", y todas las variantes de "no reporta" pasan a "No reportado".
- **Fechas.** Ocho fechas venían como números de serie de Excel (44335); las convertimos a fecha.
- **Periodo.** El archivo original va de 2010 a mayo de 2021. Dejamos 2018 a 2021 porque esos años tienen proyecciones de población del DANE con la misma metodología.

### Las columnas de la hoja Mapa_departamentos {#ejercicio-3-columnas}

Cada fila es un departamento. El ejemplo es Antioquia:

| Columna | Qué significa | Antioquia |
|:--|:--|:--|
| `cod_dep` | Código DANE del departamento, de 2 dígitos. | 05 |
| `iso` | Código internacional del departamento (ISO 3166-2). Datawrapper lo usa para ubicar cada departamento en el mapa. | CO-ANT |
| `departamento` | Nombre oficial. | Antioquia |
| `casos_2018`, `casos_2019`, `casos_2020` | Casos de violencia intrafamiliar registrados por la Policía en cada año. | 13.485, 16.889, 15.559 |
| `casos_2021_ene_may` | Casos de enero a mayo de 2021. El año está incompleto: no se compara con los anteriores. | 6.290 |
| `casos_2018_2020` | Suma de los casos de 2018, 2019 y 2020. | 45.933 |
| `poblacion_2018` a `poblacion_2021` | Habitantes del departamento en cada año, según el DANE. | 6.642.072 en 2020 |
| `tasa_2018`, `tasa_2019`, `tasa_2020` | Casos por cada 100.000 habitantes en ese año. | 210,5; 259,1; 234,2 |
| `tasa_promedio_2018_2020` | Tasa anual promedio de los tres años. **Es la que usamos en el mapa.** | 234,7 |
| `pct_victimas_mujeres_2018_2020` | Porcentaje de víctimas mujeres sobre el total de casos de 2018 a 2020. | 80,4 % |
| `pct_victimas_menores_adolesc_2018_2020` | Porcentaje de víctimas que la Policía clasificó como "Menores" o "Adolescentes". | 7,5 % |

**Los cálculos.** La tasa de un año es:

> tasa = casos del año ÷ población del año × 100.000

Por ejemplo, en Antioquia en 2020: 15.559 ÷ 6.642.072 × 100.000 = 234,2 casos por cada 100.000 habitantes.

La tasa promedio suma los casos de los tres años y los divide por la suma de la población de los tres años:

> tasa promedio = casos 2018-2020 ÷ (población 2018 + población 2019 + población 2020) × 100.000

No calculamos tasa para 2021, porque con solo cinco meses saldría artificialmente baja. Los porcentajes, en cambio, no necesitan la población: se calculan dentro de los casos de cada departamento.

{: .recordar }
> **¿Por qué tasa y no casos?** Bogotá y Antioquia siempre tendrán más casos porque tienen más habitantes. Un mapa de casos solo muestra dónde vive más gente. Al dividir por la población, comparamos departamentos de tamaños distintos en igualdad de condiciones. Repase la sección [Volumen frente a tasa](#volumen-tasa).

### ¿Qué vamos a hacer? {#ejercicio-3-tareas}

> ¿Dónde se registra más violencia intrafamiliar en Colombia cuando se tiene en cuenta el tamaño de la población?

#### Paso 1. Hacer el mapa en Datawrapper

1. Entre a [Datawrapper](https://www.datawrapper.de) y cree una cuenta gratuita.
2. Elija **New Map > Choropleth map** y busque el mapa de **Colombia por departamentos**.
3. En la hoja **Mapa_departamentos** del Excel, copie la tabla completa y péguela en Datawrapper. Empareje los datos por la columna `iso` (o por `departamento`).
4. Elija `tasa_promedio_2018_2020` como valor que colorea el mapa. Use una escala de un solo color, del claro (tasa baja) al oscuro (tasa alta).
5. En **Annotate**, complete los textos del mapa:

| Campo | Qué escribir |
|:--|:--|
| **Title** | Violencia intrafamiliar: casos por cada 100.000 habitantes, 2018-2020 |
| **Description** | Tasa anual promedio de casos registrados por la Policía Nacional en cada departamento. Bogotá registra la tasa más alta; Vichada, La Guajira y Chocó, las más bajas. |
| **Notes** | Tasa = casos registrados ÷ población × 100.000 (promedio de 2018 a 2020). Son casos denunciados o reportados a la Policía, no todos los hechos ocurridos: una tasa baja puede reflejar menos denuncia. Bogotá aparece separada de Cundinamarca. |
| **Data source** | Policía Nacional (datos abiertos); DANE, proyecciones de población |
| **Link to data source** | El enlace a la página de datos abiertos de la Policía desde donde se descargó la base |
| **Byline** | Su nombre |
| **Alternative description** | Mapa de Colombia por departamentos coloreado según la tasa de violencia intrafamiliar por cada 100.000 habitantes entre 2018 y 2020. Bogotá tiene la tasa más alta (468), seguida de Boyacá (299) y Meta (265). Las más bajas son las de Vichada (46), La Guajira (49) y Chocó (50). |

6. Haga una segunda versión del mapa con `casos_2018_2020` y compárelas. ¿Qué departamentos cambian más de posición?

<details markdown="1">
<summary>Ver respuesta</summary>

- Con la tasa, los primeros lugares son Bogotá (468 por 100.000), Boyacá (299), Meta (265), Cundinamarca (239), Santander (236) y Antioquia (235).
- Con los casos, Antioquia es segunda (45.933) y Valle del Cauca, tercero (25.360). Con la tasa, Antioquia baja al sexto lugar y Valle del Cauca al duodécimo (186).
- Boyacá y Meta, que no destacan por número de casos, suben al segundo y tercer lugar con la tasa.
- Atlántico tiene 8.561 casos y una tasa de 109 por 100.000: está en el puesto 27 de 33.

</details>

##### Así queda el mapa

Después de hacer su versión, compárela con este mapa. Pase el cursor por cada departamento para ver su tasa.

<div markdown="0" class="mapa-datawrapper">
<iframe title="Violencia intrafamiliar: casos por cada 100.000 habitantes, 2018-2020" aria-label="Choropleth map" id="datawrapper-chart-tGNQL" src="https://datawrapper.dwcdn.net/tGNQL/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="825" data-external="1"></iframe><script type="text/javascript">(function(){function e(){window.addEventListener(`message`,function(e){if(e.data[`datawrapper-height`]!==void 0){var t=document.querySelectorAll(`iframe`);for(var n in e.data[`datawrapper-height`])for(var r=0,i;i=t[r];r++)if(i.contentWindow===e.source){var a=e.data[`datawrapper-height`][n]+`px`;i.style.height=a}}})}e()})();</script>
</div>

#### Paso 2. Escribir la noticia

Con el mapa y la tabla, escriba una **noticia breve de 300 a 400 palabras**. Debe tener:

1. **Titular:** una frase que diga el hallazgo principal, sin exagerar.
2. **Entrada (primer párrafo):** qué, dónde, cuándo y según quién, en dos o tres líneas.
3. **Cuerpo:** las cifras que sostienen el hallazgo (tasas, comparaciones, porcentajes), de la más importante a la menos importante.
4. **Contexto y límites:** qué no dicen los datos.
5. **Fuentes:** quién publicó los datos y cómo se calcularon las tasas.
6. **El mapa**, con su título, nota y fuente.

**Antes de entregarla, revise que la noticia cumpla estas precisiones:**

- **Casos registrados, no hechos ocurridos.** Las cifras son denuncias o reportes a la Policía. Escriba "se registraron" o "se denunciaron", no "ocurrieron". Muchos casos de violencia intrafamiliar nunca se denuncian.
- **Una tasa baja no prueba que haya menos violencia.** Puede haber menos denuncia, menos presencia de la Policía o más dificultad para acceder a ella. Esto pesa en departamentos como Vichada, La Guajira o Chocó.
- **Compare con tasas, no con casos.** Si menciona casos, acompáñelos de la tasa. "Antioquia tiene 45.933 casos" no dice si es mucho o poco para su población.
- **Diga qué tasa usa:** "casos por cada 100.000 habitantes, promedio anual de 2018 a 2020".
- **No compare 2021 con los años anteriores.** Solo tiene datos de enero a mayo.
- **Tenga en cuenta la pandemia.** 2020 incluye el confinamiento por la COVID-19, que pudo cambiar tanto la violencia como la posibilidad de denunciarla.
- **Correlación no es causalidad.** El mapa muestra dónde se registran más casos, no por qué. No atribuya las diferencias a una causa que los datos no miden.
- **Cite las dos fuentes:** Policía Nacional (casos) y DANE (población).
- **Respete las categorías de la fuente.** "Menores" y "Adolescentes" son grupos definidos por la Policía; use esos nombres.
- **Redondee para el lector.** "Casi 8 de cada 10 víctimas son mujeres" se entiende mejor que "78,5 %". Pero no cambie el sentido del dato.
- **Cuide el lenguaje.** Hable de "víctimas" y de "casos"; evite adjetivos que dramaticen o que culpen a la víctima.

<details markdown="1">
<summary>Ver un ejemplo de noticia</summary>

**Bogotá, Boyacá y Meta registran las tasas más altas de violencia intrafamiliar del país**

*Entre 2018 y 2020, la Policía registró en promedio 223 casos de violencia intrafamiliar por cada 100.000 habitantes en Colombia. Bogotá duplicó ese promedio.*

Bogotá es el territorio del país donde más casos de violencia intrafamiliar se registran en proporción a su población. Entre 2018 y 2020, la Policía Nacional recibió en la capital un promedio de 468 casos por cada 100.000 habitantes al año, más del doble del promedio nacional (223). Le siguen Boyacá (299), Meta (265), Cundinamarca (239) y Santander (236).

Las cifras cambian el orden que suele aparecer en los titulares. Por número de casos, Antioquia ocupa el segundo lugar, con 45.933 en tres años, pero al tener en cuenta su población baja al sexto (235 por 100.000). Boyacá, en cambio, tiene menos de la cuarta parte de los casos de Antioquia, pero su tasa es mayor.

En el otro extremo están Vichada (46 por 100.000), La Guajira (49) y Chocó (50). Atlántico, con 109, ocupa el puesto 27 entre 33 departamentos.

En todo el país, casi 8 de cada 10 víctimas fueron mujeres, y alrededor de 1 de cada 10 fue clasificada por la Policía como menor de edad o adolescente.

Estas cifras corresponden a casos denunciados o reportados a la Policía, no a todos los hechos ocurridos. Una tasa baja puede reflejar menos violencia, pero también menos denuncia o menos presencia institucional. Además, 2020 incluye los meses de confinamiento por la pandemia, que pudieron afectar tanto la violencia en los hogares como la posibilidad de denunciarla.

*Fuentes: Policía Nacional de Colombia, Reporte Delito Violencia Intrafamiliar (datos abiertos); DANE, proyecciones de población departamental 2018-2050. La tasa se calculó dividiendo los casos registrados entre la población de cada año y multiplicando por 100.000.*

</details>

#### Paso 3. Revisar entre pares

Intercambie su noticia con un compañero. Cada uno revisa la del otro con la lista de precisiones y marca:

1. Una cifra que no esté bien explicada o que no tenga fuente.
2. Una frase que afirme más de lo que muestran los datos.
3. Una pregunta que la noticia deja abierta y que valdría la pena investigar, por ejemplo hablando con una fuente en el departamento.

---

## Producto final del módulo {#producto-final}

El producto final del módulo es una **nota periodística publicada en la web**, sostenida en datos. Así debe verse:

[Ver la nota de ejemplo]({{ '/nota/' | relative_url }}){: .btn .btn-primary }

La nota de ejemplo usa los resultados reales, agregados y anónimos, de la evaluación de un programa de liderazgo para estudiantes de colegios públicos de Barranquilla. Fíjese en sus partes:

1. **Sección, titular y bajada.** El titular dice el hallazgo principal sin exagerar; la bajada lo amplía con la cifra clave.
2. **Autor y fecha.**
3. **Entrada.** Responde qué, quién, cuándo y dónde en el primer párrafo.
4. **Cifras destacadas.** Tres números que el lector debe recordar.
5. **Cuerpo con subtítulos.** Cada sección desarrolla un hallazgo, del más importante al menos importante, incluidos los que no salieron como se esperaba.
6. **Gráficos.** Cada uno con título que dice el hallazgo, subtítulo que dice qué se mide, nota con la fuente y el tamaño de la muestra, y enlace para descargar los datos. Puede hacerlos en Datawrapper e insertarlos con el código que da la herramienta.
7. **Una voz.** Una cita que da contexto humano a los números.
8. **"Cómo hicimos esta nota".** Un recuadro con los datos, los cálculos, los límites del análisis y las decisiones de anonimización. Es lo que distingue al periodismo de precisión: cualquier lector puede revisar cómo se llegó a cada cifra.

{: .recordar }
> Cuando los datos son sobre personas, y sobre todo sobre menores de edad, publique solo resultados agregados, no nombre a nadie que pueda ser identificado y no use fotografías sin autorización.

---

## Referencias {#referencias}

Bradshaw, P. (2012). *The inverted pyramid of data journalism*. Online Journalism Blog.

Castañeda, J. A. (2023). *colombian_map: TopoJSON of Colombia's departments and towns* [Repositorio de GitHub]. https://github.com/jacasta2/colombian_map

Dader, J. L. (1997). *Periodismo de precisión: la vía socioinformática de descubrir noticias*. Madrid: Síntesis.

DANE. (2025). *Proyecciones de población departamental por área, 2018-2050* (actualización del 30 de julio de 2025). Departamento Administrativo Nacional de Estadística. https://www.dane.gov.co/index.php/estadisticas-por-tema/demografia-y-poblacion/proyecciones-de-poblacion

Generalitat de Catalunya. (2019). *Guía de visualización de datos*. Barcelona: Generalitat de Catalunya. Licencia CC BY 4.0.

Lambeth, E. B. (1992). *Periodismo comprometido: un código de ética para la profesión*. México: Limusa.

López, P. J. (2016). Antecedentes y fundamentos del periodismo de datos. En *Periodismo de datos. Nuevas narrativas para el periodismo especializado* (pp. 5-26). Madrid: Universidad Complutense de Madrid.

Meyer, P. (2002). *Precision journalism: A reporter's introduction to social science methods* (4.ª ed.). Lanham: Rowman & Littlefield.

Policía Nacional de Colombia. (s. f.). *Reporte Delito Violencia Intrafamiliar* [Conjunto de datos]. Datos abiertos. Consultado en noviembre de 2026.

Protess, D. L., Cook, F. L., Doppelt, J. C., Ettema, J. S., Gordon, M. T., Leff, D. R. y Miller, P. (1991). *The journalism of outrage: Investigative reporting and agenda building in America*. Nueva York: Guilford Press.

*Social Media vs Productivity: Realistic Behavioral Dataset (30,000 Users)* [Conjunto de datos simulado]. (s. f.). Kaggle. Consultado en noviembre de 2026.

Salón Acosta, E. P. (s. f.). *Herramientas estadísticas para el mejoramiento continuo* [Material de clase]. Departamento de Matemáticas, Física y Ciencia de Datos, Universidad del Norte.

Trujillo, J. C. y Howley, P. (2018). *Dataset for weather and crime in Barranquilla, Colombia* (versión 1) [Conjunto de datos]. Mendeley Data. https://doi.org/10.17632/836wyfy5rn.1
