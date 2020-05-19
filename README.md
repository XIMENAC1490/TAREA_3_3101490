# TAREA 3- Publicación de mapas utilizando servicios en la nube

**Objetivos**

* Aplicar técnicas para el procesamiento, análisis y visualización de información georrefenciada para plantear la solución de un problema de interés.
* Entender y aplicar los procedimientos requeridos para realizar la publicación y visualización de datos geográficos en internet utilizando SaaS (Software as a Service).
* Aprovechar los elementos de interactividad proporcionados por las diferentes herramientas para la generación de aplicaciones que incorporan mapas.
* Narrar la solución dada al problema propuesto a través de una historia interactiva que involucre mapas y elementos multimedia.

**Entrega de resultados para revisión** 

* En el repositorio github personal creado para la clase crear una carpeta llamada Tarea_3
* Dentro de la carpeta Tarea_3 Crear un archivo Readme.md con los resultados de las actividades solicitadas.
* Una vez tenga los resultados publicados en github, crear un issue en 
https://github.com/dersteppenwolf/cartografia_web/issues con lo siguiente:
    
    ° Título: Tarea 3 - CODIGO_ESTUDIANTE
    ° Contenido: Enlace (URL) al archivo Readme.md dentro de la carpeta Tarea_3 publicado en el repositorio personal del curso.
     Ejemplo: https://github.com/dersteppenwolf/tareas_jc/blob/master/Tarea_1/README.md 

**Actividades**

**1. Definición del problema y fuentes de datos**

**Impacto Ambiental positivo que ha dejado el COVID- 19**

* Descripción del trabajo

La pandemia del coronavirus paradójicamente le ha generado un respiro al planeta. La reducción del número y la frecuencia de vuelos entre distintos destinos, así como el tráfico vehicular interno y el encierro obligado en el que se encuentran miles de personas en varias ciudades del mundo, han permitido que se reduza el nivel de emisiones de gases de efecto invernadero. 

* Describa de forma resumida el enfoque propuesto para el desarrollo del problema.


* Crear un boceto (mockup) donde se plantee la narrativa que se presentará al usuario e incluir cada una de las imágenes del mismo.

* Listado detallado de las fuentes de datos seleccionadas.

Capa | Descripción | Link
---|---|---
**Estaciones Calidad del aire**|Ubicación de las estaciones de la Red de Monitoreo de Calidad del Aire de Bogotá (RMCAB) para el área urbana del Distrito Capital, temáticamente  cuenta con el nombre de la estación de monitoreo que identifica el lugar donde se encuentra instalada, codificación, dirección, nombre de la entidad que permite la instalación de los equipos, altura de la estación snmm y altura de la estación con referencia al suelo, propósito de medición de la estación (Tráfico, fondo de la ciudad, de frontera, industrial) y si la estación está activa o inactiva| [https://www.datos.gov.co/Ambiente-y-Desarrollo-Sostenible/calidad-del-aire/7nmd-u7pq]
**Localidad. Bogotá D.C**|División política, administrativa y territorial municipal, con competencias claras y criterios de financiación y aplicación de recursos, creada por el Concejo Municipal a iniciativa del alcalde respectivo, con el fin de atender de manera más eficaz las necesidades de esa porción del territorio, cuenta con el nombre de cada localidad, localización y área.| [https://datosabiertos.bogota.gov.co/dataset/localidad-bogota-d-c]
**Temperatura Media Superficial**| Almacena las curvas de interpolación de la temperatura media superficial representada mediante un intervalo de temperatura medido en grados centigrados, y calculado para el periodo de reporte en el área urbana de Bogotá D.C,cuenta con  los valores de temperatura media superficial, periodo de medición (mensual, trimestral o anual) y año correspondiente al valor medido, así como el área de cada nivel de temperatura.| [http://visorgeo.ambientebogota.gov.co/?lon=-74.088081&lat=4.661300&z=11&l=5:1|84:1|12:1]
**Concentración de Material Particulado Inferior a 2.5 Micrómetros [PM 2.5] Promedio Mensual por Estación**| Contiene la concentración de Material Particulado inferior a 2.5 micras (PM2.5) anual por estación (Kennedy - Ken, Carvajal - Carv, Centro de Alto rendimiento - CdAR, Usaquén - Usaq, Fontibón - Fon, Puente Aranda - Puen, San Cristóbal - SanC, Tunal - Tunal, Guaymaral - Gua, Las Ferias - LFer, MinAmbiente - MinA, Suba - Suba) de la Red de Monitoreo de Calidad del Aire de Bogotá RMCAB.|[https://datosabiertos.bogota.gov.co/dataset/concentracion-de-material-particulado-inferior-a-2-5-micrometros-pm2-5-promedio-rmcab]
**Concentración de Material Particulado Inferior a 10 Micrómetros [PM 10] Promedio Mensual por Estación** | Contiene la concentraación de Material Particulado inferior a 10 micras (PM 10) anual por estación (Kennedy - Ken, Carvajal - Carv, Centro de Alto rendimiento - CdAR, Usaquén - Usaq, Fontibón - Fon, Puente Aranda - Puen, San Cristóbal - SanC, Tunal - Tunal, Guaymaral - Gua, Las Ferias - LFer, MinAmbiente - MinA, Suba - Suba) de la Red de Monitoreo de Calidad del Aire de Bogotá RMCAB. | https://datosabiertos.bogota.gov.co/dataset/concentracion-de-material-particulado-inferior-a-10-micrometros-pm10-promedio-mensual-por-estacion



https://datosabiertos.bogota.gov.co/dataset/temperatura-media-superficial-bogota-d-c