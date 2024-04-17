# Informe sobre Siniestros Viales en Buenos Aires

<p align="center">
  <img src="Dataset/image.png" alt="Descrição da imagem" width="800" height="500">
</p>


Este [Informe](https://drive.google.com/file/d/1BYOtdUqWXpGMsyuVFU0ebE6jCZY7XCMr/view?usp=sharing) tiene como objetivo analizar la problemática de los siniestros viales en la ciudad de Buenos Aires, utilizando como referencia el [Dataset Homicidios en Buenos Aires](https://data.buenosaires.gob.ar/dataset/victimas-siniestros-viales).

El informe proporciona una visión general de los siniestros viales, centrándose en tres aspectos clave: la reducción de accidentes, el análisis de accidentes de motocicletas y la relación entre sexos en los siniestros viales.

## EDA

El archivo EDA.ipynb apresenta los análisis exploratória de datos para el dataset disponibilizado, con explicación de que fue hecho en cada momento.

## Reducción de accidentes

El KPI utilizado para analizar la reducción de accidentes en la ciudad se basa en la tasa de homicidios en siniestros viales. Esta tasa se calcula dividiendo el número de homicidios en siniestros viales por la población y multiplicando el resultado por 100,000. La meta establecida es una reducción del 10% en la tasa de homicidios en comparación con el año base.

Su fórmula es: (Número de homicidios en siniestros viales / Población total) * 100,000

## Análisis de accidentes de motocicletas

El KPI utilizado para el análisis de accidentes de motocicletas se basa en la comparativa anual y la evolución de los mismos. Se calcula la media de reducción de accidentes de motocicletas por año y se establece una meta de reducción. La tendencia se calcula utilizando la media de reducción y se establece una meta de tendencia.

Su fórmula es: (Número de accidentes mortales con víctimas en moto en el año anterior - Número de accidentes mortales con víctimas  en moto en el año actual) / (Número de accidentes mortales con víctimas en moto en el año anterior) * 100

## Relación entre sexos en los siniestros viales

El KPI utilizado para analizar la relación entre sexos en los siniestros viales es la proporción de víctimas por sexo. Se calcula el porcentaje de víctimas masculinas y femeninas en comparación con el total de casos. Además, se realiza un análisis de la proporción por comuna y sexo para obtener una visión más detallada de las disparidades de género en diferentes áreas de la ciudad.

En conclusión, este informe destaca la importancia de abordar la problemática de los siniestros viales en Buenos Aires. A través del análisis de diferentes indicadores, se busca promover la adopción de políticas y medidas que contribuyan a reducir los accidentes, preservar la seguridad vial y proteger la vida de los ciudadanos.

**Nota 1**: Cada archivo KPI tiene paso a paso del proceso realizado
**Nota 2**: [Dataset adicional para hacer el KPI Reducción de accidentes](https://www.estadisticaciudad.gob.ar/eyc/?p=76599)