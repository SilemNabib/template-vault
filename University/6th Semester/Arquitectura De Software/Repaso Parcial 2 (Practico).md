
###### 1. ¿Qué estructura de almacenamiento favorece baja latencia pero limita la escalabilidad?

> La que favorece baja latencia pero limita la escalabilidad es **NUMA (Non-Uniform Memory Access)**

***Apuntes.*** [[Modelos de Acceso a la Memoria]]

###### 2. La estructura de almacenamiento de la taxonomía de Flynn que favorece más la integridad, consistencia y acceso seguro a los datos es:

> **MISD (Multiple Instruction, Single Data)**

***Apuntes.*** [[Taxonomía de Flynn, Arquitecturas de Procesamiento]]

###### 3. Los aspectos que debe considerar un buen método (i.e., aplicable sistemáticamente) de elicitación y análisis de requerimientos para identificar los RAS y poder lograr una arquitectura de software de alta calidad, son: 

- [x] El método debe partir de la misión y los objetivos de negocio para obtener información sistemática para el proceso de elicitación.

- [x] El método debe incluir técnica(s) de elicitación que capturen expresamente los RAS.

- [x] El método debe proveer una forma de evaluación de los requerimientos que brinde sistemáticamente la guía de cómo codificar el sistema.

- [ ] El método debe proveer un lenguaje extensible y flexible de metamodelado de 4 niveles.

- [x] En el método, los requerimientos deben ser especificados en forma tal que incluyan la información necesaria para el diseño.

***Apuntes.*** [[RAS, Requerimientos de Atributos de Calidad]]

###### 4. En el método de Dorfman:   $\text{\_\_\_\_\_\_\_\_\_\_\_}$ es el proceso por el cual se descompone el sistema en subsistemas o componentes.

(NOTA: escriba una sola palabra en español que corresponde a la respuesta)

> Particionar

***Apuntes.*** [[Dorfman, Método De Análisis De Requerimientos Funcionales]]

###### 5. En el método de Dorfman: $\text{\_\_\_\_\_\_\_\_\_\_\_}$ es el proceso por el cual se refinan o re-escriben los requerimientos analizados, para establecer las responsabilidades específicas (o las funcionalidades de bajo nivel) que tienen aquellos subsistemas o componentes que fueron determinados con responsabilidad parcial para satisfacer los requerimientos considerados. 
 
(NOTA: escriba una sola palabra en español que corresponde a la respuesta)

> Asignación

***Apuntes.*** [[Dorfman, Método De Análisis De Requerimientos Funcionales]]

###### 6. A continuación, escoja el concepto que corresponde con la definición proporcionada: Capacidad del sistema de cambiar o personalizar sus componentes antes de su ejecución sin modificar su código fuente.

- [x] Configurabilidad
- [ ] Portabilidad
- [ ] Recuperabilidad
- [ ] Escalabilidad
- [ ] Disponibilidad

***Apuntes.*** [[Atributos de Calidad]]


###### 7. Capacidad del sistema de correr en múltiples plataformas.

- [ ] Configurabilidad
- [x] Portabilidad
- [ ] Recuperabilidad
- [ ] Escalabilidad
- [ ] Disponibilidad

***Apuntes.*** [[Atributos de Calidad]]

###### 8. Capacidad para recuperarse ante fallas fatales del sistema, o lidiar con datos inconsistentes o erróneos utilizando mecanismos aceptables para la organización, dentro de tiempos igualmente aceptables.

- [ ] Configurabilidad
- [ ] Portabilidad
- [x] Recuperabilidad
- [ ] Escalabilidad
- [ ] Disponibilidad

***Apuntes.*** [[Atributos de Calidad]]

###### 9. Capacidad del sistema de mantener el mismo nivel de servicio a incrementos significativos de cargas de trabajo, aumentando recursos computacionales.

- [ ] Configurabilidad
- [ ] Portabilidad
- [ ] Recuperabilidad
- [x] Escalabilidad
- [ ] Disponibilidad

***Apuntes.*** [[Atributos de Calidad]]

###### 10. Proporción de tiempo en que un sistema está presto a responder solicitudes a sus servicios (i.e., requerimientos funcionales).

- [ ] Configurabilidad
- [ ] Portabilidad
- [ ] Recuperabilidad
- [ ] Escalabilidad
- [x] Disponibilidad

***Apuntes.*** [[Atributos de Calidad]]

