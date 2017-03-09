# Monitor de sistema

Fecha de entrega: 23.03.2017

El primer proyecto es programar un monitor de recursos del sistema
operativo (de los recursos que juzguen útiles, interesantes, o que
decidan por la razón que sea), pero con la particularidad o requisito
de que /debe trabajar/ de forma concurrente, sincronizando multihilos,
multiprocesos o ambos. Empleen los mecanismos de sincronización que
consideren adecuados.

La calificación de este proyecto se guiará por los siguientes criterios:

|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|------|
|                        | **Excelente** (100%)                                                                                                                                                                                                                                                    | **Bueno**  (75%)                                                                                                                                                        | **Suficiente** (50%)                                                                                                                                                | **Insuficiente** (0%)                                                                                                         | Peso |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|------|
| **Requisitos**           |                                                                                                                                                                                                                                                                       |                                                                                                                                                                       |                                                                                                                                                                   |                                                                                                                             |  20% |
| Cumplimiento           | Se cumplen los requisitos planteados al 100% e incluso se exceden                                                                                                                                                                                                     | Los requisitos planteados se cumplen a cabalidad                                                                                                                      | El proyecto se aproxima a los requisitos, sin llegar a cumplirlos por completo                                                                                    | El proyecto presentado no tiene relación con lo solicitado en clase                                                         |      |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|------|
| **Proyecto**             |                                                                                                                                                                                                                                                                       |                                                                                                                                                                       |                                                                                                                                                                   |                                                                                                                             |  20% |
| Creatividad            | El problema abordado es novedoso, o la manera en que aborda la necesidad es notoriamente original                                                                                                                                                                     | Resuelve una necesidad ampliamente conocida, pero de forma original/interesante                                                                                       | Emplea mecanismos y fuentes de datos conocidas para resolver un problema ampliamente conocido                                                                     |                                                                                                                             |      |
| Complejidad            | Combina datos de varias fuentes para brindar un panorama no obvio.                                                                                                                                                                                                    |                                                                                                                                                                       | Presenta directamente la información obtenida de una fuente sin aplicar procesamiento alguno.                                                                     |                                                                                                                             |      |
| Interfaz usuario       | Logra una interfaz usuario atractiva, consistente y clara, con la explicación necesaria para un uso natural y fluido                                                                                                                                                  | La interfaz usuario muestra trabajo, pero requiere consultar la documentación para comprender el uso.                                                                 | La interfaz usuario es suficiente para presentar los datos generados, pero su uso requiere comprender el código fuente.                                           | El programa es imposible de utilizar exitosamente sin conocer la implementación detalladamente                              |      |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|------|
| **Documentación**        |                                                                                                                                                                                                                                                                       |                                                                                                                                                                       |                                                                                                                                                                   |                                                                                                                             |  20% |
| Documentación externa  | Incluye una sección de presentación con, por lo menos: Nombres de los participantes del equipo, problema que busca resolver, lógica de operación (cómo lo resuelve), y ejemplos de uso o invocación                                                                   | Incluye tres de los puntos mencionados                                                                                                                                | Incluye dos de los puntos mencionados                                                                                                                             | No incluye documentación del proyecto.                                                                                      |      |
| Entorno y dependencias | Detalla el entorno para el cual el programa fue escrito, detallando según sea pertinente lenguaje (incluyendo la implementación y versiones mayores), principales módulos que deben ser instalados (con sus respectivas versiones), y demás instrucciones pertinentes |                                                                                                                                                                       | Indica los principales componentes requeridos para la construcción y ejecución del proyecto, pero omite detalles importantes que dificultan su exitosa ejecución. |                                                                                                                             |      |
| Comentarios            | El código está comentado donde hace falta, no repite información obvia. Los comentarios ayudan a comprender la lógica, no la implementación.                                                                                                                          | El código está comentado donde hace falta, pero los comentarios son excesivos: Además de la lógica general, mencionan lo obvio.                                       | Hay algunos comentarios útiles en el programa, pero falta mucho para que ayude a una buena comprensión.                                                           | No hay comentarios.                                                                                                         |      |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|------|
| **Entrega**              |                                                                                                                                                                                                                                                                       |                                                                                                                                                                       |                                                                                                                                                                   |                                                                                                                             |  20% |
| Historia en Git        | El proyecto consta de un mínimo de cinco commits, con información suficientemente descriptiva para comprender el proceso de desarrollo                                                                                                                                | Consta de un mínimo de cinco /commits/, pero no presentan un título/comentario suficiente para entender el proceso de desarrollo                                      | La entrega consta de un sólo /commit/, no permite entender el proceso de desarrollo del proyecto                                                                  | No entregó usando Git                                                                                                       |      |
| Directorio de proyecto | El trabajo entregado consta exclusivamente del código fuente y la documentación, en una estructura acorde para su construcción/compilación, evaluación y uso directo; en caso de requerirlo, un =.gitignore= mantiene limpio el directorio al compilar.               | Sólo el código fuente y la documentación forman parte de los /commits/, pero construir / ejecutar el código /ensucia/ al repositorio (¿debería manejar =.gitignore=?) | El trabajo entregado incluye archivos innecesarios (como archivos objeto ya compilados o subdirectorios generados por el entorno de desarrollo empleado)          | No entregó usando Git                                                                                                       |      |
| Código válido          | Al ejecutar las instrucciones documentadas, el código puede ejecutarse exitosamente al primer intento.                                                                                                                                                                | Las instrucciones que forman parte de la documentación tienen que adecuarse para poder ejecutar el código, o hay errores menores que corregir para que funcione.      | No está documentado cómo ejecutar el código, o hay errores mayores que corregir para poder ejecutarlo.                                                            | Resultó imposible probar la ejecución.                                                                                      |      |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|------|
| **Legibilidad**          |                                                                                                                                                                                                                                                                       |                                                                                                                                                                       |                                                                                                                                                                   |                                                                                                                             |  20% |
| Estructura             | El código está bien organizado y emplea un estilo de indentación de forma consistente.                                                                                                                                                                                | El código está mayormente indentado; hay inconsistencias menores.                                                                                                     | Falta claridad en los bloques por no emplear indentación o hacerlo de forma absolutamente inconsistente.                                                          |                                                                                                                             |      |
| Nomenclatura           | Los nombres de los símbolos (variables, funciones, métodos, clases) son claros y acorde a su función; los principales elementos están documentados expresamente.                                                                                                      | Los nombres de los símbolos mencionados son claros y acorde a su función, aunque no estén documentados.                                                               | Los nombres de los símbolos no son claros, pero su uso y significado forma parte de la documentación.                                                             | Cuesta trabajo seguir la lógica; los símbolos empleados no tienen nombres significativos, y su función no está documentada. |      |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|------|

El proyecto se puede desarrollar en forma individual o en equipos de
dos personas, y su peso en la calificación será
[equivalente a un examen parcial](http://sistop.gwolf.org/generalidades.html#org9c51f5e).