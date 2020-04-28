# Datos-COVID19
El objetivo de la Mesa de Datos COVID-19 liderada por el Ministerio de Ciencia, Tecnología, Conocimiento e Innovación es disponer la información epidemiológica de nuestro país para promover el uso de datos para investigación científica, clínica y para soluciones innovadoras que contribuyan a la toma de decisiones de las autoridades y la ciudadanía frente a esta pandemia. Como primer resultado de este equipo técnico, se disponen los datos epidemiológicos provenientes del Ministerio de Salud (MINSAL), documentados y abiertos para el análisis de la comunidad, en concordancia con la [Ley Nº 19.628](https://www.leychile.cl/Navegar?idNorma=141599). 

Ver http://www.minciencia.gob.cl/COVID19 para más información.

# Data Products

[Data Product 1 - Casos totales por comuna incremental](output/producto1): Archivo con valores separados por coma (csv) que concatena historia de publicaciones de MINSAL sobre casos confirmados totales por comuna. Contiene las columnas 'Región', ‘Código Región’, 'Comuna', ‘Código comuna’, 'Población', múltiples columnas correspondientes a '[fecha]', y una columna 'Tasa'. Incluye versión con serie de tiempo. [Ver más](output/producto1).

[Data Product 2 - Casos totales por comuna](output/producto2): Archivos con valores separados por coma (csv) con la información de casos confirmados notificados a nivel comunal por cada informe publicado. Cada archivo contiene las columnas 'Región', ‘Código Región’, 'Comuna', ‘Código comuna’, 'Población' y 'Casos Confirmados'. [Ver más](output/producto2).

[Data Product 3 - Casos totales por región incremental](output/producto3): Archivo con valores separados por coma (csv) que concatena historia de publicaciones de casos totales por parte de MINSAL. El archivo contiene una columna 'Región', seguida por columnas correspondientes a '[fecha]'. Estas últimas columnas, ‘[fecha]’, contienen los 'Casos Confirmados' reportados por el Ministerio de Salud de Chile en cada una de las fechas que se indican en las respectivas columnas. Incluye versión con serie de tiempo. [Ver más](output/producto3).

[Data Product 4 - Casos totales por región](output/producto4) (un archivo por informe): Serie de archivos que dan cuenta del total de casos confirmados, casos recuperados, % de casos totales y casos fallecidos en cada una de las regiones de Chile, según residencia. Cada uno de los archivos corresponde a la información diaria que reporta el Ministerio de Salud del país. Existe variabilidad en los campos según la fecha. [Ver más](output/producto4).

[Data Product 5 - Totales Nacionales Diarios](output/producto5): Set de 2 archivos sobre casos a nivel nacional. El primero de ellos (TotalesNacionales.csv) incluye los casos nuevos confirmados, totales o acumulados, recuperados, fallecidos a nivel nacional y activos según fecha de diagnóstico, reportados diariamente por el Ministerio de Salud desde el 03-03-2020. El segundo (recuperados.csv) contiene sólo los casos recuperados. [Ver más](output/producto5).

[Data Product 6 (contribuido) - Enriquecimiento del Data Product 2](output/producto6): Set de 2 archivos, en formato CSV y JSON, que dan cuenta de la tasa de incidencia acumulada y los casos confirmados acumulados en cada una de las comunas de Chile, según residencia, conforme a los informes epidemiológicos publicados por el Ministerio de Salud del país. Esto es una mejora derivada del producto 2, al colocar varios archivos de aquel producto en un solo archivo. [Ver más](output/producto6).

[Data Product 7 - Exámenes PCR por región](output/producto7): Set de 2 archivos que dan cuenta del número de exámenes PCR realizados por región reportados diariamente por el Ministerio de Salud, desde el 09-04-2020. El archivo PCR.csv contiene las columnas ‘Región’, ‘Código Región’ y ‘Población’, seguidas por columnas correspondientes a ‘[Fecha]’. Estas últimas columnas, ‘[Fecha]’ indican el número de exámenes realizados por región, desde el 09-04-2020 hasta la fecha. Incluye versión con serie de tiempo. [Ver más](output/producto7).

[Data Product 8 - Pacientes en UCI por región](output/producto8): Set de 2 archivos que dan cuenta del número de pacientes en UCI por región reportados diariamente por el Ministerio de Salud, desde el 01-04-2020. El archivo UCI.csv contiene las columnas ‘Región’, ‘Código Región’ y ‘Población’, y múltiples columnas correspondientes a ‘[Fecha]’. Estas últimas columnas, ‘[Fecha]’ indican el número de pacientes en UCI por región, desde el 01-04-2020 hasta la fecha. Incluye versión con serie de tiempo. [Ver más](output/producto8).

[Data Product 9 - Pacientes en UCI por grupo de edad](output/producto9): Set de 2 archivos que dan cuenta del número de pacientes en UCI por grupos etarios (<=39; 40-49; 50-59; 60-69; y >=70) reportados diariamente por el Ministerio de Salud, desde el 01-04-2020. El archivo HospitalizadosUCIEtario.csv contiene la columna ‘Grupo de edad’, seguida por columnas correspondientes a ‘[Fecha]’. Estas últimas columnas, ‘[Fecha]’, indican el número de pacientes en UCI por grupo etario, desde el 01-04-2020 hasta la fecha. Incluye versión con serie de tiempo. [Ver más](output/producto9).

[Data Product 10 - Fallecidos por grupo de edad](output/producto10): Set de 2 archivos que dan cuenta del número de fallecidos por grupos etarios (<=39; 40-49; 50-59; 60-69; 70-79; 80-89; y >=90) reportados diariamente por el Ministerio de Salud, desde el 09-04-2020. El archivo FallecidosEtario.csv contiene la columna ‘Grupo de edad’, seguida por columnas correspondientes a ‘[Fecha]’. Estas últimas columnas, ‘[Fecha]’, indican el número de personas fallecidas por grupo etario, desde el 09-04-2020 hasta la fecha. Incluye versión con serie de tiempo. [Ver más](output/producto10).

[Data Product 11 (contribuido) - Enriquecimiento del Data Product 4](output/producto11): El [Data Product 4](output/producto4) con todos los datos compilados en formato CSV y JSON, en un solo archivo, llamados producto4.csv y producto4.json respectivamente. Los archivos contienen las columnas ‘Región’, ‘Nuevos Casos’, ‘Casos Confirmados’, ‘Fallecidos’, ‘Fecha’, ‘Región ID’, ‘Población’ y ‘Tasa’. Estos valores están separados entre sí por comas (csv), y organizados en tuplas en el caso del JSON. [Ver más](output/producto11).

[Data Product 12 (contribuido) - Enriquecimiento del Data Product 7](output/producto12): El [Data Product 7](output/producto7) con todos los datos compilados en formato CSV y JSON, en un solo archivo, llamados producto7.csv y producto7.json respectivamente. Los archivos contienen las columnas ‘Región’, ‘Población’, ‘Fecha’, ‘PCR Realizados’, ‘Región ID’, y ‘Tasa’. Estos valores están separados entre sí por comas (csv), y organizados en tuplas en el JSON. [Ver más](output/producto12).

[Data Product 13 - Casos nuevos por región incremental](output/producto13): Set de 2 archivos que dan cuenta del número de casos nuevos por día según resultado del diagnóstico, por región de residencia, reportados por el Ministerio de Salud desde el 03-03-2020. El archivo CasosNuevosCumulativo.csv contiene la columna ‘Región’, seguida por columnas correspondientes a ‘[Fecha]’. Estas últimas columnas, ‘[Fecha]’, indican el número de casos nuevos acumulativos, por región, desde el 03-03-2020 hasta la fecha. Incluye versión con serie de tiempo. [Ver más](output/producto13).

[Data Product 14 - Fallecidos por región incremental](output/producto14): Set de 2 archivos que dan cuenta del número de fallecidos por día, según región de residencia, y concatena la historia de los reportes del Ministerio de Salud desde el 22-03-2020. El archivo FallecidosCumulativo.csv contiene la columna ‘Región’, seguida por columnas correspondientes a ‘[Fecha]’. Estas últimas columnas, ‘[Fecha]’, indican el número de fallecidos acumulativo, por región, desde el 22-03-2020 hasta la fecha. Incluye versión con serie de tiempo. [Ver más](output/producto14).

[Data Product 15 - Casos nuevos por fecha de inicio de síntomas por comuna](output/producto15): Set de 3 archivos que dan cuenta de los casos nuevos por fecha de inicio de sus síntomas en cada una de las comunas de Chile, según residencia. Refleja la información del último informe epidemiológico publicado por el Ministerio de Salud del país. Se indexan estos casos según semana epidemiológica reportada en el informe, con fechas incluidas en los archivos. Incluye versión con serie de tiempo. [Ver más](output/producto15).

[Data Product 16 - Casos por genero y grupo de edad](output/producto16): Archivo que da cuenta del número acumulado de casos confirmados distribuidos por género y grupo de edad, para cada fecha reportada. Este concatena la historia de los informes epidemiológicos publicados por el Ministerio de Salud del país. Incluye versión con serie de tiempo. [Ver más](output/producto16).

[Data Product 17 - PCR acumulado e informado en el último día por tipo de establecimientos](output/producto17): Archivo que da cuenta del número total acumulado de exámenes PCR a nivel nacional y los informados durante las últimas 24 hrs. Se consideran los distintos tipos de establecimientos: Instituto de Salud Pública, Hospitales públicos y Hospitales privados. Este archivo concatena la historia de los reportes diarios publicados por el Ministerio de Salud del país. El archivo (PCREstablecimiento.csv), contiene las columnas 'Establecimiento' para el tipo de institución; 'Examenes', cuyas 3 primeras filas muestran el total realizado acumulado y las 3 últimas los reportados durante las últimas 24 hrs; y una serie de columnas con '[Fecha]', donde se da el número de exámenes reportados por Epidemiología MINSAL a cada fecha. [Ver más](output/producto17).

[Data Product 18 - Tasa de incidencia historica por comuna y total regional](output/producto18): Archivo que da cuenta de la tasa de incidencia acumulada en cada una de las comunas de Chile, y concatena la historia de los informes epidemiológicos publicados por el Ministerio de Salud del país. Se entiende por tasa de incidencia al número total de casos confirmados desde el primer caso confirmado hasta la fecha de elaboración del informe epidemiológico, en relación a la población susceptible de enfermar en un periodo determinado. El archivo TasadeIncidencia.csv), contiene las columnas 'Región', 'Código región', 'Comuna', 'Código comuna', 'Población', y varias columnas '[Fecha]', donde cada una tiene la 'Tasa de incidencia' reportadas en cada publicación de Epidemiología, para cada comuna, en las fechas reportadas. Incluye versión con serie de tiempo. [Ver más](output/producto18).

