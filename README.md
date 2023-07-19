<p align=center><img style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;
           height=400px"
        src=src/henry.PNG
        alt="henry"><p>
<h1 align=center> <strong>Henry Project Nº Data Science</strong> </h1>
<h1 align=center><strong> Data Analytics </strong></h1>
<p align=center><img style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 400px
           height=300px"
        src="src/telecommunications.jpg"
        alt="Telecommunications"><p>



# **Introducción y Contexto**

📡 Las telecomunicaciones se refieren a la transmisión de información a través de medios electrónicos, como la telefonía, la televisión, la radio y, más recientemente, el internet. Estos medios de comunicación permiten la transmisión de información entre personas, organizaciones y dispositivos a largas distancias.

El internet, por su parte, es una red global de computadoras interconectadas que permite el intercambio de información en tiempo real. Desde su creación, ha tenido un impacto significativo en la vida de las personas, transformando la manera en que nos comunicamos, trabajamos, aprendemos y nos entretenemos.

La industria de las telecomunicaciones ha jugado un papel vital en nuestra sociedad, facilitando la información a escala internacional y permitiendo la comunicación continua incluso en medio de una pandemia mundial. La transferencia de datos y comunicación se realiza en su mayoría a través de internet, líneas telefónicas fijas, telefonía móvil, y en casi cualquier lugar del mundo.

En comparación con la media mundial, Argentina está a la vanguardia en el desarrollo de las telecomunicaciones, teniendo para el 2020 un total de 62,12 millones de conexiones.

▶ En este contexto, me ha sido encargado realizar un análisis completo que me permita reconocer el comportamiento del sector de las telecomunicaciones a nivel nacional. Sin embargo, también es importante considerar el comportamiento asociado al resto de los servicios de comunicación. Esto me permitirá orientar a la empresa para ofrecer servicios de alta calidad, identificar oportunidades de crecimiento y plantear soluciones personalizadas a nuestros posibles clientes.


▶ El análisis abarcará diversos aspectos, como la calidad del servicio de internet ofrecido, la cantidad de conexiones por tipo de tecnología (ADSL, Cablemodem, Fibra óptica, Wireless, entre otros), el total de conexiones de internet en cada provincia. También se analizará la distribución de conexiones por velocidades de descarga, desde conexiones de baja velocidad hasta conexiones de alta velocidad (como 30 Mbps o más).
Este análisis nos permitirá tener una visión integral del sector de las telecomunicaciones, identificar áreas de mejora, detectar oportunidades para expandir nuestra cobertura y brindar un servicio de internet más rápido y confiable. Además, podremos adaptar nuestras estrategias y soluciones a las necesidades específicas de cada provincia, teniendo en cuenta las particularidades de cada región.

En resumen, el objetivo principal es utilizar este análisis completo del sector de las telecomunicaciones para optimizar nuestros servicios de internet, mantenernos a la vanguardia en el mercado, mejorar las conexiones y la calidad de estas a nivel nacional y brindar una experiencia excepcional a nuestros clientes en todo el país.

# **Diccionario de Datos** 

| Campo                     | Descripción                                                                                               |
|---------------------------|-----------------------------------------------------------------------------------------------------------|
| Año                       | El año correspondiente a los datos de la fila.                                                            |
| Trimestre                 | El trimestre correspondiente a los datos de la fila.                                                      |
| Provincia                 | El nombre de la provincia para la cual se proporcionan los datos.                                         |
| ADSL                      | Número de conexiones de tipo ADSL en la provincia para el año y trimestre específicos.                   |
| Cablemodem                | Número de conexiones de tipo Cablemodem en la provincia para el año y trimestre específicos.             |
| Fibra óptica              | Número de conexiones de tipo Fibra óptica en la provincia para el año y trimestre específicos.           |
| Wireless                  | Número de conexiones de tipo Wireless en la provincia para el año y trimestre específicos.               |
| Otros                     | Número de conexiones de otros tipos en la provincia para el año y trimestre específicos.                  |
| Total_conexion            | Total de conexiones de Internet en la provincia para el año y trimestre específicos.                      |
| Accesos por cada 100 hab  | Número de accesos a Internet por cada 100 habitantes en la provincia para el año y trimestre específicos. |
| Accesos por cada 100 hog  | Número de accesos a Internet por cada 100 hogares en la provincia para el año y trimestre específicos.    |
| Banda ancha fija          | Número de conexiones de banda ancha fija en la provincia para el año y trimestre específicos.            |
| Dial up                   | Número de conexiones de tipo Dial up en la provincia para el año y trimestre específicos.                |
| Hasta 512 kbps            | Número de conexiones con velocidad hasta 512 kbps en la provincia para el año y trimestre específicos.    |
| 512 Kbps - 1 Mbps         | Número de conexiones con velocidad entre 512 Kbps y 1 Mbps en la provincia para el año y trimestre específicos. |
| 1 Mbps - 6 Mbps           | Número de conexiones con velocidad entre 1 Mbps y 6 Mbps en la provincia para el año y trimestre específicos. |
| 6 Mbps - 10 Mbps          | Número de conexiones con velocidad entre 6 Mbps y 10 Mbps en la provincia para el año y trimestre específicos. |
| 10 Mbps - 20 Mbps         | Número de conexiones con velocidad entre 10 Mbps y 20 Mbps en la provincia para el año y trimestre específicos. |
| 20 Mbps - 30 Mbps         | Número de conexiones con velocidad entre 20 Mbps y 30 Mbps en la provincia para el año y trimestre específicos. |
| 30 Mbps                   | Número de conexiones con velocidad superior a 30 Mbps en la provincia para el año y trimestre específicos. |
| Otros Mbps                | Número de conexiones con velocidad de otros tipos en la provincia para el año y trimestre específicos.    |
| Total suma Mbps           | Total de la suma de todas las conexiones de Internet por velocidad en la provincia para el año y trimestre específicos. |

