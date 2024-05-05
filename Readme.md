# Proyecto integrador 2

#### Introducción
En este trabajo integrador el objetivo es analizar las operaciones de un Call Center de un Banco, para proponer mejoras en:
* Eficiencia operativa, proponiendo mejoras operativas.
* Mejorar la satisfacción del cliente, cumpliendo los SLA comprometidos.
* Brindar una herramienta para la gestión y la toma de decisiones a los managers del Call Center.

  A la hora de analizar nos basaremos en las siguientes preguntas:
  
* ¿Cuál es el nivel de servicio para los clientes Prioritarios? 1
* ¿Damos un mejor servicio que a los clientes normales? 1
* ¿Qué volumen de llamadas atendemos? 2
* ¿Cuáles son los cuellos de botella? ¿En qué días? ¿En qué bandas horarias? 2
* ¿Cómo es la eficiencia y productividad de nuestros agentes? 3
* ¿Hay clientes recurrentes en el uso del servicio? 4
* ¿Cuáles son los tipos de servicio más recurrentes?4
* ¿Podemos estimar la dotación necesaria para cumplir con una calidad de servicio determinada?  Ejemplo: si quiero que mi tiempo promedio de espera sea menor a 60 segundos?

  Este trabajo fue realizado integramente con Power Bi para poder aplicar todo lo aprendido en el M5.

  ## 1º Limpieza y validación de los datos

  En primer lugar se comienza con una limpieza de los datos para tener los mismos en la forma más conveniente para poder trabajar de manera eficaz y eficiente, además de descomponer algunas columnas codificadas y crear una tabla calendario.
  No se ahonda mucho en esta parte ya que la lista de  transformaciones está en Power Query dentro de Power BI.

  ## Conclusiones
  En cuanto al trato respecto entre los clientes prioritarios y los de alta prioridad debemos comparar 3 etapas de la atención del callcenter.

  En primer lugar, en el tiempo medio que pasan en el VRU tanto entre ambos tipos de clientes no hay diferencias significativas.
  
  En el tiempo medio por que pasan los clientes en la fila de espera para ser atendidos lo clientes de alta prioridad tiene una media de 86,8 segundos mientras que los de prioridad regular tienen una media de 98,55 segundos lo que implica que los de lata prioridad tiene un timpo de cola de 11,9% menor que los de prioridad regular.
  
  En el tiempo del servicio por el agente los clientes de prioridad regular tienen un tiempo medio de 128,13 segundos mientras que los de alta prioridad 178,99 segundos. Entonces el el tiempo en servicio de los clientes de alta prioridad 39,7% mayor que los de prioridad regular.

  Entonces al analizar estos datos podemos ver como no hay una diferencia significativa en los timempos medios de VRU y en cola entre clientes regulares y de alta prioridad, e incluso en el tiempo medio de servicio es mas alto en los clientes de alta prioridad. Por lo que no se esta cunmpliendo con ell objetivo de darle un mejor servicio a un cliente con alta prioridad que paga un fee mensual.
