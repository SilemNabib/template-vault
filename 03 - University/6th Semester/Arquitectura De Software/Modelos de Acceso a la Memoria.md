Se refieren a cómo los sistemas multiprocesadores organizan la memoria y permiten que múltiples procesadores accedan a ella. La forma en que los procesadores acceden a la memoria afecta la latencia y la escalabilidad del sistema.

## UMA (Uniform Memory Access)

Todos los procesadores tienen acceso **uniforme** a una memoria compartida, es decir, el tiempo que tarda cualquier procesador en acceder a cualquier dirección de memoria es siempre el mismo.

#### Características

- **Acceso uniforme**: Todos los procesadores tienen el mismo tiempo de acceso a cualquier parte de la memoria.
- **Memoria compartida**: Existe un único bloque de memoria accesible por todos los procesadores, a través de un bus o un sistema de interconexión centralizado.
- **Facilidad de programación**: Es más fácil de programar porque no hay necesidad de preocuparse de qué procesador accede a qué parte de la memoria.
- **Limitaciones de escalabilidad**: A medida que se añaden más procesadores, el bus compartido puede convertirse en un cuello de botella, ya que todos los procesadores compiten por el acceso a la misma memoria.

#### Ejemplo

- **Sistemas SMP (Symmetric Multiprocessing)**.

![[diagram-20241017(1).png#invert]]

#### Ventajas

- Sencillo de implementar.
- Ideal para un número reducido de procesadores.

#### Desventajas

- **Cuello de botella**: A medida que se agregan más procesadores, el acceso compartido a la memoria se vuelve un problema.
- Menor escalabilidad.

## NUMA (Non-Uniform Memory Access)
el acceso a la memoria no es uniforme. La memoria está dividida en varios "nodos" de memoria local, y cada procesador tiene una porción de memoria que puede acceder rápidamente (memoria local). Sin embargo, también puede acceder a la memoria de otros nodos, pero con una mayor latencia.

#### Características

- **Memoria distribuida**: La memoria se divide en nodos, cada uno asociado a un conjunto de procesadores.
- **Acceso no uniforme**: Los procesadores acceden rápidamente a la memoria de su nodo (memoria local) y más lentamente a la memoria de otros nodos (memoria remota).
- **Optimización**: Las aplicaciones deben estar optimizadas para intentar mantener el acceso a la memoria local y minimizar el acceso a memoria remota para evitar mayores tiempos de acceso.

#### Ejemplo

- **Sistemas multiprocesador avanzados**, como algunos sistemas de servidores de alto rendimiento.

![[03 - University/6th Semester/Arquitectura De Software/attachments/diagram-20241017.png#invert]]

#### Ventajas

- **Escalabilidad mejorada**: Escala mejor que UMA porque distribuye la carga de la memoria entre los nodos.
- Mejora el rendimiento local de memoria.

#### Desventajas

- **Latencia variable**: Acceder a la memoria remota es más lento.
- Requiere mayor complejidad en la programación para optimizar el acceso a la memoria.

## NORMA (No Remote Memory Access)

Cada procesador tiene su propia memoria local, y no hay acceso directo a la memoria de otros procesadores. Si un procesador necesita datos que están en la memoria de otro procesador, esos datos deben ser transferidos explícitamente a través de un mecanismo de comunicación (como mensajes).

#### Características:

- **Memoria privada**: Cada procesador tiene su propia memoria local que no puede ser accedida directamente por otros procesadores.
- **Comunicación explícita**: Los procesadores deben intercambiar datos utilizando un sistema de paso de mensajes o interconexión de red.
- **Escalabilidad alta**: Debido a que los procesadores no compiten por el acceso a la misma memoria, NORMA escala mejor en sistemas de gran tamaño.

#### Ejemplo:

- **Clusters de computadoras** o **sistemas distribuidos**.

#### Ventajas:

- **Alta escalabilidad**: Puede crecer indefinidamente sin un cuello de botella de memoria compartida.
- Reduce los conflictos por acceso a la memoria.

#### Desventajas:

- **Mayor latencia para la comunicación entre nodos**: Los procesadores no pueden acceder a la memoria de otros, lo que puede resultar en mayores tiempos de espera si necesitan datos que no están localmente disponibles.
- Complejidad en la programación, ya que los programadores deben gestionar explícitamente la transferencia de datos entre procesadores.