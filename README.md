
![HenryLogo](https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png)

# **PROYECTO INDIVIDUAL Nº3**

# <h1 align="center">**`Telecomunicaciones`**</h1>

<p align="center">
<img src="./Telecomunicaciones.jpg"   



## **Descripción del problema (Contexto y rol a desarrollar)**

### **Contexto**
Una conocida empresa líder a nivel mundial en implementación de servicios de telecomunicaciones , principalmente implementación de fibra y antenas 4 y 5G requiere hacer un estudio, analizando el comportamiento del sector y las posibilidades de inversión en Sudamérica.
Recabaron información del año 2020 en donde obtienen, en comparación con la media mundial, Argentina está a la vanguardia del desarrollo de las telecomunicaciones, teniendo para el 2020 un total de [62,12 millones conexiones](https://www.datosmundial.com/america/argentina/telecomunicacion.php). 

### Objetivo
En este contexto, nos encargan la realización de un **análisis** completo que permita reconocer el comportamiento de este sector a nivel nacional. Considere que la principal actividad de la empresa es brindar **acceso a internet**, pero también es importante considerar el resto de los servicios. 

Con el fin de monitorear la eficacia de los objetivos de la empresa, nos piden analizar  y visualizar metricas que permitan una adecuada toma de decisión en la inversion que quieren realizar. 
De todas las metricas nos solicitan revisar la penetración por familia, metrica muy usada para el analisis en este sector.


## **Plan de trabajo **

1.- Nos solicitan hacer una revisión de la fuente ENACOM, quien proporciona información de servicios de comunicaciones en provincias.
2.- Se revisa las 16 tablas que refieren información del Internet en Argentina
3. Se revisa el resumen del informe de directorio expuesto en redes para ver el alcance y el compromiso de planes del año 2023
4. Se valida la información que brinda este ente del estado con otras fuentes:
    Unión Internacional de Telecomunicaciones (UIT) es el organismo especializado de las Naciones Unidas para las tecnologías de la información y la comunicación – TIC.
    -https://datahub.itu.int/data/?i=&d=location&e=701&c=ARG
    Paginas de estadisticas como https://es.statista.com/

Para realizar este trabajo se cargo a traves del api la data a Python, y se procedió al EDA que contempla:
            - Revisión de nulos
            -Estandarizacion de nombres de columnas faciles de usar
            -Revision de decimales y comas
            - carga de valores 'no dato'
            -revision de los tipo de dato luego de realizar la limpieza.

De las 16 tablas revisadas se escogieron 6, que nos podian dar información general y a nivel de provincia, data importante para tener al analizar la penetración del uso de Internet.
Estas tablas son llevadas a Mysql, con el fin de poder mejorar el imforme despues de esta primera presentación al cliente.

`Dashboard`:
Se crean 5 paginas que nos muestran las metricas que presentamos al cliente:
            Métrica de ingresos por trimestre por año 
            Métrica de penetración de uso de internet por hogares y por habitante
            Métrica de penetración de internet por provincia
            Métrica de evolución de la tecnología de internet 
            Métrica uso de banda ancha versus Dialup
            Métrica uso de banda ancha versus Dialup por provincia


`Análisis`: :Se adjunta en este documento los antecedentes, las metricas y las conclusiones del analisis realizado.