###### 11. Los beneficios que brinda QAW para el desarrollo de un sistema de software: Seleccione una o más de una:

- [ ] Tener un método que da soporte para las buenas prácticas y principios de implementación de diseño arquitectónico.
- [ ] Tener un método que mejora la documentación y redacción del diseño arquitectónico obtenido.
- [x] Tener un método que da soporte para la elicitación, análisis y especificación de RAS de atributos de calidad.
- [x] Tener un método que ayuda a obtener una base informada de aspectos propios del negocio que soporte decisiones arquitectónicas.
- [x] Determinar metódicamente los drivers arquitectónicos para el diseño de un sistema.

***Apuntes.*** [[QAW, Quality Attribute Workshop]]

###### 12. Requerimientos que son pertinentes para conjuntos de sistemas que comparten funcionalidades comunes.

- [ ] Operación y deployment 
- [ ] Familia de producto 
- [ ] Volumen de funcionalidad 
- [ ] Determinación de tecnología 
- [ ] Atributos de calidad

###### 13. Conjunto de requerimientos funcionales similares en su esencia, que solo al considerarse como conjunto, inciden en la arquitectura del sistema.

- [ ] Operación y deployment 
- [ ] Familia de producto 
- [ ] Volumen de funcionalidad 
- [ ] Determinación de tecnología 
- [ ] Atributos de calidad

###### 14. Requerimientos que implican el uso tecnologías específicas particulares en el desarrollo del software.

- [ ] Operación y deployment 
- [ ] Familia de producto 
- [ ] Volumen de funcionalidad 
- [ ] Determinación de tecnología 
- [ ] Atributos de calidad

###### 15. Requerimientos que implican estrategias específicas de instalación y configuración de ejecución, o formas específicas (sobre todo no convencionales) de cómo usar o interactuar con el sistema.

- [ ] Operación y deployment 
- [ ] Familia de producto 
- [ ] Volumen de funcionalidad 
- [ ] Determinación de tecnología 
- [ ] Atributos de calidad

###### 16. Características relacionadas con la percepción de qué tan bueno es un producto o proceso, o con las expectativas del mismo, que pueden llevarse a una escala cuantitativa de medición.

- [ ] Operación y deployment 
- [ ] Familia de producto 
- [ ] Volumen de funcionalidad 
- [ ] Determinación de tecnología 
- [ ] Atributos de calidad

###### 17. Marque todas las opciones que son afirmaciones ciertas para el análisis de requerimientos con el método de Dorfman: Seleccione una o más de una:

- [ ] El criterio para determinar cuándo no seguir haciendo análisis es cuando se ha terminado de agrupar, jerarquizar, y ordenar todos los requerimientos.
- [ ] La agrupación, jerarquización y ordenamiento de requerimientos se hace como parte del particionamiento del sistema en subsistemas, estableciendo qué requerimiento es padre de cuáles otros, y en qué orden estos son hijos del primero.
- [x] La agrupación, jerarquización y ordenamiento de requerimientos se hace antes del particionamiento del sistema en subsistemas, ayudando a establecer qué requerimientos están altamente relacionados, qué requerimiento debería ser padre de cuáles otros, y en qué orden (de acuerdo a algún criterio) éstos son hijos del primero.
- [ ] Dorfman permite elicitar, de manera sistemática, toda clase de requerimientos del sistema.
- [x] Dorfman es un método de análisis que permite verificar cubrimiento en anchura y en profundidad los requerimientos funcionales y subsistemas con respecto al sistema solicitado.


###### 18. Los drivers de la arquitectura de un software, según el método de QAW, son: Seleccione una o más de una:

- [x] El conjunto consistentemente satisfacibles de atributos de calidad, asociados a los escenarios de QAW, que resultan de su priorización
- [ ] El conjunto de escenarios de QAW priorizados que resultan de la subespecificación de los requerimientos arquitectónicamente significativos de volumen de funcionalidad.
- [x] Los requerimientos arquitectónicamente significativos que más influencian el análisis.
- [ ] El resultado principal y objetivo único para el que fue creado el método QAW.
- [x] El conjunto consistentemente satisfacibles de requerimientos arquitectónicamente significativos más importantes, que resultan de su priorización.

###### 19. Marque las afirmaciones que son verdaderas:

