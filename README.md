![Logo del proyecto](logo.jpg)

# Proyecto Final

**Integrantes:**
- Luis José Aramayo Téllez
- Nataly Zarco Paniagua
- Ricardo Antonio Montero Ardaya

**Materia:** Tecnología Web 2  
**Docente:** Ing. Jaime Zambrana Chacón  

**SANTA CRUZ – BOLIVIA**

---

# Sistema Web de Música – *MusicaWeb*

## 1. Introducción

El presente documento describe el desarrollo de **MusicaWeb**, un sistema web diseñado para permitir la reproducción de música en línea a través de una interfaz amigable y sencilla. El objetivo principal de este proyecto es ofrecer a los usuarios una experiencia interactiva de exploración y reproducción de canciones, implementando tecnologías web de uso común como **HTML**, **CSS**, **JavaScript** y **PHP**.

El desarrollo de MusicaWeb surge como parte de la asignatura de **Tecnología Web 2**, con el propósito de aplicar conocimientos teóricos y prácticos en la creación de aplicaciones dinámicas que integren funcionalidades multimedia.

---

## 2. Objetivos

### 2.1. Objetivo general
Desarrollar un sistema web que permita a los usuarios reproducir música de manera sencilla e interactiva, mediante una interfaz accesible y funcional.

### 2.2. Objetivos específicos
- Diseñar una interfaz web atractiva utilizando **HTML** y **CSS**.
- Implementar controles de reproducción con **JavaScript**.
- Integrar el backend con **PHP** para la gestión de archivos y, opcionalmente, base de datos.
- Permitir la visualización de una lista de canciones disponibles para su reproducción.

---

## 3. Tecnologías utilizadas

Para la implementación de **MusicaWeb** se emplearon las siguientes herramientas y tecnologías:

- **HTML5**: estructura y contenido de las páginas web.
- **CSS3**: estilos y diseño visual.
- **JavaScript**: control de eventos y funcionalidades dinámicas.
- **PHP**: procesamiento del lado del servidor.
- **MySQL** (opcional): almacenamiento y consulta de información musical si se usa base de datos.

---

## 4. Instalación y configuración

Para ejecutar el sistema en un entorno local:

1. Descargar o clonar el repositorio:
https://github.com/Nataly495/MusicaWeb.git

2. Copiar la carpeta del proyecto en el directorio **htdocs** de XAMPP (o la carpeta pública de su servidor local).
3. *(Opcional)* Si se utiliza una base de datos:
- Crear una base de datos en **phpMyAdmin**.
- Importar el archivo `.sql` ubicado en la carpeta `/database`.
- Configurar las credenciales de conexión en el archivo `conexion.php`.
4. Iniciar los servicios de **Apache** (y **MySQL** si aplica) desde XAMPP.
5. Acceder a través del navegador ingresando:

http://localhost/MusicaWeb


---

## 5. Funcionalidades principales

**MusicaWeb** ofrece las siguientes características:

- Visualización de una lista de canciones disponibles para su reproducción.
- Reproductor integrado con controles de **play**, **pause**, **stop** y **siguiente/anterior**.
- Diseño responsivo que se adapta a diferentes tamaños de pantalla.
- Posibilidad de gestionar (agregar, eliminar) archivos de música en el servidor (si se habilita en backend).

---

## 6. Capturas de pantalla

A continuación se presentan algunas vistas del sistema:

### 6.1. Página principal
![Página principal](1.jpg)

### 6.2. Reproductor en acción
![Reproductor en acción](2.jpg)

### 6.3. Lista de canciones
![Lista de canciones](3.jpg)

### 6.4. Menú de navegación
![Menú de navegación](4.jpg)

### 6.5. Página de detalles de la canción
![Detalles de la canción](5.jpg)

### 6.6. Vista móvil responsiva
![Vista móvil responsiva](6.jpg)

### 6.7. Controles de reproducción
![Controles de reproducción](7.jpg)

### 6.8. Pie de página con créditos
![Pie de página](8.jpg)

