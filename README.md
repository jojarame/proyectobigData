# proyectobigData

En este proyecto para la materia Tópicos Especiales en Telemática haremos análisis de los datos de COVID 19 para Colombia.

Usaremos la insfraestructura de AWS (EMR, S3, Glue y Athena) para la parte de ingesta y procesamiento y PowerBI para la parte de visualización de la data procesada.

La ingesta de datos se hace de forma automática en el cluster con el uso de un crontab, desde donde crearemos un cronjob que permita hacer la ingesta con una periodicidad determinada.

En el documento adjunto se encuentra toda la información relacionada, así como los pasos a seguir para la creación del sistema.