- [x] La privacidad e integridad de los datos, la confidencialidad y la identificación/autenticación son factores del atributo de calidad de seguridad.
- [x] El throughput y el missing-rate son factores que permiten medir el rendimiento (performance) de un sistema.
- [ ] La confiabilidad es la capacidad de un sistema para mantener garantizada la integridad y consistencia de sus datos.
- [ ] La escalabilidad es la capacidad de un sistema de correr en cualquier plataforma operacional.


###### 20. Empareje cada uno de las elementos del formato de escenario QAW con sus respectivas definiciones: Condición que activa o dispara la situación planteada por el escenario.

- [ ] Estímulo
- [ ] Medida de respuesta
- [ ] Respuesta
- [ ] Fuente del estímulo
- [ ] Entorno (Environment)
- [ ] Artefactos

###### 21. Unidad de medida (métrica) y respectivo valor de referencia que debe observarse en el comportamiento ideal del sistema frente al escenario.

- [ ] Estímulo
- [ ] Medida de respuesta
- [ ] Respuesta
- [ ] Fuente del estímulo
- [ ] Entorno (Environment)
- [ ] Artefactos

###### 22. Descripción de cómo debe ser el comportamiento ideal del sistema ante la ocurrencia de la situación planteada en el escenario.

- [ ] Estímulo
- [ ] Medida de respuesta
- [ ] Respuesta
- [ ] Fuente del estímulo
- [ ] Entorno (Environment)
- [ ] Artefactos

###### 23. Entidad, actor, o motivo que causa que se dispare o active la situación planteada por el escenario.

- [ ] Estímulo
- [ ] Medida de respuesta
- [ ] Respuesta
- [ ] Fuente del estímulo
- [ ] Entorno (Environment)
- [ ] Artefactos

###### 24. Contexto (relacionado con momento, lugar, circunstancia, etc.) específico en el que ocurre potencialmente la situación planteada en el escenario.

- [ ] Estímulo
- [ ] Medida de respuesta
- [ ] Respuesta
- [ ] Fuente del estímulo
- [ ] Entorno (Environment)
- [ ] Artefactos


###### 25. Elementos, partes, o componentes de la propuesta arquitectónica preliminar, que son directamente afectados por (o son responsables de) la situación problemática que plantea el escenario.

- [ ] Estímulo
- [ ] Medida de respuesta
- [ ] Respuesta
- [ ] Fuente del estímulo
- [ ] Entorno (Environment)
- [ ] Artefactos

###### 26. Ordene los pasos para obtener el diseño arquitectónico final de un sistema de software:

 - Clasificar los requerimientos.
 - Refinar la arquitectura del software funcional para que cumpla con todos los drivers de arquitectura.
 - Sintetizar una arquitectura del software para que cumpla con los requerimientos funcionales.
 - Agrupar, jerarquizar, ordenar los requerimientos funcionales.
 - Identificar requerimientos a partir de las necesidades expresadas por el cliente, teniendo en cuenta la misión de su negocio.
 - Identificar y analizar los requerimientos arquitectónicamente significativos
 - Completar los requerimientos con diversas técnicas de elicitación.
 - Aplicar Dorfman para analizar los requerimientos funcionales de producto
 - Aplicar QAW para completar la elicitación y para analizar los requerimientos de atributos de calidad.

> 1. Identificar requerimientos a partir de las necesidades expresadas por el cliente, teniendo en cuenta la misión de su negocio.
> 2. Completar los requerimientos con diversas técnicas de elicitación.
> 3. Clasificar los requerimientos.
> 4. Identificar y analizar los requerimientos arquitectónicamente significativos.
> 5. Agrupar, jerarquizar, ordenar los requerimientos funcionales.
> 6. Aplicar Dorfman para analizar los requerimientos funcionales de producto
> 7. Sintetizar una arquitectura del software para que cumpla con los requerimientos funcionales.
> 8. Aplicar QAW para completar la elicitación y para analizar los requerimientos de atributos de calidad.
> 9. Refinar la arquitectura del software funcional para que cumpla con todos los drivers de arquitectura.


###### 27. Moviendo los rectángulos a continuación, ordene los pasos para obtener los drivers definitivos de la arquitectura de software con el método QAW:

- Lluvia de ideas de escenarios de QAW
- Presentación del negocio y su misión
- Priorización de escenarios
- Consolidación de escenarios
- Presentación e introducción del método QAW
- Presentación de los diagramas de arquitectura preliminares
- Refinamiento de escenarios
- Identificación de drivers arquitectónicos potenciales

> 