[Data Product 19 - Casos activos por fecha de inicio de síntomas y comuna](output/producto19): Archivo que da cuenta del número de casos confirmados activos notificados en cada una de las comunas de Chile, según residencia, y concatena la historia de los informes epidemiológicos publicados por el Ministerio de Salud del país. El archivo (CasosActivosPorComuna.csv), contiene las columnas 'Región', 'Código región', 'Comuna', 'Código comuna', 'Población', y una serie de columnas '[Fecha]', donde en cada una están los 'Casos activos' reportados en cada publicación de Epidemiología, por cada comuna, en cada fecha reportada. Incluye versión con serie de tiempo. [Ver más](output/producto19).

[Data Product 20 - Ventiladores a nivel nacional](output/producto20): Este producto da cuenta del número total de ventiladores en el Sistema Integrado Covid 19, el número de ventiladores disponibles y el número de ventiladores ocupados, para cada fecha reportada.  Se concatena la historia de los reportes diarios publicados por el Ministerio de Salud del país. Incluye versión con serie de tiempo. [Ver más](output/producto20).

[Data Product 21 - Sintomas por Casos Confirmados e informado en el último día](output/producto21): Este producto da cuenta de la sintomatología reportada por los casos confirmados. También da cuenta de la sintomatología reportada por casos confirmados que han requerido hospitalización. Se concatena la historia de los informes de Situación Epidemiológica publicados por el Ministerio de Salud del país. Los archivos SintomasCasosConfirmados.csv y SintomasHospitalizados.csv tienen una columna 'Síntomas' y una serie de columnas '[Fechas]', donde por cada síntoma en una fila, se reporta el número acumulado a cada fecha de casos confirmados con dicho síntoma (entre casos confirmados y hospitalizados, respectivamente). Incluye versiones con series de tiempo. [Ver más](output/producto21).

