[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Z6NE2ogx)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=16551446&assignment_repo_type=AssignmentRepo)
# Práctica 1: Introducción al desarrollo. Reflexiones.

Apoyate en los siguientes recursos para realizar la práctica:

[Descripción de la práctica](https://revilofe.github.io/section3/u01/practica/EDES-U1.-Practica010/)


---

# Título de la Actividad

## Identificación de la Actividad
- **ID de la Actividad:** [Reflexiones]
- **Módulo:** [EDES] (`PROG`, `IS`, `EDES`, etc.)
- **Unidad de Trabajo:** [1,1]
- **Fecha de Creación:** [15/10/2024]
- **Fecha de Entrega:** [Fecha de entrega]
- **Alumno(s):** 
  - **Nombre y Apellidos:** [Samuel Sánchez López]
  - **Correo electrónico:** [ssanlop2806@g.educaand.es]
  - **Iniciales del Alumno/Grupo:** [S]

## Descripción de la Actividad
[Descripción detallada de la actividad, objetivos, y contexto necesario para comprenderla. Explicar en qué consiste la actividad y qué se espera que el alumno desarrolle o implemente.]

## Instrucciones de Compilación y Ejecución
1. **Requisitos Previos:**
   - [Lenguaje de programación y versión]
   - [Entorno de desarrollo o dependencias necesarias]

2. **Pasos para Compilar el Código:**
   ```bash
   [Comando para compilar el código]
   ```

3. **Pasos para Ejecutar el Código:**
   ```bash
   [Comando para ejecutar la aplicación]
   ```

4. **Ejecución de Pruebas:**
   ```bash
   [Comandos para ejecutar pruebas, si las hubiera]
   ```

## Desarrollo de la Actividad
### Descripción del Desarrollo
[Explicación de cómo se ha abordado el desarrollo de la actividad, incluyendo las decisiones de diseño, estructura del código y enfoque de resolución de problemas. Se recomienda adjuntar diagramas o capturas de pantalla si es necesario.]

### Código Fuente
[Aquí se incluirá un enlace directo a los archivos de código fuente en el repositorio, por ejemplo, si se está usando GitHub: `src/main.java` o algún enlace directo.]

### Ejemplos de Ejecución
- **Entrada 1:** Descripción de la entrada y valor de prueba.
- **Salida Esperada 1:** Explicación de la salida esperada y el resultado de la prueba.

### Resultados de Pruebas
[Aquí se detallará cómo se ha verificado la funcionalidad del código, incluyendo resultados de pruebas automatizadas o manuales, en caso de que las haya.]

## Documentación Adicional
- **Manual de Usuario:** [Enlace a la documentación del usuario, si existe]
- **Autorización de Permisos:** Verificar que el profesor tenga permisos de lectura en el repositorio para revisar el código.

## Conclusiones
[Resumen de las conclusiones alcanzadas al desarrollar la actividad, las lecciones aprendidas, y posibles mejoras que se puedan implementar en futuras entregas.]

## Referencias y Fuentes
[Aquí se listarán las fuentes consultadas para el desarrollo de la actividad, tales como documentación oficial, artículos, o cualquier recurso externo relevante.]

### Notas Adicionales:
1. **Nombres de Archivos y Repositorios:**
   - Asegúrate de que el nombre del archivo o repositorio siga la estructura definida: `XXX-idActividad-Iniciales`.
2. **Permisos:**
   - Verifica que el profesor tenga los permisos necesarios para acceder al repositorio o documento.
3. **Formato:**
   - Si se entrega en formato PDF o Google Docs, asegúrate de cumplir con el mínimo y máximo de folios establecidos.
4. **Compilación y Ejecución:**
   - Detalla claramente cómo compilar y ejecutar el código, incluyendo las instrucciones en el archivo `README.md`.



P 1.10: Reflexión y discusión sobre los resultados¶
1. Relación software y hardware¶
1.1. Primera parte¶
1.1.1. ¿Cómo se ejecuta el código en el procesador?ç

Pues el procesador recibe instrucciones del programa en el que calcula los cambios necesarios para que funcione.

1.1.2. ¿Qué hace la memoria RAM con la información del botón o el LED?

La RAM almacena información temporalmente junto a las instrucciones que se le da al funcionamiento del LED

1.1.3. ¿Cómo se comunican los periféricos (botón y LED) con el procesador?
Se comunican con el sistema de entrada/salida del procesador.

1.2. Segunda parte¶
1.2.1. ¿Cómo interactúan el procesador, la memoria y los periféricos en la ejecución del programa?

Pues el procesador lanza algunas instrucciones del programa y utiliza la memoria para almacenar datos temporales pero cuando necesita información, la busca en la memoria si no esta disponible puede acceder a los periféricos.

1.2.2. ¿Qué pasa con los datos en la memoria cuando el programa se ejecuta?

Se guarda los datos en alguna celda de memoria hasta la finalización del mismo

1.2.3. ¿Qué roles juegan las instrucciones del software en esta interacción?

Guían al procesador en las operaciones que tienen que hacer

1.2.4. ¿Cómo se relaciona esta simulación con lo que ocurre en un ordenador real?

Muestra como interactúa el procesador, la memoriay los periféricos.

2. Del código fuente al ejecutable¶
2.1. ¿Cómo se diferencia el código fuente del código objeto y del ejecutable?

Entre que el codigo fuente es lo que escribe un programador y el objeto es una versión mas compilada que no se puede ejecutar, el ejecutable es el codigo objeto final.

2.2. ¿Por qué el ordenador no puede entender el código fuente directamente?

Porque está en un lenguaje de alto nivel

2.3. ¿Por qué es importante el paso de enlazado en la creación de programas?

Porque junta múltiples archivos de código objeto y bibliotecas en un solo ejecutable.

2.4. ¿Qué ocurre si falta alguna de las etapas (código objeto o ejecutable)?

Pues que no podria ser compilado bien, ya que habrá una versión intermedia para enlazar.

3. Generación de código intermedio¶
3.1. ¿Cómo difiere el código intermedio del código ejecutable tradicional?

Es un código formato portatil optimizado para máquinas virtuales, y mientras que el código ejecutable está diseñado para una arquitectura específica que se ejecuta luego en el hardware.

3.2. ¿Por qué es útil tener una máquina virtual?

Porque te permite ejecutar software en entornos aislados, aumentando la seguridad sin afectar el sistema.

3.3. ¿Qué ventajas ofrece el código intermedio?

La seguridad ya que se puede ejecutar en un entorno controlado, tambien la optimización a la hora de ejecución.

3.4. ¿Además de java, qué otros lenguajes usan máquinas virtuales?

Kotlin, Pyhton, C#

4. Lenguajes de programación¶
4.1. Primera parte¶
Compara el proceso de ejecución entre el lenguaje compilado y el interpretado.

Pues que en un lenguaje compilado el codigo fuente se traduce a codigo máquina antes de ejecutarse,y el interpretado el código se traduce y ejecuta línea por línea, siendo asi mas facil de depurar.

4.1.1. ¿Qué diferencias notaron en el proceso de compilación frente a la ejecución directa?

En de compilación el codigo fuente se traduce a un ejecutable mejorando el rendimiento y la directa traduce y ejecuta el código simultaneamente, facilitandote las pruebas.

4.1.2. ¿Qué pasa si hay un error de sintaxis en cada lenguaje? ¿Cuándo se detecta el error?

Pues que se detectan, impidiendo la creación del ejecutable, y los errores se detectan justo a la hora de ejecutar.

4.2. Segunda parte¶
Compara un lenguaje de alto nivel con uno de bajo nivel.

Python: es mas fácil de leer y usar con menos errores
Ensamblador: más dificil entender y programar

4.2.1. ¿Qué notaron sobre la abstracción entre los lenguajes de alto nivel y bajo nivel?

En los de alto nivel permite a los programadores enfocarse más en lógica que por hardware, y los de bajo nivel requiere una comprensión más profunda del sistema.

4.2.2. ¿Qué ventajas y desventajas encontraron en cada uno?

En que los de alto nivel son fáciles de usar y rápidos de desarrollar, y los de bajo nivel permiten un control mas centrado y mejor rendimiento.

4.3. Tercera parte¶
Compara un lenguaje orientado a objetos vs funcional.

Los orientados a objetos son buenos para modelar y los funcionales son mas claros y precisos.

4.3.1. ¿Cómo funciona la organización de datos en Java usando objetos y métodos?

Pues los datos se organizan mediante unas clases que sirven como modelos para crear objetos. Permite agrupar datos lo que favorece la reutilización del código.

4.3.2. ¿Cómo es diferente trabajar en un enfoque funcional en Python, usando solo funciones puras?

En Python utilizar funciones puras que no causan efectos secundarios pueden producir el mismo resultado. 

4.4. Reflexión final¶
4.4.1. ¿Qué lenguajes se sintieron más fáciles de usar? ¿Por qué?

Pyhton, es el más utilizado, siendo el más cómodo y el que menos errores da.

4.4.2. ¿En qué casos es preferible usar un lenguaje compilado frente a uno interpretado?

Es mejor un lenguaje compilado para alto rendimiento en aplicaciones exigentes.

4.4.3. ¿Cuándo es mejor usar un lenguaje de alto nivel en lugar de uno de bajo nivel?

Cuando quieras más rapidez y facilidad en aplicaciones complejas.

4.4.4. ¿Cómo se siente trabajar con el paradigma orientado a objetos en comparación con el imperativo o funcional?

Ofrece una posición buena, ya que los otros paradigmas requieren enfoques mas abstractos

5. Herramientas de desarrollo¶
5.1. Primera parte¶
Respecto a las proceso de creación de software identifica un conjunto de herramientas a usar.

Lenguajes de Programación, sistemas de gestión de base de datos, entornos de desarrollo.

5.1.1. ¿Qué hace cada una de las herramientas?

lenguajes de programación: Permite escribir el código fuente
sistemas de gestión de base de datos: Almacena y gestiona los datos de manera eficiente.
Entornos de desarrollo: Espacio de trabajo donde los desarrolladores pueden escribir y ejecutar código.

5.1.2. ¿Qué tipo de tareas facilita?

Lenguajes de programación: escribir de forma lógica
Entornos de desarrollo: Edición de código
sistemas de gestión de base de datos: Almacena y recupera datos.

5.1.3. ¿Qué características ofrece que la hacen única o diferente de otras herramientas similares?

En entornos de desarrollo, combinan características como depuración, controlador de versiones

En lenguajes de programación tienen sintaxis simple 

en sistemas de gestión de base de datos realiza operaciones avanzadas sobre los datos

5.1.4. Elige una ¿Cómo es la experiencia de usuario al usarla? ¿Es fácil o compleja?

Visual Studio Code (Entorno de desarrollo) tiene una interfaz muy limpia y es fácil de navegar, tiene las herramientas organizadas lo que permite la facilidad de trabajo para los nuevos usuarios

5.1.5. Elige una ¿En qué situaciones sería ideal utilizar esta herramienta?

Es ideal para el desarrollo web, colaboración de equipo y aprendizaje.

5.1.6. Elige una ¿Qué limitaciones encontraste en la herramienta?

Se necesita una configuración inicial y falta de algunas caracteríticas

5.2. Segunda parte¶
Céntrate en una herramienta dentro de la misma categoría y compárala con otras:

Visual Studio Code y Sublime text
visual studio code: ideal para el desarrollo web, con herramientas y funciones avanzadas
sublime text: Ideal para editores que trabajan con archivos grandes y que necesitan mas eficiencia.

5.2.1. ¿Qué herramienta se considera más útil y por qué?

Visual Studio Code, ya que tiene una gran facilidad de uso, y es adecuada para hacer proyectos de trabajo.

5.2.2. ¿Qué ventajas tiene una sobre la otra?

El rendimiento es mucho mas rapido, la interfaz es mejor y mas cómoda

5.2.3. ¿Cuál herramienta resultó ser la más intuitiva y por qué?

Visual Studio Code, por su facilidad de uso y sus funciones.

5.2.4. ¿En qué casos se recomendaría usar un compilador en lugar de un intérprete?

Cuando se requiera un alto rendimiento o cuando se desarrolla el software.

5.2.5. ¿Qué tipo de proyectos se beneficiarían más de un framework como Django?

Sistemas de gestión de contenido, Aplicaciones basada en datos, aplicaciones basada en redes

5.3. Reflexión final¶
Con base en la experiencia de evaluación de las herramientas:

Visual Studio Code por sus funciones, comunidad, interfaz sus actualizaciones y mantenimiento

5.3.1. ¿Cómo crees que impacta la elección de la herramienta en la calidad del software?

Impacta por varias razones, por la eficiencia en el desarrollo, por la colaboración, por la detección de errores, etc...

5.3.2. ¿Qué características buscarías en una herramienta para facilitar tu flujo de trabajo?

Terminal, herramientas de depuración, interfaz

5.3.3. ¿Cómo cambió tu percepción de estas herramientas después de haberlas probado y evaluado?

Pues la adaptabilidad, al fin y al cabo te acabas adaptando, también las ideas cambian en como quieres organizar tu propio proyecto en una de las herramientas.