# Definición de KPIs (Key Performance Indicators)
Como parte de nuestro proyecto, hemos desarrollado un conjunto de KPIs estratégicos que están diseñados para servir como propuestas de negocios dirigidas a potenciales clientes, como el gobierno nacional de Argentina y los gobiernos provinciales. Estos KPIs tienen como objetivo principal mejorar los aspectos de conectividad en cuanto a calidad y alcance de las redes de conexión a internet en el país, así como abordar las necesidades de las provincias menos desarrolladas en el sector de las telecomunicaciones. Nuestras propuestas se enfocan en expandir la infraestructura de telecomunicaciones, mejorar la calidad de los servicios de internet y garantizar un acceso equitativo a la tecnología en todas las regiones. A través de una posible colaboración estrecha con las diferentes entidades gubernamentales, nuestro objetivo final es cerrar la brecha digital en Argentina y construir un país más conectado e inclusivo para todos los ciudadanos, sin importar su ubicación geográfica.


📈 **1. Incremento en la cantidad de accesos de conexiones a internet por población y provincias:** Incremento del 2% anual en la cantidad de acceso de conexiones a internet por población, de las provincias Tucumán, Jujuy, Salta, Mendoza, Misiones, Catamarca, Santa Cruz, Santiago del Estero, Corrientes, Chaco, San Juan y Formosa, en los proximos 4 años. (2022-2026)
 * **Metrica:** Aumento en el numero de conexiones totales / Población total de cada provincia, en porcentaje
 * **Meta:**
>>> | Provincia             | 2022-Q1  | 2026-Q1  |
>>> |-----------------------|----------|----------|
>>> | Jujuy                 | 0.147960 | 0.227960 |
>>> | Catamarca             | 0.147649 | 0.227649 |
>>> | Misiones              | 0.133109 | 0.213109 |
>>> | Tucuman               | 0.141619 | 0.221619 |
>>> | Corrientes            | 0.125112 | 0.205112 |
>>> | Salta                 | 0.135342 | 0.215342 |
>>> | Chaco                 | 0.117386 | 0.197386 |
>>> | Formosa               | 0.088738 | 0.168738 |
>>> | Mendoza               | 0.135555 | 0.215555 |
>>> | Santa Cruz            | 0.127927 | 0.207927 |
>>> | Santiago Del Estero   | 0.116684 | 0.196684 |
>>> | San Juan              | 0.110541 | 0.190541 |


📈 **2. Incremento en el porcentaje de accesos a conexiones de internet por la tecnología 'Cablemodem' en relación a los accesos totales:** Incremento del 2.5% anual en los accesos de conexión a internet en la **tecnología 'Cablemodem'** para las provincias San Juan, Tucuman, Formosa y San Luis en los proximos 4 años. (2022-2026)
 * **Metrica:** Aumento en el número de conexiones por Cablemodem / Conexiones totales de cada provincia, en porcentaje.
 * **Meta:**
>>> | Provincia | 2022-1  | 2026-1  |
>>> |-----------|---------|---------|
>>> | Tucuman   | 0.254072 | 0.354072 |
>>> | San Juan  | 0.163862 | 0.263862 |
>>> | Formosa   | 0.291981 | 0.391981 |
>>> | San Luis  | 0.094256 | 0.194256 |

   
📈 **3. Incremento del porcentaje de provincias con una velocidad media de bajada de al menos 30 Mbps o más a nivel nacional:** Incremento del **20%** en el total de provincias con velocidad media de bajada de 30 Mbps o más para el año 2023 (5% Trimestral).
  * **Métrica:** Porcentaje actual de provincia con una velocidad de al menos 30 Mbps o más.
  * **Meta:** 83% en total para el año 2023.

