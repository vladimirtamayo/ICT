# From MOOC to MAIC

## Keywords

- Massive AI-empowered Course
- Intelligent tutoring
- AI-augmented classroom

## Introduction

- Teaching in accordance with individual aptitudes
- Intelligent agents (What was the framework?)
> [!tip] MAIC is conceived as an evolution of MOCC, my idea aims to improve the classroom
- 

# Congnitive Modeling and Intelligent Tutoring
[PDF](./Cognitive_Modeling_and_Intelligent_Tutoring.pdf)

## Ideas

- Los tutores individuales/particulares tienen una gran efectividad a la hora de llevar al estudiante por una camino que garantice la apropiación de conocimiento. [p1]
- La única forma de comprobar la suficiencia de la teoría ACT es comprobar a apropiación de conocimientos complejos por parte de grandes poblaciones de estudiantes. [p1]
- Modelo de desempeño (Performance model): Es un conjunto de reglas correctas o incorrectas para desarrollar una habilidad.
- Modelo de seguimiento (Model tracing): Compara las reglas con las reglas del modelo para intentar seguir en tiempo real los estados cognitivos por los que pasa el estudiante durante la resolución del problema.
- Modelo de aprendizaje (Learning model): Es un conjunto de suposiciones acerca de como cambia el estado de conocimiento del estudiante después de cada paso en la resolución del problema.
- Seguimiento de conocimiento (Knowledge tracing): Rastrea los cambios en el conocimiento del estudiante a medida que resuelve problemas. Lo que se obtiene de este seguimiento sirve para desambiguar interpretaciones den el modelo de seguimiento y puede ser usado para seleccionar mejores problemas y optimizar el proceso de aprendizaje (¿se podría usar RL?)
- PUPS (PenUltimate production system)

- **Teoría cognitiva**

  - Es la teoría en la que se basan los AI-tutores del artículo
  - Los autores asumen que si su teoría es correcta los AI-tutores optimizan el proceso de aprendizaje
  - Conocimiento declarativo (Declarative knowledge): Instrucciones, lecturas, etc. es conocimiento sin saber como se usará
  - Conocimiento procedimental (Procedural knowlendge): es el conocimiento adquirido después de usar el conocimiento declarativo

    - **Producciones**

      En ACT y PUPS el conocimiento procedimental se representa como un conjunto de reglas de producción que definen una habilidad. La idea central es producir experiencias que le permitan al estudiante adquirir reglas de producción que debería poseer alguien que puede resolver problemas en ese campo por ejemplo:

      ```bash
      IF meta = "Resolver un sistema de ecuaciones mediante la reducción de Gauss-Jordan"
      THEN acciones = "1. Multiplicar o dividir un renglón por un número diferente de cero, 2. Sumar ..."
      ```

      La idea se centra en la descomposición de una meta en metas mas pequeñas que si se cumplen se entiende que el estudiante tiene dominio sobre el tema. Debe haber un prospecto de estudiante para que el tutor pueda ser efectivo ya que por ejemplo en el caso de reducción Gauss-Jordan por lo menos debe saberse lo que es una matriz o una ecuación es decir, se deben definir un conjunto de características mínimas que un estudiante debe tener a la hora de usar el tutor. Esta teoría predice que diferentes dominios del conocimiento implican una diferente organización de las reglas de producción. Un buen tutor es aquel que comunica la mejor estructura de resolución de problemas para un dominio específico.

    - **Conocimiento declarativo: Estructuras PUPS**
      Estructuras tipo esquema que se caracterizan por tener slots especiales que resultan fundamentales para aplicarlo en la interpretación de la resolución de problemas. 

      Aún con una buena instrucción los estudiantes cometen errores a la hora de resolver problemas por esto, es tarea de los tutores irlos corrigiendo a medida que van apareciendo.

    - **Uso Interpretativo del conocimiento declarativo**
      Se generan dos ciclos de ineficiencia:
      1. La búsqueda de las operaciones que el estudiante conoce para poder encontrar el siguiente paso mas adecuado.
      2. La aplicación por analogía de la representación declarativa de la estructura PUPS
      La aplicación por analogía es costosa en términos de la cantidad de datos que se deben mantener en memoria 
      
      **Analogía**
      Si se tiene un ejemplo de resolución de una problema del tipo:
      función 1 -> resultado 1 => función 2 -> resultado 2
      No es una solución óptima porque es costoso computar el mapeo y porque solo funciona si hay ejemplos.
    
    - **Compilación de conocimiento**
      





## Key concepts

- ATC
- PUPS
- Declarative knowledge
- Procedural knowledge

