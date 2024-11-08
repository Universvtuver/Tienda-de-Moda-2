<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Sitio Web Accesible</title>
    <!-- Enlace a Bootstrap -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Enlace a CSS personalizado -->
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Encabezado con barra de navegación -->
    <header>
        <nav class="navbar navbar-expand-lg navbar-light bg-light" aria-label="Barra de navegación">
            <div class="container-fluid">
                <a class="navbar-brand" href="#">Mi Sitio Web</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Alternar navegación">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ms-auto">
                        <li class="nav-item">
                            <a class="nav-link active" href="#inicio" aria-current="page">Inicio</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#productos">Productos</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#contacto">Contacto</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>

    <!-- Sección de bienvenida -->
    <section id="inicio" class="bg-primary text-white text-center p-5">
        <div class="container">
            <h1>¡Bienvenidos a Mi Sitio Web!</h1>
            <p class="lead">Aquí encontrarás productos exclusivos con las mejores tendencias.</p>
        </div>
    </section>

    <!-- Sección de productos destacados -->
    <section id="productos" class="py-5">
        <div class="container">
            <h2 class="text-center">Productos Destacados</h2>
            <div class="row">
                <div class="col-lg-4 col-md-6 mb-4">
                    <div class="card h-100">
                        <img src="Producto 1.jpg" alt="Descripción del Producto 1" class="card-img-top">
                        <div class="card-body">
                            <h5 class="card-title">Producto 1</h5>
                            <p class="card-text">$29.99</p>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6 mb-4">
                    <div class="card h-100">
                        <img src="Producto 2.jpg" alt="Descripción del Producto 2" class="card-img-top">
                        <div class="card-body">
                            <h5 class="card-title">Producto 2</h5>
                            <p class="card-text">$39.99</p>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6 mb-4">
                    <div class="card h-100">
                        <img src="Producto 3.jpg" alt="Descripción del Producto 3" class="card-img-top">
                        <div class="card-body">
                            <h5 class="card-title">Producto 3</h5>
                            <p class="card-text">$49.99</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Sección de contacto -->
    <section id="contacto" class="bg-light py-5">
        <div class="container">
            <h2 class="text-center">Contacto</h2>
            <form action="#" method="post" aria-label="Formulario de contacto">
                <div class="mb-3">
                    <label for="nombre" class="form-label">Nombre:</label>
                    <input type="text" id="nombre" name="nombre" class="form-control" aria-required="true">
                </div>
                <div class="mb-3">
                    <label for="email" class="form-label">Correo Electrónico:</label>
                    <input type="email" id="email" name="email" class="form-control" aria-required="true">
                </div>
                <div class="mb-3">
                    <label for="mensaje" class="form-label">Mensaje:</label>
                    <textarea id="mensaje" name="mensaje" rows="5" class="form-control" aria-required="true"></textarea>
                </div>
                <div class="text-center">
                    <button type="submit" class="btn btn-primary">Enviar</button>
                </div>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white text-center p-3">
        <p>&copy; 2024 Mi Sitio Web - Todos los derechos reservados.</p>
    </footer>

    <!-- Enlace a Bootstrap JS (necesario para el funcionamiento del navbar) -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