[Data Product 22 - Hospitalizados por grupo de edad](output/producto22): Este producto, que consiste de varios archivos, da cuenta del número acumulado del total de pacientes hospitalizados por rango de edad y género. También da cuenta del número acumulado de pacientes internados en la Unidad de Cuidados Intensivos (UCI) por rango de edad. Se concatena la historia de los informes de Situación Epidemiológica publicados por el Ministerio de Salud del país. Los archivos presentan varias versiones de rangos etareos. Incluye versiones con series de tiempo. [Ver más](output/producto22). 

[Data Product 23 - Pacientes críticos](output/producto23): Este producto da cuenta del número de pacientes hospitalizados en la Unidad de Cuidados Intensivos (UCI) y se consideran en situación médica crítica. Se concatena la historia de reportes diarios publicados por el Ministerio de Salud del país. El archivo (PacientesCriticos.csv) contiene el reporte diario de la cantidad de pacientes críticos, por cada '[Fecha]' reportada en las columnas. Incluye versión con serie de tiempo. [Ver más](output/producto23).

[Data Product 24 - Hospitalización de pacientes en sistema integrado](output/producto24): Este producto da cuenta del número de pacientes en hospitalización según el tipo de cama que ocupan: Básica, Media, UTI y UCI. Se concatena la historia de reportes diarios publicados por el Ministerio de Salud del país. El archivo CamasHospital_Diario.csv, corresponde al reporte diario de la cantidad de pacientes en camas (Básica, Media, UCI o en UTI). Contiene las columnas 'Tipo de Cama', y una serie de columnas '[Fecha]', donde estas contiene el número de ocupación por día, por tipo de cama. Incluye versión con serie de tiempo. [Ver más](output/producto24).

