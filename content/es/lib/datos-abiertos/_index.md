---
# Title, summary, and page position.
linktitle: Gestión de datos abiertos
summary: ""
weight: 11
icon: database
icon_pack: fas

# Page metadata.
title: Gestión de datos abiertos
date: "2021-04-30T00:00:00Z"
type: book # Do not modify.

translationKey: datuak
---

En España los datos relacionados con la epidemia de COVID-19, tanto los asistenciales como los epidemiológicos, son gestionados por cada comunidad o ciudad autónoma y enviados al Ministerio de Sanidad, que los publica de forma centralizada a través del Instituto de Salud Carlos III. Los datos se obtienen caso por caso a partir de la declaración de éstos a la Red Nacional de Vigilancia Epidemiológica (RENAVE) a través de la plataforma informática vía Web SiViES (Sistema de Vigilancia de España) que gestiona el Centro Nacional de Epidemiología (CNE)[^1].

Cada comunidad autónoma decide qué datos en abierto publicar y cómo[^2]. Dependiendo del tratamiento de los datos, los números resultantes pueden ser diferentes dependiendo de si se consultan las bases de datos estatales o autonómicas. Cuando hay diversas fuentes para un dato y no coinciden, no hay forma de saber cuál es el más cercano a la realidad.

Durante la pandemia, la CAV ha realizado, como otras comunidades autónomas y países, cambios a la hora de publicar y mantener los datos en abierto que no han tenido en cuenta las dificultades que se introducían para el seguimiento de la evolución de la pandemia. Algunas variables se publican sueltas en notas de prensa, sin ofrecerse la serie histórica de los datos ni posibilidad de descarga. Otras series de datos dejaron de publicarse, como los fallecidos por provincias[^3] o los datos asistenciales por hospitales.

Una serie de datos que no se publica o que requiere de mucha elaboración para ser analizada es menos susceptible de ser utilizada y, por tanto, de ser publicada por los medios de comunicación y atraer la atención del público. De forma deliberada o no, el acceso a los datos ha sido problemático y ha puesto de manifiesto las limitaciones de las formas en las que han sido publicados y la falta de voluntad para hacerlo en abierto.

