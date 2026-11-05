# Reflexion

### El script está diseñado para medir con cronómetro (time.perf_counter) y báscula (len(r.content)) quién gana: si ir de compras 10 veces por separado (REST) o hacer un súper pedido express (GraphQL).

### Divide las tareas en funciones limpias (consumir_rest y consumir_graphql) y al final arroja una comparativa directa en la consola para ver qué arquitectura choca menos contra el tiempo y el uso de datos.

### En pocas palabras este código es una prueba de rendimiento en vivo para demostrar por qué losBackend y los desarrolladores aman GraphQL cuando tienen que pedir un montón de cosas juntas sin saturar la red.