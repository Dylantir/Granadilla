<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Granadilla - Sostenibilidad y Nutrición</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f3f4ed;
            color: #333;
        }
        header {
            background-color: #ffcb77;
            padding: 20px;
            text-align: center;
            color: #fff;
        }
        header h1 {
            margin: 0;
            font-size: 36px;
            color: #333;
        }
        nav {
            background-color: #f4a261;
            padding: 10px;
            display: flex;
            justify-content: space-around;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
            padding: 10px;
        }
        nav a:hover {
            background-color: #e76f51;
            border-radius: 5px;
        }
        .container {
            padding: 20px;
            margin: auto;
        }
        section {
            display: none;
            padding: 20px;
            border-bottom: 2px solid #ccc;
        }
        section.active {
            display: block;
        }
        h2 {
            color: #2a9d8f;
            font-size: 28px;
        }
        p {
            font-size: 18px;
            line-height: 1.6;
            margin: 10px 0;
        }
        .highlight {
            font-weight: bold;
            color: #e76f51;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #ffcb77;
            color: #fff;
        }
        img {
            width: 100%;
            height: auto;
            margin: 10px 0;
        }
        .two-columns {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        .two-columns div {
            flex: 0 1 48%;
            margin: 10px 0;
        }
    </style>
</head>
<body>

    <!-- Encabezado principal -->
    <header>
        <h1>Gomitas de Granadilla - Saludables y Ecológicas</h1>
    </header>

    <!-- Menú de navegación -->
    <nav>
        <a href="#" onclick="cambiarPestana('inicio')">Inicio</a>
        <a href="#" onclick="cambiarPestana('infoGeneral')">Información General</a>
        <a href="#" onclick="cambiarPestana('cultivo')">Cultivo</a>
        <a href="#" onclick="cambiarPestana('usos')">Usos</a>
        <a href="#" onclick="cambiarPestana('producto')">Producto</a>
        <a href="#" onclick="cambiarPestana('precios')">Precios del Mercado</a>
    </nav>

    <!-- Contenido principal -->
    <div class="container">
        <!-- Sección de Inicio -->
        <section id="inicio" class="active">
            <h2>Granadilla: Deliciosa y Sostenible</h2>
            <div class="two-columns">
                <div>
                    <p>La <span class="highlight">granadilla</span>, una fruta exótica originaria de la región andina, es reconocida no solo por su sabor dulce y suave, sino también por sus numerosos beneficios para la salud y su potencial en diversas industrias.</p>
                    <p>Nuestra empresa se ha inspirado en esta fruta para crear un producto innovador: <span class="highlight">gomitas rellenas de granadilla</span>, empaquetadas en un material biodegradable elaborado a partir de la cáscara de la misma fruta.</p>
                </div>
                <div>
                    <img src="granadilla_inicio.jpg" alt="Granadilla fresca">
                </div>
            </div>
        </section>

        <!-- Sección de Información General -->
        <section id="infoGeneral">
            <h2>Información General</h2>
            <div class="two-columns">
                <div>
                    <p><strong>Nombre científico:</strong> <span class="highlight">Passiflora ligularis</span>.</p>
                    <p><strong>Origen:</strong> Países andinos como <span class="highlight">Colombia</span>, <span class="highlight">Ecuador</span> y <span class="highlight">Perú</span>, con gran adaptabilidad a otras regiones tropicales.</p>
                    <p>El nombre refleja su parentesco con otras frutas como el maracuyá y la gulupa, conocidas por sus beneficios nutricionales y sus usos en la gastronomía.</p>
                </div>
                <div>
                    <img src="granadilla_info.jpg" alt="Beneficios de la granadilla">
                </div>
            </div>
            <p>La granadilla es rica en <strong>antioxidantes</strong>, <strong>vitaminas A, C y E</strong>, lo que ayuda a mejorar la salud ocular, fortalecer el sistema inmunológico y proteger las células del daño por radicales libres.</p>
        </section>

        <!-- Sección de Cultivo -->
        <section id="cultivo">
            <h2>Cultivo de la Granadilla</h2>
            <div class="two-columns">
                <div>
                    <p><strong>Condiciones ideales de cultivo:</strong> Prosperan en suelos fértiles entre los <span class="highlight">1,200 y 2,400 metros</span> de altitud con temperaturas entre <span class="highlight">18°C y 24°C</span>.</p>
                    <p>Variedades más conocidas: <span class="highlight">criolla</span> (frutos más grandes y dulces) y <span class="highlight">común</span> (más ácida y resistente).</p>
                </div>
                <div>
                    <img src="cultivo_granadilla.jpg" alt="Cultivo de granadilla">
                </div>
            </div>
        </section>

        <!-- Sección de Usos -->
        <section id="usos">
            <h2>Usos de la Granadilla</h2>
            <div class="two-columns">
                <div>
                    <p>La granadilla tiene múltiples <strong>aplicaciones en la industria alimentaria</strong>, como jugos, postres y ensaladas. Además, es un ingrediente clave en nuestras <span class="highlight">gomitas rellenas</span>, combinando sabor y beneficios nutricionales.</p>
                </div>
                <div>
                    <img src="usos_granadilla.jpg" alt="Usos de la granadilla en cosmética">
                </div>
            </div>
            <p><strong>En cosmética</strong>, se usan las semillas como exfoliantes naturales y los extractos de la pulpa para productos de cuidado de la piel, ricos en antioxidantes y humectantes.</p>
        </section>

        <!-- Sección de Producto -->
        <section id="producto">
            <h2>Gomitas Rellenas de Granadilla</h2>
            <p>Nuestras <strong>gomitas</strong> son una opción saludable y ecológica, hechas con <strong>pulpa de granadilla</strong>. Ofrecen vitaminas y antioxidantes, protegiendo las células y fortaleciendo el sistema inmunológico.</p>
            <img src="gomitas_granadilla.jpg" alt="Gomitas de granadilla">
            <p>El empaque biodegradable hecho de la cáscara de la fruta es una solución innovadora que <strong>reduce el impacto ambiental</strong> y aprovecha los residuos orgánicos del proceso de producción.</p>
        </section>

        <!-- Sección de Precios del Mercado -->
        <section id="precios">
            <h2>Precios del Mercado</h2>
            <div class="two-columns">
                <div>
                    <p>El precio de la granadilla en los <strong>mercados locales</strong> varía entre <span class="highlight">$2 y $4 USD por kilogramo</span>, mientras que para <strong>exportación</strong> puede alcanzar los <span class="highlight">$6 USD por kilogramo</span>.</p>
                    <p>Los principales mercados incluyen Europa, Estados Unidos y Canadá.</p>
                </div>
                <div>
                    <img src="precios_granadilla.jpg" alt="Precios del mercado">
                </div>
            </div>
        </section>
    </div>

    <!-- Pie de página -->
    <footer>
        <p>Creador: Dylan Tirado</p>
    </footer>

    <script>
        // Función para cambiar las pestañas
        function cambiarPestana(pestanaId) {
            // Ocultar todas las secciones
            const secciones = document.querySelectorAll('section');
            secciones.forEach(section => section.classList.remove('active'));
            
            // Mostrar la sección seleccionada
            document.getElementById(pestanaId).classList.add('active');
        }
    </script>
</body>
</html>
