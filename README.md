# Grupo Hotusa - Data Analyst/Scientist test.

Tarea para candidatos que aplican a un puesto de Data Analyst/Scientist en Grupo Hotusa.

## Descripción de la tarea

El dataset (**clients_analysis.csv**) con el que trabajar contiene las siguientes columnas:
- *id_secuencial*: Id de Cliente
- *Idioma*: Idioma con el que dirigirse al cliente
- *genero*: Género del cliente
- *tratamiento*: Forma de dirigirse al cliente.
- *alta_cliente*: Fecha de alta del cliente.
- *comunicaciones_comerciales*: Si el cliente permite comunicaciones comerciales o no.
- *alta_comunicaciones*: Fecha en la que el cliente aceptó las comunicaciones comerciales.
- *nivel_fidelizacion*: Nivel en el programa de fidelización de la empresa del cliente.
- *alta_fidelizacion*: Fecha en la que el cliente se dio de alta en el programa de fidelización.
- *fecha_nacimiento*: Fecha de nacimiento del cliente.
- *mail*: Si el cliente tiene un mail informado en su ficha de cliente o no.
- *Total_Reservation*: Número total de reservas del cliente.
- *media_estancia*: Duración media de las estancias del cliente.
- *antelacion_media*: Antelación media con la que se hacen las reservas.
- *facturacion*: Total de facturación del cliente.
- *Canal_reserva*: Canal de reserva más habitual del cliente.
- *Motivo_viaje*: Motivo del viaje/Segmento.
- *ultima_reserva*: Fecha de la última reserva.
- *n_hoteles_distintos*: Número de hoteles distintos en los que se ha alojado el cliente.
- *acompanante*: Acompañante más recurrente en sus reservas.
  
Debes crear un report reproducible (en un notebook en Python o R) siguiendo estos pasos:

1. **Estandarización y limpieza**: Puedes observar que el csv está desordenado, las columnas no tienen una estándar en cuanto a la nomenclatura y los valores, en su mayoría, ni siquiera tienen un formato adecuado. Esto se debe a que se han recogido datos de varias fuentes diferentes. Desde el departamento de Marketing quieren usar esta información de manera que les sea sencillo filtrar y extraer los clientes a los que impactar en comunicaciones comerciales. ¿Qué tipo de limpieza, agrupaciones o estandarizaciones piensas que podrían hacerse? Realiza los que creas de importancia. [Ejemplo: transformar la columna 'mail' en booleano, estandarizar los nombres de las columnas a un único idioma, etc.]
2. **EDA**: ¿Existen columnas que no sean útiles? ¿Crees que podemos extraer alguna otra nueva? Propón y realiza un par de análisis que te parezcan interesantes en cuanto a los clientes.
3. **Propuesta de campañas**: Sabiendo que queremos, por un lado, agradecer a los clientes más 'top' y, por otro, llamar la atención de aquellos clientes que creemos potenciales para que sean recurrentes en un futuro, ¿cómo identificarías o segmentarías los clientes más top? ¿Y los potenciales clientes recurrentes? ¿Qué variables echas en falta para poder afinar tu segmentación? ¿Cuáles serían tus resultados?
4. **Modelo predictivo**: Al margen de las campañas de marketing, ¿qué otro tipo de valor le darías a estos datos? ¿Qué modelo predictivo podrías crear alrededor de los clientes? ¿Sabrías cómo hacerlo?

Se valorarán las explicaciones y insights que se detecten como también que las gráficas y los resultados sean fáciles de leer. No se trata de escupir los datos, sino contar una historia con ellos. Este report lo debería poder leer tanto un perfil técnico como un perfil de negocio. 

## Entrega

Entrega tus resultados en notebook o en un link al repo en GitHub a: recursos.humanos@grupohotusa.com
