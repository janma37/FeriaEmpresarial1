Aquí tienes la versión actualizada del README.md sin emojis.

Proyecto: Feria Empresarial
Este es un proyecto académico desarrollado en Java que simula un sistema de gestión para una feria empresarial. La aplicación permite administrar empresas, stands, visitantes e interacciones, aplicando los conceptos de la Programación Orientada a Objetos (POO).

Descripción del Proyecto
El objetivo es crear una aplicación de consola que permita al usuario realizar operaciones de gestión completas para una feria. El sistema maneja el registro de participantes, la asignación de espacios, el registro de visitas y la generación de reportes básicos.

Funcionalidades Principales
Gestión de Empresas: Registrar, editar, eliminar y listar empresas participantes.

Gestión de Stands: Crear stands, asignarlos a empresas y listar los disponibles u ocupados.

Gestión de Visitantes: Registrar, editar y eliminar los datos de los asistentes a la feria.

Interacción y Calificaciones: Permitir que los visitantes dejen comentarios y calificaciones (1-5 estrellas) en los stands que visitan.

Generación de Reportes: Crear informes básicos que cruzan la información de empresas, stands y visitantes.

Tecnologías y Herramientas
Lenguaje: Java

Entorno de Desarrollo: NetBeans, Eclipse, IntelliJ IDEA

Control de Versiones: Git y GitHub

Requisitos Previos
Para ejecutar este proyecto, necesitas tener instalado:

Java Development Kit (JDK), versión 8 o superior.

Un IDE de Java como NetBeans, Eclipse o similar.

¿Cómo Ejecutar el Proyecto?
Dado que el código fuente está consolidado en un archivo .zip en el repositorio, sigue estos pasos:

Descargar el Archivo: En la página principal del repositorio, haz clic sobre el archivo .zip y descárgalo a tu computadora.

Descomprimir: Busca el archivo descargado y descomprímelo. Esto creará una carpeta con todos los archivos del proyecto.

Abrir en tu IDE:

Abre tu IDE (NetBeans, Eclipse, etc.).

Ve a File > Open Project... (en NetBeans) o File > Import... > General > Projects from Folder or Archive (en Eclipse).

Selecciona la carpeta que acabas de descomprimir.

Ejecutar la Aplicación:

Una vez que el proyecto esté cargado, busca el archivo Aplicacion.java en el explorador de proyectos.

Haz clic derecho sobre él y selecciona la opción "Run File" (NetBeans) o "Run As > Java Application" (Eclipse).

La aplicación se iniciará en la consola de tu IDE, mostrando el menú principal.

Estructura del Proyecto
El proyecto se compone de 6 clases que trabajan en conjunto:

Aplicacion.java: Clase principal que contiene el método main(). Se encarga de mostrar el menú y gestionar la interacción con el usuario.

FeriaManager.java: El cerebro del proyecto. Centraliza toda la lógica de negocio: registrar, buscar, asignar y generar reportes.

Empresa.java: Modela a una empresa participante con su ID, nombre, sector y email.

Stand.java: Modela un puesto físico. Tiene un número, ubicación, tamaño y se le puede asignar una Empresa. También almacena una lista de Comentarios.

Visitante.java: Modela a un asistente a la feria con su identificación, nombre y email.

Comentario.java: Modela una calificación dejada por un Visitante en un Stand.