En Open Data Euskadi, la plataforma de datos abiertos de la CAV, están disponibles para su descarga varias series de datos[^4], que se actualizan únicamente en días laborables. En ocasiones, esta información se actualiza semanalmente y se dan únicamente datos acumulados, requiriendo para su uso la reconstrucción de la serie completa descargando, agrupando y comparando todos los archivos. Sin embargo, esta tarea no siempre es posible porque pueden no estar disponibles todos los archivos. A veces, algunas variables en uno de los formatos ofrecidos (`.csv`) eran diferentes que las descargables en hoja de cálculo (`.xlsx`), dificultando su comparación. Los archivos disponibles para ser procesados mezclan datos con explicaciones, incumpliendo los estándares a la hora de publicar datos abiertos (como se indican por ejemplo en [_Open Standards for Data_](https://standards.theodi.org/). Además, muchas variables no están claramente definidas. Tampoco existe dirección web (URL) para cada una de las series de datos, sino que se encuentran en hojas de cálculo multipestaña o en archivos `.csv` contenidos en `.zip`. Varias veces las hojas de cálculo contienen errores fruto, probablemente, de un procesado de datos manual. 

En [Irekia](https://www.irekia.euskadi.eus/), la plataforma web del Gobierno Vasco, se ofrece información en notas de prensa o en boletines en formato PDF de la situación epidemiológica de la Viceconsejería de Salud, Esta información recoge información diaria en días laborables y resúmenes semanales. Algunas series de datos contenidas en los boletines o notas de prensa no se publican como datos abiertos (p. ej., las relativas a los motivos de realización de test diagnóstico o el número de aulas escolares cerradas).
Desde la ciudadanía se han planteado preguntas sobre algunas variables y sobre la publicación de datos adicionales, todavía sin respuesta. Se ha contestado puntualmente a alguna pregunta en Irekia y a algunas cuestiones por la cuenta de Twitter de @opendataeuskadi. En cualquier caso, puede decirse que, en general, la Administración no ha respondido a las peticiones de apertura de datos[^5].

## Propuestas

Algunas de las siguientes propuestas están inspiradas en el manifiesto _Todavía es posible_[^6].
- Publicar datos actualizados. Para tomar medidas epidemiológicas, decisiones políticas y comunicar claramente a la población en qué se basan, es necesario contar con información actualizada fiable. La publicación debería ser, en la medida de lo posible, lo más próxima en el tiempo respecto a su obtención y tratamiento en origen.
- Habilitar repositorios que permitan la accesibilidad a datos organizados de forma estructurada, abierta, vinculada y contextualizada, en la línea de iniciativas gubernamentales ya existentes como https://red.es/redes/ o https://datos.gob.es/. Deben incluir metadatos que describan tanto los campos utilizados como la forma en la que se ha obtenido cada uno de ellos, incluido el nivel de incertidumbre que pueda existir en torno a la definición del campo en sí, como al procedimiento de recogida y el valor obtenido. Este repositorio debería disponer no solamente los datos mínimos y armonizados que solicita el Ministerio de Sanidad (en el ejercicio de sus funciones de coordinación), sino todos los conjuntos de datos que se estén recopilando. La transparencia ayuda a la ciudadanía a comprender las medidas que se toman en base a los datos y a aplicarlas.
- Asegurar un tratamiento de los datos que permita mantener su trazabilidad, conservar accesibles todas las versiones de los datos (registros históricos) dentro del repositorio con el fin de permitir el estudio de la evolución de la pandemia. El repositorio debería estar integrado con los portales de transparencia tanto de la administración central como de las comunidades autónomas, para facilitar aún más el acceso de la ciudadanía a los datos. 
- Publicar los datos de forma transparente, teniendo en cuenta las necesidades informativas y de investigación de los colectivos que trabajan con los datos (comunidad científica y medios de comunicación, por poner dos ejemplos).
- Proporcionar datos con un nivel de desagregación suficiente para ser útiles (edad, provincia, municipio, zonas de salud,...) y que al mismo tiempo sea compatible con la anonimización exigida en materia de protección de datos. 
- Centralizar la información. La Administración debe mantener un sitio web orientado a la ciudadanía que de forma clara centralice toda la información e indique cuál es la situación epidemiológica actual y qué medidas le afectan en cada momento (por localidad, actividad profesional etc). De esta forma, la ciudadanía tendría la posibilidad de incrementar las medidas de precaución o limitar su movilidad más allá de lo exigido por las autoridades basándose en información veraz y accesible.
- Informar de forma transparente sobre la influencia de la variación del número y tipo tests realizados en valores obtenidos (incidencia acumulada, porcentaje positividad). Con la gran variación de pruebas diagnósticas realizadas, y sin información desagregada por provincias, ni información separada de los cribados generalizados, la evaluación de la incidencia acumulada o casos diarios es muy problemática.
- Interpretar los datos de forma preliminar. La publicación de los datos por parte de la administración debería incluir una primera interpretación de los mismos, así como las pautas de dicho análisis, para evitar las interpretaciones erróneas tanto por parte de los medios como de la propia ciudadanía. 


 [^1]: Situación y evolución de la pandemia de COVID-19 en España. Panel Covid-19 en Instituto de Salud Carlos III. [https://cnecovid.isciii.es/covid19/#documentación-y-datos](https://cnecovid.isciii.es/covid19/#documentaci%C3%B3n-y-datos)

 [^2]: Autonomías y Covid-19: ¿datos para comunicar o para confundir? (David Rodríguez Mateos) [https://theconversation.com/profiles/david-rodriguez-mateos-1170231](https://theconversation.com/profiles/david-rodriguez-mateos-1170231)
 
 [^3]: Artículo en blog que cuenta la ausencia de publicación de fallecidos por provicnias en la CAPV [https://numeroteca.org/2020/11/25/fallecidos-euskadi-provinicias-datos](https://numeroteca.org/2020/11/25/fallecidos-euskadi-provinicias-datos)
 
 [^4]: Evolución del coronavirus (COVID-19) en Euskadi [https://opendata.euskadi.eus/catalogo/-/evolucion-del-coronavirus-covid-19-en-euskadi/](https://opendata.euskadi.eus/catalogo/-/evolucion-del-coronavirus-covid-19-en-euskadi/)

[^5]: Hilo de Twitter que recoge el proceso de reutilización de datos en la CAV: https://twitter.com/numeroteca/status/1370123787472154625

[^6]: _Todavía es posible. Por unos datos públicos accesibles para la construcción de un conocimiento compartido en tiempos de pandemia global_ (junio 2020) [https://datoscovid19esposible.github.io](https://datoscovid19esposible.github.io/)
