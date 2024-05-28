<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página Web Personal</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 2rem 0;
        }
        .bio {
            text-align: center;
        }
        .projects {
            margin-top: 2rem;
        }
        .projects h2 {
            text-align: center;
        }
        .project {
            background: #fff;
            padding: 1rem;
            margin-bottom: 1rem;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .project h3 {
            margin-top: 0;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        a {
            color: #1e90ff;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Mi Página Web Personal</h1>
    </header>
    <div class="container">
        <div class="bio">
            <h2>Sobre mí</h2>
            <p>¡Hola! Soy un apasionado de la programación con experiencia en diversos lenguajes y tecnologías. Me encanta crear soluciones innovadoras y eficientes para problemas complejos. Aquí puedes encontrar algunos de mis proyectos destacados.</p>
        </div>
        <div class="projects">
            <h2>Proyectos Destacados</h2>
            <div class="project">
                <h3>Proyecto 1: Sistema de Gestión de Tareas</h3>
                <p>Un sistema completo para gestionar tareas y proyectos, con funcionalidades de asignación de tareas, seguimiento de progreso y reportes.</p>
            </div>
            <div class="project">
                <h3>Proyecto 2: Aplicación de Comercio Electrónico</h3>
                <p>Una aplicación web de comercio electrónico con carrito de compras, procesamiento de pagos y administración de inventario.</p>
            </div>
            <div class="project">
                <h3>Proyecto 3: Plataforma de Blog</h3>
                <p>Una plataforma de blogging con funcionalidades de creación de contenido, comentarios de usuarios y panel de administración.</p>
            </div>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 Mi Página Web Personal | <a href="mailto:tuemail@ejemplo.com">Contacto</a></p>
    </footer>
</body>
</html>