[Data Product 25 - Casos actuales por fecha de inicio de síntomas y comuna](output/producto25): Archivo que da cuenta del número de casos confirmados actuales notificados en cada una de las comunas de Chile, según residencia, y concatena la historia de los informes epidemiológicos publicados por el Ministerio de Salud del país. El archivo CasosActualesPorComuna.csv, contiene las columnas 'Región', 'Código región', 'Comuna', 'Código comuna', 'Población', y una serie de columnas '[fecha]', donde cada fecha tiene los 'Casos actuales' reportados en cada publicación de Epidemiología. Incluye versión con serie de tiempo. [Ver más](output/producto25)

**Nota: La fecha otorgada a cada reporte corresponde a la publicación por MINSAL. Habitualmente refleja el registro del día anterior, salvo que se indique lo contrario**


## ¿Cómo funciona?
Tenemos cuatro fuentes de datos: el reporte diario, informe epidemiológico, informe de situación covid19 y la pagina web del MINSAL.
Para el caso de los pdfs, transcribimos los contenidos para generar archivos CSV, que son utilizados para generar los productos relevantes:

   * [Reporte diario](src/reporteDiario.py)
   * [Informe epidemiológico](src/informeEpidemiologico.py) 
   * [Informe de situación epidemiológica](src/informeSituacionCOVID19.py)


En cuanto a los archivos a nivel regional: Hacemos scraping de tabla en https://www.minsal.cl/nuevo-coronavirus-2019-ncov/casos-confirmados-en-chile-covid-19/ y generamos archivo csv por día.
   * [Webscraper](src/webpage.py)

Este esta automatizado a ~ 12:00, usando github actions.

![dataUpdate](https://github.com/MinCiencia/Datos-COVID19/workflows/dataUpdate/badge.svg)

# Contacto
Si encuentras errores, por favor repórtalos [acá](https://github.com/MinCiencia/Datos-COVID19/issues). La automatización de este proceso y disposición de datos ha sido inicializada por el equipo del Data Observatory (http://www.dataobservatory.net), estan todos invitados a colaborar.
Si has creado una solución que permita facilitar el trabajo con estos datos, algún análisis, o simplemente tienes una solicitud de data product considerando los datos que MINSAL hace públicos hoy, escríbenos a darancibia@minciencia.gob.cl

## Agradecimientos

Geógrafo Virginia Behm - académica Escuela de Salud Pública U. Chile.

Miguel A. Bustos Valdebenito | Estudiante Dr. Ing. Mec. - U.Chile | Mtr. Ing. Ind. - UAI  | Ing. Civil y Ejec. Mec. - U. de Santiago

Annabella Zapata y Carlos Navarrete, Chilecracia y Datawheel

Leandro Zamudio León y Luis Meneses Retamal | Soporta Ltda.
