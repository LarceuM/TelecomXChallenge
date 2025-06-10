# TelecomXChallenge
Ejercicio Nro. 2  ETL

## Análisis de Fuga de Clientes (Churn) - Telecomx

Este proyecto tiene como objetivo analizar los datos de clientes de **Telecomx** (una empresa de servicios de internet, telefonía y televisión por cable) para entender los factores que influyen en la **fuga de clientes (Churn)** y proponer estrategias basadas en datos para **retener a los clientes**.

## Objetivos

- Identificar patrones de comportamiento en los clientes que abandonan el servicio.
- Descubrir variables que impactan en la evasión, como métodos de pago, tipo de contrato, cantidad de servicios, etc.
- Proporcionar visualizaciones efectivas para la toma de decisiones.
- Servir como base para el desarrollo de un modelo predictivo de churn.


## Estructura del proyecto

Para este  analisis se nos entrego un archivo en formato JSON  que contenia mas de 7000 clientes tanto activos como fugados ( o dados de Baja) con informacion de sus servicios contratados , valores cobrados , y algunos datos  del cliente .

se trabajo con Python y con sus librerias : 
    matplotlib.pyplot,
    seaborn, 
    pandas,
    numpy

##  Visualizaciones incluidas

Algunos de los gráficos generados:
  .  Distribución del churn (dona)
  .  Churn vs tipo de contrato
  .  Churn vs tenure (tiempo de permanencia)
  .  Churn vs método de pago
  .  Boxplot de cargos mensuales por churn
  .  Heatmap de correlaciones
  .  Número de servicios vs churn
  .  Análisis por género, edad, dependientes y pareja

## Principales hallazgos

  .  Clientes con contratos mensuales tienen mayor probabilidad de churn.
  .  El método de pago “Electronic Check” se asocia con mayor tasa de fuga.
  .  Clientes con menos servicios contratados tienden a darse de baja más.
  .  Cargos mensuales altos también se relacionan con mayor churn.

 ## Recomendaciones estratégicas
 
  .  Incentivar contratos anuales o bianuales con promociones.
  .  Ofrecer bundles o paquetes que sumen valor (más servicios).
  .  Revisar y optimizar la experiencia de pago con “Electronic Check”.
  .  Aplicar modelos de machine learning para anticipar churn.

## Contribuciones

¡Las contribuciones son bienvenidas! Por favor abre un issue o haz un pull request si deseas mejorar el análisis o agregar nuevas visualizaciones/modelos.

 ## Contacto
Autor: Lorenzo Arceu Morla
📧 larceum@gmail.com
