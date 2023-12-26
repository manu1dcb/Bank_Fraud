# EDA Dataset

Componentes: 
Gaspar Cólogan Barajas
- Email: gaspar.cologan@cunef.edu
- Ruta Repositorio: https://github.com/GasparCologan/Bank_Fraud

José Manuel de Castro Beristain
- Email: josemanuel.decastro@cunef.edu
- Ruta Repositorio: https://github.com/manu1dcb/Bank_Fraud

Objetivo: 
Este proyecto tiene como objetivo examinar y prevenir el fraude bancario mediante el análisis de una solicitud de apertura de cuenta bancaria a partir de un conjunto de datos anonimizado.
Para ello, hemos realizado un análisis exploratorio de los datos, selección e ingeniería de variables, modelo base, selección del modelo final, optimización de hiperparámetros, evaluación del modelo y finalizado con la explicabilidad. 

El conjunto de datos fue elaborado por Sérgio Jesus, José Pombal, Duarte Alves, André F. Cruz, Pedro Saleiro y Pedro Bizarro. Consta de seis conjuntos de datos, pero en esta investigación nos enfocaremos exclusivamente en el conjunto de datos "base", el cual fue seleccionado debido a la ausencia de sesgo en el proceso de muestreo.

Cada instancia en estos conjuntos de datos simula una aplicación sintética para la apertura de una cuenta bancaria, generada mediante un modelo CTGAN entrenado con datos bancarios reales anonimizados, utilizado para la detección de fraudes en solicitudes de apertura de cuentas. La información original se obtuvo con el consentimiento del usuario durante el proceso de solicitud. No se llevaron a cabo revisiones éticas y la recopilación de datos no se realizó directamente de los individuos, sino mediante el muestreo de un modelo CTGAN.

La asignación de etiquetas se efectúa a través del campo "fraud_bool", donde un valor positivo (fraud_bool=1) indica una solicitud fraudulenta, mientras que un valor negativo (fraud_bool=0) indica una solicitud legítima. Cabe destacar que el conjunto de datos enfrenta desafíos en la selección de etiquetas debido a restricciones regulatorias y comerciales, las cuales limitan el tipo de clientes que algunos bancos pueden aceptar y generan una pequeña selección sesgada.

Conclusión: 
En este trabajo hemos encontrado la forma de hallar con unos datos que, creemos, no son de una gran calidad, un modelo mediante el cual podemos ordenar por probabilidades la posibilidad de que los clientes de una entidad bancaria cometan fraude.
Hemos erradicado el 46% del fraude bancario investigando solo al 3,8% de nuestra clientela.