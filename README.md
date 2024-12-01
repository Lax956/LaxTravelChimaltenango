<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lax Travel Chimaltenango</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #000;
            color: #fff;
            text-align: center;
        }
        .header {
            padding: 20px;
        }
        .logo {
            width: 100px;
            border-radius: 50%;
        }
        .title {
            font-size: 1.5em;
            margin: 10px 0;
        }
        .social-icons {
            margin: 10px 0;
        }
        .social-icons img {
            width: 30px;
            margin: 0 10px;
            cursor: pointer;
        }
        .contact-info {
            margin-top: 10px;
        }
        .contact-info a {
            color: #fff;
            text-decoration: none;
        }
        .contact-info a:hover {
            text-decoration: underline;
        }
        .button {
            display: block;
            margin: 15px auto;
            width: 80%;
            max-width: 300px;
            padding: 15px;
            font-size: 1.1em;
            background-color: #333;
            color: #fff;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            text-decoration: none;
        }
        .button:hover {
            background-color: #555;
        }
        .requisitos {
            display: none;
            text-align: left;
            margin: 20px auto;
            width: 80%;
            max-width: 500px;
            background-color: #222;
            padding: 15px;
            border-radius: 10px;
        }
        .requisitos ul {
            list-style: none;
            padding: 0;
        }
        .requisitos li {
            margin: 5px 0;
        }
        .footer {
            padding: 20px;
        }
        .footer a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
        }
        .footer a:hover {
            text-decoration: underline;
        }
    </style>
    <script>
        function mostrarRequisitos(id) {
            const requisitos = document.querySelectorAll('.requisitos');
            requisitos.forEach(req => req.style.display = 'none'); // Oculta todos
            document.getElementById(id).style.display = 'block'; // Muestra el seleccionado
        }
    </script>
</head>
<body>
    <div class="header">
        <!-- Aquí agregas tu logo -->
        <img src="imagenes/logo.jpeg" alt="Logo Lax" class="logo">
        <h1 class="title">Lax Travel Chimaltenango</h1>
        <p>Agencia de viajes</p>
        <div class="social-icons">
            <!-- Íconos de redes sociales -->
            <a href="https://facebook.com" target="_blank">
                <img src="imagenes/facebook.png" alt="Facebook">
            </a>
            <a href="https://instagram.com" target="_blank">
                <img src="imagenes/instagram.png" alt="Instagram">
            </a>
            <a href="https://tiktok.com" target="_blank">
                <img src="imagenes/tiktok.png" alt="TikTok">
            </a>
            <a href="https://wa.me/1234567890" target="_blank">
                <img src="imagenes/whatsapp.png" alt="WhatsApp">
            </a>
        </div>
        <div class="contact-info">
            <p>Teléfono: <a href="tel:+50212345678">+502 1234-5678</a></p>
            <p>Correo: <a href="mailto:info@laxtravel.com">info@laxtravel.com</a></p>
        </div>
    </div>
    <div class="buttons">
        <!-- Botones de los servicios -->
        <button class="button" onclick="mostrarRequisitos('requisitos-visa-americana')">Visa americana</button>
        <button class="button" onclick="mostrarRequisitos('requisitos-visa-mexicana')">Visa mexicana</button>
        <button class="button" onclick="mostrarRequisitos('requisitos-visa-canadiense')">Visa canadiense</button>
        <button class="button" onclick="mostrarRequisitos('requisitos-pasaporte-guatemalteco')">Pasaporte guatemalteco</button>
        <button class="button" onclick="mostrarRequisitos('requisitos-pasaporte-americano')">Pasaporte americano</button>
        <button class="button" onclick="mostrarRequisitos('requisitos-maletas')">Maletas</button>
        <button class="button" onclick="mostrarRequisitos('requisitos-envios')">Envíos a USA</button>
    </div>
    <div id="requisitos-visa-americana" class="requisitos">
        <h2>Requisitos para Visa Americana</h2>
        <ul>
            <li>Pasaporte vigente</li>
            <li>Copia de DPI</li>
            <li>Formulario DS-160</li>
            <li>Comprobante de pago de la tarifa</li>
            <li>Fotografía reciente</li>
        </ul>
    </div>
    <!-- Agrega aquí más secciones de requisitos -->
    <div class="footer">
        <p>Síguenos en nuestras redes sociales:</p>
        <a href="https://facebook.com" target="_blank">Facebook</a>
        <a href="https://instagram.com" target="_blank">Instagram</a>
        <a href="https://tiktok.com" target="_blank">TikTok</a>
        <a href="https://wa.me/1234567890" target="_blank">WhatsApp</a>
    </div>
</body>
</html>
