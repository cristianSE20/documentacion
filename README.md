# 🗺️ UPIICSAExplore: Tu Guía Interactivo del Campus y Alrededores

## **Descripción General del Proyecto**

Descripción General del Proyecto
UPIICSAExplore es una aplicación móvil diseñada para transformar la manera en que los estudiantes de UPIICSA interactúan y navegan por su entorno académico. Sabemos que el 
campus y sus alrededores son vastos y, a menudo, puede ser un desafío para los recién llegados, e incluso para los alumnos con más tiempo, localizar puntos de interés 
específicos o descubrir esos "lugares secretos" que hacen la vida estudiantil más cómoda y productiva.

Nuestra misión es resolver este problema proporcionando una plataforma intuitiva y centrada en la comunidad. Con UPIICSAExplore, los estudiantes pueden fácilmente encontrar 
y marcar ubicaciones importantes dentro y fuera de la escuela, como aulas, laboratorios, bibliotecas, pero también esos espacios valiosos identificados por la comunidad: 
lugares tranquilos para estudiar, zonas con excelente cobertura Wi-Fi, opciones de comida cercanas, y áreas ideales para trabajar o relajarse.

A diferencia de las aplicaciones de mapas genéricas, que no ofrecen el nivel de detalle necesario para el día a día estudiantil, UPIICSAExplore es el primer mapa creado 
específicamente por y para la comunidad UPIICSA. Mientras que otras herramientas permiten la personalización, nuestra aplicación se distingue por su facilidad de uso y 
la capacidad de compartir descubrimientos directamente con tus compañeros, fomentando una experiencia de exploración colaborativa y siempre actualizada, ¡sin complicaciones!

## Características Principales 🛠️

La aplicación está diseñado con una serie de características intuitivas para enriquecer tu experiencia en el campus:

- Creación Intuitiva de Pines Personalizados: Simplemente toca cualquier punto en el mapa para iniciar la creación de un nuevo pin. Cada pin puede ser enriquecido con:
  - Una fotografía capturada al instante.
  - Un título descriptivo.
  - Una descripción detallada del lugar.
  - Una categoría para una mejor organización (ej. "Comida", "Estudio", "Relax").
  - La opción de marcarlo como privado (visible solo para ti) o público (compartido con la comunidad).
- Todos tus pines personalizados muestran directamente en el mapa con íconos de pin distintivos, facilitando la identificación de ubicaciones importantes de un vistazo.
- Accede a una sección dedicada donde puedes ver, buscar y filtrar pines compartidos por otros estudiantes. Cada pin comunitario incluye su descripción completa y el
  nombre del usuario que lo compartió, creando una especie de "muro" de descubrimientos colaborativos. Esta funcionalidad te permite explorar fácilmente los lugares más
  relevantes y útiles identificados por la propia comunidad estudiantil, asegurando que la información compartida esté siempre accesible en un único lugar consolidado.

## Tecnologías Utilizadas 🖥️

Desarrollamos la app utilizando un robusto conjunto de tecnologías para asegurar un rendimiento óptimo y una experiencia de usuario fluida:

UPIICSAExplore ha sido desarrollado meticulosamente utilizando una combinación de tecnologías robustas para garantizar tanto una experiencia de usuario fluida y nativa 
como una gestión de datos escalable y segura. La aplicación móvil fue construida enteramente para Android, aprovechando el poder de Android Studio 2024.3.2 y la versatilidad 
de los lenguajes Kotlin y Java para crear una interfaz intuitiva y un rendimiento optimizado directamente en el dispositivo. Para la crucial sincronización y gestión de datos, 
el proyecto se apoya en una API desarrollada en C# con Visual Studio, que actúa como el puente entre la aplicación móvil y su base de datos, alojada en Microsoft Azure. 
Esta infraestructura asegura que todos los pines, tanto los personales como los de la comunidad, estén siempre disponibles, actualizados y gestionados de forma eficiente en la nube.

## Arquitectura 👷🏼

Sigue el patrón de arquitectura Model-View-ViewModel (MVVM) para asegurar una clara separación de responsabilidades, facilitar la escalabilidad y mejorar la capacidad de 
prueba y mantenimiento del código. En esta estructura:

- El Modelo representa los datos y la lógica de negocio, incluyendo la interacción con la API de sincronización (desarrollada en C#) y la base de datos alojada en Azure. 
Es el encargado de gestionar la persistencia y recuperación de los pines.
- La Vista (implementada con las interfaces de usuario de Android en Kotlin/Java) es lo que el usuario ve e interactúa. Su función principal es mostrar los datos proporcionados por el ViewModel.
- El ViewModel actúa como un puente entre la Vista y el Modelo. Contiene la lógica de presentación, preparando los datos del Modelo para ser mostrados en la Vista y manejando las interacciones del usuario de la Vista, comunicándolas al Modelo.

Esta arquitectura garantiza que la aplicación móvil se mantenga modular y robusta, permitiendo una gestión eficiente de la creación de pines, la visualización en el mapa y la interacción con los pines de la comunidad, todo ello sincronizado a través de nuestra API y persistido en Azure.

## Requisitos del Dispositivo para el Usuario 📱

Para disfrutar de una experiencia óptima con UPIICSAExplore, tu dispositivo Android debe cumplir con las siguientes especificaciones:

- Versión del Sistema Operativo Android:
  - Mínimo Soportado: Android 7.0 (Nougat, API 24).
  - Recomendado para un Rendimiento Óptimo: Android 9.0 (Pie, API 28) o superior, ya que estas versiones incluyen mejoras significativas en rendimiento y gestión de memoria que benefician a aplicaciones con mapas interactivos.

- Hardware del Dispositivo:
  - Procesador (CPU): Para un funcionamiento fluido y una navegación sin interrupciones en el mapa, se recomienda un procesador de ocho núcleos (Octa-core) de gama media (como un Qualcomm Snapdragon 660 o MediaTek Helio G85) o superior. Esto asegurará transiciones suaves al desplazar y hacer zoom.
  - Memoria RAM: Se necesitan al menos 4 GB de RAM para que la aplicación funcione correctamente junto con el sistema operativo y otras aplicaciones. Sin embargo, 6 GB de RAM o más son ideales para una experiencia más cómoda y sin demoras.
  - Almacenamiento Interno: Es aconsejable disponer de un mínimo de 64 GB de almacenamiento interno.
 
 ## Autores 📕

UPIICSAExplore fue desarrollado gracias al esfuerzo y dedicación del siguiente equipo:

- Cristian Solis: Responsable del desarrollo del Front-End de la aplicación móvil y el diseño de la base de datos.
- Daniel: Encargado del desarrollo del Back-End, la creación de la API de sincronización y el montaje de la base de datos en Azure.

