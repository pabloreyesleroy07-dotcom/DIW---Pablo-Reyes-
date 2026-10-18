# BRIEF - PABLO REYES
## Indice
[Introduccion](#Introduccion)  
[El problema que resuelve la aplicacion](#El-problema-que-resuelve-la-aplicacion)  
[El Alcance](#El-Alcance)  
[Las Personas](#Las-Personas)  
[Criterios de éxito](#Criterios-de-Exito)  
[Restricciones del Proyecto](#Restricciones-del-Proyecto)  
## Introduccion 
Buenas, aquí iré construyendo el BRIEF paso a paso e iré contando mi idea de proyecto, espero que te guste.

## El problema que resuelve la aplicacion
La hipotesis inicial que comenzó este proyecto fue:  
> Creo que las personas que coleccionan logros en videojuegos necesitan saber qué aporta cada uno y cómo conseguirlo pero, necesitan ver videos de horas y horas.


Tras esta hipotesis hice una lluvia de ideas y respondí a varias preguntas, las preguntas me llevaron a hacer una encuesta a mis personas cercanas relacionadas con el tema del proyecto, los videojuegos.  
  
Esta encuesta, la cual te invito a que le des un vistazo a los resultados, la puedes encontrar [aqui](https://docs.google.com/spreadsheets/d/1g2nSU0fiEUSPu0I42e9nOrjyJDGKkbX4/edit?usp=drive_link&ouid=114390182737670734859&rtpof=true&sd=true).    
  
Ver los datos de la encuesta me hizo darme cuenta que las personas no quieren conseguir todos los logros para lucir o fardar de ellos. Sino que les interesa divertirse en el proceso y sobretodo, conseguir objetos o cosméticos dentro del juego como recompensa (7,6 % vs 92,4% ), lo que nos indica que deberíamos orientar la web un poco. 

## El Alcance 

Para decidir qué se queda dentro y que no en esta primera versión, me he fijado en tres aspectos: si la persona principal la necesita para su tarea más importante, si se puede construir con el tiempo que tengo, y si existe otra forma de resolverla mientras tanto.

### Funciones que se quedan:
- **Buscador de juegos:** Imprescindible para que el usuario localice rápidamente el juego que quiere.
- **Ficha del juego:** Muestra metadatos importantes.
- **Listado y filtrado de logros:** Permite ordenar los retos según las recompensas o cosméticos que de el logro al completarlo.
- **Creación de Runs personalizadas:** Es el núcleo de la aplicación, permite al usuario seleccionar logros y hacer un seguimiento de su progreso.

### Funciones que se van porque:
- **Expositor de logros en el perfil de usuario:** Se descarta porque la persona principal no lo necesita para su tarea.
- **Sistema de favoritos y personalización de perfil:** Se descarta ya que no es vital para el funcionamiento básico del MVP.
- **Recomendaciones automatizadas por historial:** Se descarta porque excede el tiempo de desarrollo.

## Las Personas  
El diseño de la aplicación se fundamenta en dos perfiles basados en las encuentas:

[Abraham (Persona Principal)](https://www.figma.com/board/LPBniBURjdYxFjjNCXAl2E/Proyecto-Dise%C3%B1o?node-id=60-2925&t=pF003PetDC6fHAxV-4): 
Estudiante de 18-21 años que juega a diario en PC; representa el recorrido principal para localizar rápidamente guías y filtrar logros por recompensas.  

[Alejandro (Persona Secundaria / Caso Límite)](https://www.figma.com/board/LPBniBURjdYxFjjNCXAl2E/Proyecto-Dise%C3%B1o?node-id=61-3167&t=pF003PetDC6fHAxV-4):
Estudiante y trabajador de 22-25 años con tiempo limitado que juega los fines de semana, representa la necesidad de una navegación rápida y sin saturación de contenido.  

## Criterios de éxito

El éxito del diseño se evaluará comprobando las siguientes tareas directamente sobre las personas definidas:

* **Abraham** puede buscar un juego, localizar los pasos para desbloquear una recompensa cosmética y añadir el logro a su run sin ayuda y en menos de un minuto.
* **Alejandro** puede consultar el listado de logros de un juego y filtrar únicamente los que otorgan objetos útiles para una nueva partida en menos de 30 segundos.
* **Cualquier usuario nuevo** que acceda al prototipo puede identificar para qué sirve la aplicación y completar el flujo al primer intento sin atascarse.
  
## Restricciones del proyecto

Para asegurar que la aplicación funcione de forma óptima y sostenible en los entornos de verdad, se incorporan las siguientes medidas:

- Enfoque multidispositivo : La interfaz debe adaptarse y funcionar sin pérdida de contenido en pantallas móviles estándar y de escritorio.
- Restricción ambiental y de rendimiento (WSG 2.4): Siguiendo el criterio 2.4 de las *Web Sustainability Guidelines* del W3C, se fija un límite técnico de peso máximo transferido inferior a 500 KB por página en la carga inicial. Esto garantiza un consumo energético mínimo, reduce la huella de carbono digital y asegura tiempos de respuesta inmediatos para usuarios con conexiones inestables.
- Diseño visual en baja fidelidad: Durante esta primera fase no se implementan estilos complejos ni tipografías definitivas, manteniéndose en escala de grises.
