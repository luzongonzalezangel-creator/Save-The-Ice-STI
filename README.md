<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>STI - Save The Ice</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background: #f4f9fb;
            color: #0b2c3d;
        }

        header {
            background: linear-gradient(135deg, #0d3b66, #1d6fa5);
            color: white;
            text-align: center;
            padding: 40px 20px;
        }

        header img {
            width: 140px;
            margin-bottom: 15px;
        }

        header h1 {
            margin: 10px 0 5px 0;
            font-size: 2.5em;
            letter-spacing: 3px;
        }

        section {
            padding: 50px 20px;
            max-width: 1100px;
            margin: auto;
        }

        .mission {
            text-align: center;
            font-size: 1.2em;
            line-height: 1.6;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
        }

        .gallery img {
            width: 100%;
            border-radius: 10px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.2);
        }

        .donation {
            background: #e0f4ff;
            text-align: center;
            border-radius: 15px;
            padding: 40px 20px;
        }

        .donation input {
            padding: 10px;
            width: 200px;
            border-radius: 8px;
            border: 1px solid #ccc;
            margin-right: 10px;
        }

        .donation button {
            padding: 10px 20px;
            border: none;
            border-radius: 8px;
            background: #0d3b66;
            color: white;
            font-size: 1em;
            cursor: pointer;
        }

        .donation button:hover {
            background: #144f86;
        }

        footer {
            background: #0d3b66;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
    </style>
</head>
<body>

<header>
    <img src="logo.png" alt="Logo de mi empresa" width="200">

    <h1>STI</h1>
    <p>Save The Ice</p>
</header>

<section class="mission">
    <h2>Nuestra Misión</h2>
    <p>
       Proteger y preservar los ecosistemas polares mediante la defensa activa del hielo antártico, reconociendo su papel fundamental en la regulación del clima global y en el equilibrio de la biodiversidad del planeta.

Impulsamos la investigación científica independiente y colaborativa para generar conocimiento riguroso que permita comprender, monitorear y mitigar los efectos del cambio climático en las regiones polares. Promovemos la educación ambiental como herramienta de transformación social, fomentando la conciencia ecológica, la responsabilidad colectiva y el compromiso ciudadano a nivel local e internacional.

Trabajamos para movilizar a gobiernos, organizaciones y comunidades hacia una acción climática urgente, efectiva y basada en evidencia, desarrollando iniciativas sostenibles, campañas de sensibilización y proyectos de conservación que protejan los océanos, la fauna polar y los ecosistemas asociados.

Nuestro propósito es garantizar un futuro sostenible para las próximas generaciones, defendiendo el hielo antártico como símbolo de estabilidad climática, justicia ambiental y esperanza para el planeta.
    </p>
</section>

<section>
    <h2 style="text-align:center;">Ecosistemas Polares</h2>
    <div class="gallery">
        <img src="https://hips.hearstapps.com/hmg-prod/images/icebergs-floating-in-the-sea-in-antarctic-greenland-royalty-free-image-1701103285.jpg?crop=0.76357xw:1xh;center,top&resize=1200:*" alt="Iceberg">
        <img src="https://www.lavanguardia.com/files/content_image_mobile_filter/uploads/2025/01/29/679a0404b560f.jpeg" alt="Antártida">
        <img src="https://www.fundeu.es/wp-content/uploads/2024/09/reco-antartida-antartica-pixabay-alkalenski.png" alt="Glaciar">
    </div>
</section>

<section class="donation">
    <h2>Apoya Nuestra Causa</h2>
    <p>Tu contribución ayuda a proteger el hielo antártico y combatir el cambio climático.</p>
    
    <input type="number" placeholder="Monto en USD">
    <button onclick="donar()">Donar</button>

    <p id="mensajeDonacion" style="margin-top:20px;font-weight:bold;"></p>
</section>

<footer>
    © 2026 STI - Save The Ice | Protección del hielo, protección del planeta
</footer>

<script>
    function donar() {
        const mensaje = document.getElementById("mensajeDonacion");
        mensaje.innerHTML = "¡Gracias por tu donación! (Simulación de pago realizada)";
    }
</script>

</body>
</html>

git remote add origin https://github.com/luzongonzalezangel-creator/Save-The-Ice-STI.git
git branch -M main
git push -u origin main
git remote add origin 
git branch -M main
git push -u origin main
