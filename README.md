# Taller / Evaluación — Bases de Datos Vectoriales

### Objetivo

La evaluación busca medir los conocimientos del estudiante en:

* Bases de datos de grafos.
* Bases de datos vectoriales.

### Modalidad

La evaluación es:

* presencial
* individual
* escrita en papel

El estudiante podrá:

* ejecutar código localmente
* usar Jupyter Notebook
* usar Neo4J
* usar VSCode
* ejecutar scripts Python
* realizar pruebas y debugging

Pero:

### TODAS las respuestas deben escribirse manualmente en papel

No se entregará código digital.

### Material entregado

Cada estudiante recibirá:

### Documento impreso del examen

Incluye:

* espaco para el nombre
* espacio para firma
* dataset inicial
* hoja base del sistema
* preguntas aleatorias
* espacio para responder manualmente

### Sistema base inicial

El sistema entregado incluye:

* dataset de neo4j
* modelo SentenceTransformer
* función `embedding()`
* construcción de índice FAISS
* función `buscar()`
* score semántico
* búsqueda filtrada
* clase `BuscadorSemantico`

Los estudiantes NO deben memorizar esta arquitectura.

El objetivo es:

* entenderla
* modificarla
* extenderla
* analizar su comportamiento

### Distribución de preguntas

Cada examen tendrá:

| Nivel    | Cantidad |  Puntaje cada una |
| ---------- | ---------- | ---------- |
| Medio    | 6        | 1        |
| Difícil | 2        | 2       |

Total:

### 8 preguntas - 10 puntos

Las preguntas fueron seleccionadas aleatoriamente desde el banco de ejercicios.

### Recomendaciones

Se recomienda:

* ejecutar el código paso a paso
* probar queries pequeñas
* imprimir resultados intermedios
* observar distancias y scores
* analizar el ranking semántico
* verificar cómo cambia el embedding según el contexto

### Restricciones

Durante la evaluación:

* NO se utilizará internet
* NO se utilizarán APIs externas
* NO se utilizarán servicios cloud
* NO se utilizarán modelos remotos

Todo debe ejecutarse localmente usando:

* Python
* numpy
* FAISS
* sentence-transformers

### Tecnologías permitidas

* Python 3.x
* Jupyter Notebook
* VSCode
* Scripts `.py`
* Librerías instaladas previamente

### Criterios de evaluación

Se evaluará principalmente:

* Sintaxys y funcionalidad de Cypher
* comprensión operativa
* interpretación semántica
* modificación correcta del sistema
* análisis de resultados
* comprensión del comportamiento vectorial

No se evaluará:

* memorización teórica
* sintaxis compleja de Python
* matemáticas avanzadas
* implementación interna de LLMs

