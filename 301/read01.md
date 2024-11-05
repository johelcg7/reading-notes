# READ 01: Introducción a React y los Componentes

## Component-Based Architecture

### ¿Qué es un “componente”?
En React, un componente es una pieza reutilizable y autoconstruida de código que representa una parte de la interfaz de usuario (UI). Los componentes pueden ser considerados como las "bloques de construcción" de una aplicación React. Cada componente puede tener su propio estado y propiedades, y se encarga de renderizar una parte específica de la UI.

Los componentes pueden recibir props (propiedades) que les permiten recibir datos de otros componentes y pueden gestionar su propio estado interno. Además, pueden ser anidados dentro de otros componentes, lo que permite construir interfaces de usuario complejas de manera modular y mantenible.

### ¿Cuáles son las características de un componente?

+ Reutilización : los componentes suelen estar diseñados para reutilizarse en distintas situaciones y aplicaciones. Sin embargo, algunos componentes pueden estar diseñados para una tarea específica.

+ Reemplazable − Los componentes pueden sustituirse libremente por otros componentes similares.

+ No específico del contexto : los componentes están diseñados para funcionar en diferentes entornos y contextos.

+ Extensible : un componente se puede ampliar a partir de componentes existentes para proporcionar un nuevo comportamiento.

+ Encapsulado : el componente AA representa las interfaces que permiten al llamador utilizar su funcionalidad y no expone detalles de los procesos internos ni de ninguna variable o estado interno.

+ Independiente : los componentes están diseñados para tener dependencias mínimas de otros componentes.

### ¿Cuáles son las ventajas de utilizar una arquitectura basada en componentes?

+ Facilidad de implementación : a medida que aparecen nuevas versiones compatibles, es más fácil reemplazar las versiones existentes sin afectar a los demás componentes ni al sistema en su totalidad.

+ Costo reducido : el uso de componentes de terceros le permite distribuir el costo de desarrollo y mantenimiento.

+ Facilidad de desarrollo : los componentes implementan interfaces conocidas para proporcionar una funcionalidad definida, lo que permite el desarrollo sin afectar otras partes del sistema.

+ Reutilizable : el uso de componentes reutilizables significa que pueden emplearse para distribuir el costo de desarrollo y mantenimiento entre varias aplicaciones o sistemas.

+ Modificación de la complejidad técnica : un componente modifica la complejidad mediante el uso de un contenedor de componentes y sus servicios.

+ Confiabilidad : la confiabilidad general del sistema aumenta porque la confiabilidad de cada componente individual mejora la confiabilidad de todo el sistema a través de la reutilización.

+ Mantenimiento y evolución del sistema : Fácil de cambiar y actualizar la implementación sin afectar al resto del sistema.

+ Independiente − Independencia y conectividad flexible de componentes. Desarrollo independiente de componentes por parte de diferentes grupos en paralelo. Productividad para el desarrollo de software y el desarrollo de software futuro.


## What is Props and How to Use it in React

### ¿Qué significa “props”?

Es una abreviación de la palabra "propiedades", que se usa en React para pasar datos y valores de un componente a otro para obtener resultados dinámicos y únicos.

### ¿Cómo se utilizan los props en React?

Antes de profundizar más, es importante tener en cuenta que React utiliza un flujo de datos unidireccional. Esto significa que los datos solo se pueden transferir desde el componente principal a los componentes secundarios. Además, el componente secundario no puede modificar todos los datos que se transfieren desde el componente principal.

### ¿Cuál es el flujo de los props?

+ Se crea un componente padre y un componente hijo.
+ Por medio de "export" e "import" se enlazan los dos componentes.
+ En el componente padre se ponen las propiedades en la etiqueta correspondiente, que luego desde el componente hijo se enlaza a los props.
+ Se pueden reutilizar el componente hijo a cualquier otro componente padre.
