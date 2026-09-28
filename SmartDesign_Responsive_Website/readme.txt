SMART DESIGN - SITIO WEB RESPONSIVO
===================================

Descripción
-----------
Proyecto académico de un sitio web responsivo para la empresa ficticia/portafolio Smart Design. El sitio utiliza HTML5 semántico, CSS personalizado y Bootstrap 5 mediante CDN.

Objetivo
--------
Crear un sitio web moderno que se adapte a dispositivos móviles y de escritorio, con navegación entre varias páginas, una sección de portafolio y un formulario de contacto validado con Bootstrap.

Estructura del proyecto
-----------------------
SmartDesign_Responsive_Website/
|
|-- index.html                 Página de inicio
|-- portfolio.html             Página de portafolio
|-- contacto.html              Página de contacto
|-- proyecto-landing.html      Detalle del proyecto Landing Page
|-- proyecto-logo.html         Detalle del proyecto Diseño de Logo
|-- proyecto-branding.html     Detalle del proyecto Branding
|-- readme.txt                 Documentación del proyecto
|
|-- css/
|   |-- styles.css             Estilos personalizados
|
|-- img/
    |-- smart-design-logo.png  Logo de Smart Design

Tecnologías utilizadas
-----------------------
- HTML5 semántico
- CSS3
- Bootstrap 5.3.3 por CDN
- JavaScript básico para validación del formulario de Bootstrap
- Visual Studio Code como editor recomendado
- Navegador web para pruebas

Elementos semánticos utilizados
--------------------------------
- <header>
- <nav>
- <main>
- <section>
- <article>
- <aside>
- <footer>
- <address>

Requisitos de la tarea cubiertos
--------------------------------
1. Página de inicio:
   - Barra de navegación Bootstrap con enlaces a Inicio, Portafolio y Contacto.
   - Encabezado tipo hero con imagen de fondo y título.
   - Sección "Acerca de mí" con información ficticia.
   - Botón de llamada a la acción hacia la página de contacto.

2. Página de portafolio:
   - Proyectos mostrados con tarjetas Bootstrap.
   - Cada tarjeta tiene un botón "Leer más".
   - Cada botón dirige a una página de detalle del proyecto.

3. Página de contacto:
   - Formulario con nombre, correo electrónico y mensaje.
   - Validación visual con Bootstrap.
   - Información de contacto ficticia.

4. Diseño responsivo:
   - Uso del sistema Grid de Bootstrap.
   - Navbar colapsable en pantallas pequeñas.
   - Tarjetas y columnas que se reorganizan según el ancho de pantalla.
   - Tipografía adaptable con CSS clamp().

5. Personalización:
   - Paleta azul y azul marino basada en el logo Smart Design.
   - Estilos propios para botones, tarjetas, hero, encabezados y footer.
   - Logo de Smart Design utilizado en la navegación y contenido.

Cómo ejecutar el proyecto
-------------------------
1. Abre la carpeta SmartDesign_Responsive_Website en Visual Studio Code.
2. Abre index.html.
3. Puedes hacer doble clic en index.html para abrirlo en el navegador, o utilizar la extensión Live Server de VS Code.
4. Navega por Inicio, Portafolio y Contacto para comprobar los enlaces.
5. Reduce el ancho de la ventana o utiliza las herramientas de desarrollador del navegador para comprobar el diseño responsivo.

Nota sobre Bootstrap
--------------------
No es necesario descargar Bootstrap porque este proyecto utiliza CDN. Los archivos CSS y JavaScript de Bootstrap se cargan desde jsDelivr cuando existe conexión a Internet.

Nota sobre el formulario
------------------------
El formulario es demostrativo. La validación funciona en el navegador, pero no envía información a un servidor ni almacena datos.

GitHub
------
La configuración y publicación en GitHub se realizará posteriormente y no forma parte de esta entrega inicial del código.
