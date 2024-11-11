Descripción General
Este código corresponde a una página web de presentación de un programa de "Ingeniería de Software" en Bogotá, desarrollado por una fundación universitaria. La estructura está compuesta por una serie de secciones que presentan información sobre el programa académico, las titulaciones, el campo laboral, y más. Está diseñado para ser visualmente atractivo, con botones de llamada a la acción y formularios de inscripción. El estilo está definido en un archivo CSS externo.

Estructura HTML
Encabezado (Header)
html
Copiar código
<header class="header">
    <div class="container">
        <div class="logo">
            <img src="img/main-logo.png" alt="Compensar Fundación Universitaria" width="75%">
        </div>
        <nav class="navbar">
            <a href="#">Graduados</a>
            <a href="#">Estudiantes</a>
            <a href="#">Estado de Admisión</a>
            <a href="#">Reingresos</a>
            <a href="#">Pago en Línea</a>
            <a href="#">Aplicativos</a>
            <a href="#">Emisora</a>
            <a href="#">Blog</a>
            <button class="btn-cta">Trabaja con nosotros</button>
        </nav>
    </div>
</header>
Logo: Se incluye una imagen que actúa como logo de la fundación.
Navegación: Varios enlaces y un botón "Trabaja con nosotros" que permite navegar por diferentes secciones relacionadas con la fundación.
Contenido Principal (Main Content)
html
Copiar código
<main class="main-content">
    <!-- Secciones como: Información del programa, Formulario, Titulaciones, Campo Laboral -->
</main>
Contiene múltiples secciones, entre ellas:

program-info: Descripción del programa, su modalidad y botones de acción (inscripción y consulta de tarifas).
bloque2: Información adicional, como SNIES, resolución y horarios del programa.
formulario: Formulario de inscripción que captura datos del usuario.
titulaciones: Muestra las titulaciones asociadas con el programa académico.
campo-laboral: Lista de posibles campos laborales para los egresados.
matriculas: Sección que destaca la disponibilidad de matrículas.
Pie de Página (Footer)
html
Copiar código
<footer class="footer">
    <div class="footer-content">
        <p>Fundación Universitaria Compensar PUJ</p>
        <div class="contact-info">
            <p><strong>Bogotá:</strong> Dirección, teléfono, correo</p>
            <p><strong>Villavicencio:</strong> Dirección, teléfono, correo</p>
        </div>
        <div class="social-links">
            <!-- Enlaces a redes sociales -->
            <a href="#">Facebook</a>
            <a href="#">Instagram</a>
            <a href="#">LinkedIn</a>
        </div>
    </div>
</footer>
Proporciona información de contacto y enlaces a redes sociales de la fundación.

Estilos CSS
Estilos Generales
css
Copiar código
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
Se establece una regla global para asegurarse de que no haya márgenes o rellenos predeterminados, y que el box-sizing sea border-box.

Cuerpo de la Página
css
Copiar código
body {
    font-family: Arial, sans-serif;
    background-color: #f9f9f9;
}
El cuerpo de la página tiene una fuente sans-serif y un fondo gris claro.

Encabezado (Header)
css
Copiar código
.header {
    background-color: #fff;
    padding: 1rem 2rem;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}
.navbar a {
    margin: 0 0.5rem;
    color: #333;
    text-decoration: none;
    font-size: 13px;
}
El encabezado tiene un fondo blanco con un pequeño sombreado. Los enlaces en la barra de navegación tienen márgenes y colores específicos.

Botones y Llamadas a la Acción
css
Copiar código
.btn-cta {
    background-color: #ff8400;
    color: #fff;
    padding: 0.5rem 1rem;
    border: none;
    border-radius: 20px;
    cursor: pointer;
}
Los botones tienen un fondo naranja, texto blanco y bordes redondeados, con un cursor que cambia a puntero al pasar sobre ellos.

Formulario
css
Copiar código
.formulario form {
    display: flex;
    flex-wrap: wrap;
    gap: 1rem;
}
input, select {
    padding: 0.5rem;
    border: 1px solid #ccc;
    border-radius: 5px;
    width: 100%;
}
.btn-submit {
    padding: 0.7rem 1.5rem;
    background-color: #ff8400;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}
Los formularios están diseñados con un sistema de diseño flexible. Los campos de entrada y los selectores tienen bordes y rellenos consistentes, y el botón de envío sigue el estilo de los botones de acción.

Titulaciones y Campo Laboral
css
Copiar código
.titulaciones .btargetas {
    display: flex;
    gap: 1.5rem;
}
.targeta {
    background-color: #f8f5f5;
    padding: 1rem;
    width: 30%;
    text-align: center;
}
Las titulaciones y el campo laboral se muestran en una disposición flexible, con tarjetas que contienen los detalles de cada título y campo de trabajo.

Pie de Página (Footer)
css
Copiar código
.footer {
    width: 100%;
    background-color: #333;
    color: #fff;
    padding: 2rem;
}
.footer-content {
    display: flex;
    justify-content: space-between;
    align-items: center;
}
El pie de página tiene un fondo oscuro con texto blanco, y se organiza en un diseño flexible para mostrar la información de contacto y los enlaces sociales.
