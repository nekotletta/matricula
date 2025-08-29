<div align="center">
<h1>Matrícula</h1> 
</div>

<div align="center">
   
[Documentation in English](https://github.com/nekotletta/matricula)

</div>

<div align="center">
<h2>Overview</h1> 
</div>

Matrícula es un proyecto creado específicamente para mejorar el sistema de inscripción de la Universidad de Puerto Rico (UPR). El objetivo de este proyecto es mostrar las posibilidades que se abrirían si la UPR decidiera modernizar su sistema. El proyecto se ha diseñado centrándose en la experiencia del usuario, para que sea lo más fácil de navegar posible.

Para este proyecto se utilizó React para el frontend y Django para el backend.

![Matricula showcase](https://github.com/nekotletta/matricula/blob/main/matricula-home.png)

<div align="center">
<h2>Contexto</h2>
</div>

El sistema de inscripción de la UPR es un sistema increíblemente anticuado (creado en los años 70), construido íntegramente en un terminal, en lugar de en una página web.

Esto siempre ha sido un gran problema debido a lo poco intuitivo que resulta todo el sistema para los estudiantes. Los estudiantes que lo utilizan por primera vez suelen sentirse confundidos y asustados, ya que nunca antes han utilizado un terminal. Además, la navegación tampoco es sencilla.

<div align="center">
<h2>FAQ</h2>
</div>


### ¿Por qué se creó este proyecto?

Este proyecto se creó como una muestra de lo que sería posible si se modernizara el sistema de la UPR. Su objetivo es abordar las quejas más recurrentes de los estudiantes.
### ¿Este proyecto está afiliado de alguna manera a la UPR?

No, este proyecto es completamente independiente de la UPR. Lo único que tiene que ver con la UPR son los datos de los cursos.


### Si me inscribo en cursos a través de este sitio, ¿se reflejará en mi perfil real de la UPR?

No, este proyecto no está conectado directamente con la UPR de ninguna manera. Es solo una muestra. Si deseas inscribirte en un curso de la UPR, debes ir al sitio web de la universidad.

### ¿Quién lo desarrolló?

Este proyecto fue desarrollado por un solo estudiante de informática para la UPR. Ten en cuenta que, debido a esto, es posible que no todo funcione perfectamente o que falte algo que crees que debería estar en el proyecto.

<div align="center">
<h2>Funcionalidad</h2>
</div>

El proyecto cuenta con todas las características del sistema de inscripción, además de dos adicionales.

### Registro e inicio de sesión

El sistema de inscripción de la UPR no requiere registro, ya que toda la información necesaria se encuentra en los registros de la universidad. Sin embargo, este proyecto no cuenta con dichos registros, lo que significa que cualquier persona que desee utilizar esta plataforma debe registrarse.

#### Cómo se mejoró 

- Los usuarios no necesitan proporcionar su número de seguro social para iniciar sesión en la plataforma.
- Los usuarios pueden crear sus propias contraseñas, en lugar de depender de los métodos de autenticación inseguros de la UPR.

### Menú de navegación

El sistema de inscripción de la UPR no tiene una forma sencilla de navegar por el terminal. Cada página es un código poco intuitivo que los estudiantes deben memorizar.

#### Cómo se mejoró

Se implementó un menú sencillo, en el que cada página está claramente etiquetada. Se puede acceder a este menú desde cualquier página con un simple clic.

### Perfil de usuario 

El sistema de inscripción de la UPR ya cuenta con una sección en la que el estudiante puede ver las clases en las que está inscrito actualmente.

#### Cómo se mejoró 

Se simplificó la presentación de la información. Se añadió una sección en la que los usuarios pueden ver los cursos que han completado. Esto puede ayudar a los usuarios a realizar un seguimiento del progreso de su titulación.

### Visualizador del horario de cursos

El sistema de inscripción de la UPR no cuenta con esta función. Se creó después de observar que todos dependían de sitios externos o escribían los cursos a mano para elaborar su horario. 

Cómo funciona: los usuarios pueden marcar cursos específicos en la plataforma. Estos cursos se guardan y se puede acceder a ellos más tarde para añadirlos a su horario óptimo. 

### Inscripción 

La forma en que un estudiante se inscribe en los cursos en el sistema de la UPR no es nada sencilla. Además, tampoco cuenta con la función de hacer clic en un botón. Los estudiantes deben introducir códigos específicos y pulsar Intro para inscribirse o darse de baja de un curso. 

#### Cómo se mejoró

Se implementó un menú sencillo para inscribirse con un solo clic. Además, los estudiantes ya no tienen que escribir el código del curso en el que desean inscribirse. Pueden seleccionar las clases de sus favoritos y estas se añaden automáticamente a su lista de inscripción.

### Búsqueda de clases

El sistema de la UPR solo cuenta con una búsqueda básica de todas las clases disponibles.

#### Cómo se mejoró 

La búsqueda de cursos se divide por facultades. Los estudiantes seleccionan la facultad en la que desean buscar cursos.

Las siguientes funciones no están disponibles en el sistema de la UPR:

- Búsqueda por profesores: los estudiantes pueden buscar un profesor para ver solo las clases que imparte.
- Marcadores: los estudiantes pueden marcar determinados cursos en los que deseen inscribirse. Se puede acceder a los cursos marcados al crear el horario óptimo.
- Configuración avanzada: los estudiantes pueden ajustar la siguiente configuración al buscar cursos:
   - Mostrar solo cursos con plazas disponibles.
   - Mostrar solo cursos marcados como favoritos por el estudiante.
   - Mostrar solo cursos de laboratorio (útil para cursos de biología, química o física).
   - Mostrar solo cursos presenciales, en línea o híbridos.
   - Mostrar solo cursos que comienzan y terminan entre las fechas especificadas.
   - Mostrar solo cursos que se imparten durante los días especificados.
