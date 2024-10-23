# Analisis_CABA_EDA
Análisis de accidentes viales en la Ciudad Autónoma De Buenos Aires, Argentina.  2016 - 2021 (ETL,EDA; Powerbi)

# Siniestros Viales 2016 - 2021

__Análisis de Siniestros Viales en la Ciudad de Buenos Aires: Análisis de datos para la reducción de víctimas fatales__

Los siniestros viales, que incluyen accidentes entre vehículos, peatones y objetos fijos, son una preocupación creciente en Buenos Aires, donde la alta densidad de tráfico y población intensifican su impacto. Estos incidentes pueden resultar en daños materiales y lesiones graves o fatales, afectando tanto a los residentes como a los visitantes.

Las tasas de mortalidad por siniestros viales son un indicador clave de la seguridad vial en la ciudad. Reducir estas tasas es fundamental para proteger la vida de las personas y mejorar la seguridad en las vías. Para abordar este problema, es esencial implementar medidas de prevención, que incluyen la educación vial, el cumplimiento de las normas de tráfico, la mejora de la infraestructura vial y la promoción de vehículos más seguros.

Un seguimiento constante de las estadísticas y políticas efectivas es necesario para enfrentar este desafío y garantizar una movilidad segura en la ciudad.

# Contexto y Rol 

En Argentina, aproximadamente 4,000 personas mueren anualmente en siniestros viales, lo que los convierte en la principal causa de muertes violentas en el país. Según el Sistema Nacional de Información Criminal (SNIC), entre 2018 y 2022 se registraron 19,630 muertes por accidentes de tránsito, lo que equivale a 11 muertes diarias. En 2022, se reportaron 3,828 muertes fatales. Expertos indican que la probabilidad de morir en un siniestro vial es de dos a tres veces mayor que en incidentes de inseguridad delictiva.

El Observatorio de Movilidad y Seguridad Vial (OMSV) solicita la elaboración de un proyecto de análisis de datos para generar información que ayude a las autoridades de Buenos Aires a reducir las víctimas fatales en siniestros viales. Se proporciona un dataset en formato XLSX que abarca homicidios en siniestros viales ocurridos en la ciudad entre 2016 y 2021. Este dataset incluye dos hojas principales: "hechos" y "víctimas", junto con dos hojas adicionales que contienen diccionarios de datos para facilitar la comprensión.

El proyecto se enfocará en el análisis de estos datos para identificar patrones, tendencias y factores de riesgo, proporcionando recomendaciones basadas en evidencia para mejorar la seguridad vial en la ciudad. Además, se contará con material de apoyo para enriquecer el entendimiento del contexto y la información disponible.

# Desarrollo del Proyecto

__Para este proyecto lo dividimos en 3 pasos importantes.__

1. **ETL (EXTRACT, TRANSFORM, LOAD)**

   __Procesamiento de datos ('./Procesamiento_de_datos.ipynb'): en este archivo trabajamos diferentes operaciones de limpieza de datos como:__ <br>
   * Normalizar escrituras <br>
   * Conteo de datos nulos <br>
   * Verificar tipo de datos <br>
   * Verificar duplicados <br>
   * Manejo de valores faltantes

2. **EDA (ANÁLISIS EXPLORATORIO)** <br>

   __En este archivo ('./Analisis_Exploratorio.ipynb') trabajamos con los datos ya procesados para un correcto análisis y creación de gráficas durante todo el proyecto.__

   Esto nos ayuda a tener una noción más completa de los datasets proporcionados por la OMSV y hacer algunos cálculos de los mismos, optimizando el tiempo para que en la elaboración de nuestro dashboard sea más eficiente. Esto también nos permite proponer algunas ideas para esta problemática.

3. **Dashboard en Power BI** <br>

   __Se creó un dashboard interactivo llamado ('./siniestros_viales.pbix'), el cual contiene la información más detallada y visualizada por medio de gráficas.__ 

   * Visualizamos 3 KPIs en base a la información solicitada por la OMSV.
   * Identificamos patrones.
   * Obtuvimos conclusiones del análisis de víctimas durante estos últimos años.

# Archivos Adjuntados

* __Data_Original:__ Excel proporcionado por la OMSV.
* __Data_clean:__ Datasets trabajados y limpiados para su análisis en formato CSV.
* __Analisis_exploratorio:__ Proceso EDA.
* __Procesamiento_de_datos:__ Proceso ETL.
* __siniestros_viales:__ Dashboard interactivo en Power BI.

Observaciones: hay un archivo llamado 'homicidios_victimas_ID_UNICO', el cual cuenta con una columna que se le asignó un ID único a cada persona que falleció en el mismo día y tenía un mismo ID. Este fue con el que se trabajó directamente en el dashboard.

## Dependencias

Este proyecto utiliza las siguientes librerías de Python:

- **pandas**: Para la manipulación y análisis de datos.
- **numpy**: Para operaciones numéricas y soporte de matrices.
- **seaborn**: Para visualización de datos.
- **matplotlib**: Para crear gráficos y visualizaciones.
- **datetime**: Para manejar fechas y horas.

### Instalación

Puedes instalar las dependencias necesarias utilizando `pip install`.

## Contacto

Desarrollador: [Gabriel Rizo](https://github.com/Rizo12G)  
Correo: rizo.tnt@gmail.com
