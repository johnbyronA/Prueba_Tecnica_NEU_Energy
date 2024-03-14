# Prueba Técnica para NEU Energy

Este repositorio alberga la solución a una prueba técnica diseñada específicamente para NEU Energy. La prueba abarca el análisis y procesamiento de datos, el almacenamiento eficiente de información y el desarrollo de una interfaz web para interactuar con los datos procesados. El objetivo central es demostrar habilidades en el manejo de datos, programación y desarrollo web, aplicando estos conocimientos a un escenario práctico y relevante para el sector energético.

## Descripción General

El desafío principal de esta prueba técnica es trabajar con un conjunto de datos numéricos para identificar subconjuntos cuya suma de elementos sea igual a un valor objetivo predeterminado (52). Este problema, conocido por su complejidad computacional, se aborda mediante un enfoque de programación eficiente que utiliza algoritmos de backtracking para explorar todas las combinaciones posibles de forma sistemática, asegurando que cada número se utilice de manera óptima y sin repeticiones innecesarias entre los subconjuntos válidos.

Una vez identificados, estos subconjuntos se almacenan en una base de datos SQLite, una solución ligera y eficaz para la persistencia de datos. Cada subconjunto se asocia con un identificador único, facilitando su recuperación y consulta posterior.

La interacción con los datos almacenados se realiza a través de una aplicación web desarrollada con Flask, un microframework para Python que permite crear interfaces web de forma rápida y con pocas líneas de código. Esta aplicación actúa como una capa de presentación, permitiendo a los usuarios consultar subconjuntos específicos a través de una interfaz sencilla y amigable.

## Características

- **Análisis de Datos**: La solución comienza con un profundo análisis de los datos proporcionados, identificando patrones y estrategias para optimizar la búsqueda de subconjuntos. Este análisis preliminar es crucial para diseñar un algoritmo eficiente que pueda manejar la complejidad del problema planteado.

- **Generación de Subconjuntos**: Se implementa una solución algorítmica para encontrar todos los posibles subconjuntos de números que sumen el valor objetivo. Este proceso no solo demuestra habilidades en la resolución de problemas y algoritmia, sino que también resalta la importancia de optimizar el rendimiento computacional mediante técnicas de programación avanzadas.

- **Almacenamiento Eficiente**: La elección de SQLite como sistema de gestión de base de datos refleja una preferencia por soluciones ligeras pero poderosas. Se presta especial atención a la estructura de la base de datos para asegurar un almacenamiento eficiente de los subconjuntos y un acceso rápido durante las consultas.

- **Interfaz Web Intuitiva**: La aplicación web desarrollada con Flask proporciona una interfaz de usuario clara y directa, permitiendo consultas basadas en identificadores únicos. Esta interfaz no solo mejora la accesibilidad de los datos, sino que también demuestra cómo las soluciones backend pueden integrarse con frontend para crear aplicaciones completas y funcionales.

## Tecnologías Utilizadas

La prueba técnica hace uso de varias tecnologías y herramientas, seleccionadas cuidadosamente para abordar los diferentes aspectos del desafío:

- **Python 3**: Lenguaje de programación principal, elegido por su claridad sintáctica y la amplia disponibilidad de bibliotecas para el procesamiento de datos y el desarrollo web.
- **SQLite**: Sistema de gestión de bases de datos elegido por su simplicidad, ligereza y la capacidad de manejar eficientemente las operaciones de almacenamiento y consulta requeridas por la aplicación.
- **Flask**: Microframework para el desarrollo de aplicaciones web en Python, utilizado para implementar la interfaz de usuario que facilita la consulta de subconjuntos.
- **CSV**: Formato de archivo utilizado para la exportación de datos, permitiendo una fácil integración con otras herramientas y sistemas de análisis de datos.


## Conclusión

El proyecto se diseñó con el propósito de demostrar mis competencias técnicas clave en el análisis de datos, el desarrollo de software y la ingeniería de sistemas, áreas todas críticas para el avance de soluciones innovadoras en el sector energético. La capacidad de analizar y sintetizar datos complejos es esencial para identificar patrones de consumo, optimizar la distribución de recursos y prever tendencias futuras en el consumo energético. 

