<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Comida Divina - Restaurante Saludable</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        nav {
            background-color: #333;
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px 0;
        }
        .section-title {
            text-align: center;
            margin-bottom: 20px;
        }
        .menu-item {
            display: flex;
            justify-content: space-between;
            background-color: #fff;
            margin: 10px 0;
            padding: 10px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .menu-item img {
            width: 100px;
            height: 100px;
            object-fit: cover;
        }
        .footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .price {
            font-weight: bold;
            color: #4CAF50;
        }
        form {
            background-color: #fff;
            padding: 20px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            border-radius: 5px;
            max-width: 600px;
            margin: 0 auto;
        }
        form label {
            display: block;
            margin: 10px 0 5px;
        }
        form input, form select, form textarea, form button {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        form button {
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
        }
        form button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

<header>
    <h1>Bienvenidos a Comida Divina</h1>
    <p>Disfruta de una experiencia única con comida saludable y deliciosa</p>
</header>

<nav>
    <a href="#inicio">Inicio</a>
    <a href="#menu">Menú</a>
    <a href="#nosotros">Nosotros</a>
    <a href="#pedido">Realizar Pedido</a>
    <a href="#contacto">Contacto</a>
</nav>


<footer class="footer">
    <p>&copy; 2025 Comida Divina. Todos los derechos reservados.</p>
</footer>

<script>
    document.getElementById('pedido-form').addEventListener('submit', function(e) {
        e.preventDefault();
        alert('¡Tu pedido ha sido enviado con éxito!');
    });
</script>    <div class="container" id="inicio">
        <h2 class="section-title">Comida saludable, natural y deliciosa</h2>
        <p>En Comida Divina nos especializamos en ofrecerte platillos saludables, frescos y llenos de sabor, perfectos para cuidar tu salud sin sacrificar el placer de comer bien. ¡Ven y descubre nuestros deliciosos platillos! Comida divina es una empresa innovadora dedicada a ofrecer soluciones de alimentación saludable para personas que buscan mejorar su bienestar y calidad de vida. Con el compromiso de promover una alimentación equilibrada y sostenible, Comida divina ofrece una amplia gama de productos frescos, nutritivos y orgánicos, preparados sin aditivos ni conservantes artificiales.</p>
    </div>

    <div class="container" id="menu">
        <h2 class="section-title">Nuestro Menú</h2>

        <h3>Desayuno</h3>

        <div class="menu-item">
            <div>
                <h3>Yogurt Griego con Granola y Frutas</h3>
                <p>Yogurt griego natural acompañado de granola crujiente y frutas frescas.</p>
                <button onclick="showBenefits('benefit1')">Beneficios</button>
             </div> 
            <div class="price">$45</div>
            <img src="https://usaelectrodomesticos.com.co/wp-content/uploads/2022/10/yogur-griego-frutas-cereal.jpg" alt="Yogurt Griego con Granola y Frutas">
        </div>

        <div id="benefit1" class="benefits">
            <p>Este platillo es rico en proteínas, vitaminas y antioxidantes. Ayuda a mejorar la digestión y aporta energía sostenida.</p>
        </div>

        <div class="menu-item">
            <div>
                <h3>Avena con Frutas y Nueces</h3>
                <p>Avena cocida con una mezcla de frutas de temporada y nueces, un desayuno lleno de energía.</p>
                <button onclick="showBenefits('benefit2')">Beneficios</button>
            </div>
            <div class="price">$40</div>
            <img src="https://st1.uvnimg.com/e9/73/2973c7194ac8ae99af6b95e8703c/26-avena-con-fruta-y-nueces.jpg" alt="Avena con Frutas y Nueces">
        </div>

        <div id="benefit2" class="benefits">
            <p>La avena es una fuente excelente de fibra que mejora la digestión, mientras que las frutas y nueces aportan vitaminas y grasas saludables.</p>
        </div>

        <div class="menu-item">
            <div>
                <h3>Tortillas de Verduras</h3>
                <p>Tortillas de maíz rellenas de verduras frescas, un desayuno ligero y saludable.</p>
                <button onclick="showBenefits('benefit2')">Beneficios</button>
            </div>
            <div class="price">$50</div>
            <img src="https://th.bing.com/th/id/R.88fbd0da83cdd35c211694aa968e7010?rik=O%2fLr8N6oML0%2foQ&riu=http%3a%2f%2f4.bp.blogspot.com%2f-Rypu_ui8wak%2fVZ7HAlNK9bI%2fAAAAAAAAmLM%2fv5GgUDRosrk%2fs1600%2fDSC_4444.jpg&ehk=yItWZA%2f6Jh%2fgWek11tqrwqFNsi2uU2pRBPI4%2fhGl8bY%3d&risl=&pid=ImgRaw&r=0" alt="Tortillas de Verduras">
        </div>

        <div id="benefit2" class="benefits">
            <p>Al incorporar diferentes verduras, obtienes una variedad de vitaminas (como A, C y K), minerales (como potasio y magnesio) y antioxidantes que son esenciales para la salud.</p>
        </div>

        <h3>Ensaladas</h3>

        <div class="menu-item">
            <div>
                <h3>Ensalada de Pollo a la Parrilla</h3>
                <p>Pechuga de pollo a la parrilla, acompañada de una mezcla de hojas verdes y aderezo ligero.</p>
                <button onclick="showBenefits('benefit2')">Beneficios</button>
            </div>

            <div class="price">$80</div>
            <img src="https://th.bing.com/th/id/OIP.nO_Lx1yddkfcDTwwfBSwcgHaDx?rs=1&pid=ImgDetMain" alt="Ensalada de Pollo a la Parrilla">
        </div>

        <div id="benefit2" class="benefits">
            <p>Al cocinar el pollo a la parrilla, puedes reducir el contenido de grasa en comparación con otros métodos de cocción, como freír.</p>
        </div>

        <div class="menu-item">
            <div>
                <h3>Ensalada de Quinoa y Verduras</h3>
                <p>Quinoa, tomate, pepino, espinaca y zanahoria con un toque de limón y aceite de oliva.</p>
                <button onclick="showBenefits('benefit2')">Beneficios</button>
            </div>
            <div class="price">$70</div>
            <img src="https://www.vidactual.com/rcpmaker/wp-content/uploads/2019/06/Ensalada-de-quinoa-con-verduras-768x512.jpg" alt="Ensalada de Quinoa y Verduras">
        </div>
    
        <div id="benefit2" class="benefits">
            <p>La quinoa es rica en fibra, lo que ayuda a mejorar la digestión, regular el tránsito intestinal y mantener la sensación de saciedad.</p>
        </div>

        <h3>Postres</h3>

        <div class="menu-item">
            <div>
                <h3>Frutas Frescas con Yogurt Griego</h3>
                <p>Una mezcla de frutas frescas con yogurt griego para un postre saludable.</p>
                <button onclick="showBenefits('benefit2')">Beneficios</button>
            </div>
            <div class="price">$40</div>
            <img src="https://th.bing.com/th/id/OIP.P95KyjRnkZwWvtaYMnOj4wHaFZ?rs=1&pid=ImgDetMain" alt="Frutas Frescas con Yogurt Griego">
        </div>

        <div id="benefit2" class="benefits">
            <p>Si eliges un yogur griego bajo en grasa, puedes disfrutar de un postre o snack saludable que no aporta muchas calorías ni grasas saturadas.</p>
        </div>

        <div class="menu-item">
            <div>
                <h3>Chía con Leche de Almendras y Frutas</h3>
                <p>Pudín de chía preparado con leche de almendras, decorado con frutas frescas.</p>
                <button onclick="showBenefits('benefit2')">Beneficios</button>
            </div>
            <div class="price">$45</div>
            <img src="https://consalyazucar.com/cdn/recipes/pudin_de_chia_con_frutos_rojos.jpg" alt="Chía con Leche de Almendras y Frutas">
        </div>

        <div id="benefit2" class="benefits">
            <p>Las semillas de chía son ricas en fibra, lo que ayuda a mejorar la digestión, mantener la sensación de saciedad y regular el tránsito intestinal.</p>
        </div>

        <h3>Jugos</h3>

        <div class="menu-item">
            <div>
                <h3>Jugo de Naranja</h3>
                <p>Jugo fresco de naranja natural, lleno de vitamina C.</p>
                <button onclick="showBenefits('benefit2')">Beneficios</button>
            </div>
            <div class="price">$24</div>
            <img src="https://i.pinimg.com/originals/67/25/47/6725470f6a12b03c7b8f15449632f657.jpg" alt="Jugo de Naranja">
        </div>
     
        <div id="benefit2" class="benefits">
            <p>El jugo de naranja es una excelente fuente de vitamina C, que es fundamental para el sistema inmunológico, ayuda a combatir resfriados y promueve la salud de la piel.</p>
        </div>

        <div class="menu-item">
            <div>
                <h3>Jugo de Zanahoria</h3>
                <p>Jugo natural de zanahoria, ideal para mejorar la salud visual.</p>
                <button onclick="showBenefits('benefit2')">Beneficios</button>
            </div>
            <div class="price">$28</div>
            <img src="https://cdn2.cocinadelirante.com/sites/default/files/styles/gallerie/public/beneficios-y-propiedades-del-jugo-de-zanahoria.jpg" alt="Jugo de Zanahoria">
        </div>

        <div id="benefit2" class="benefits">
            <p>El jugo de zanahoria es una excelente fuente de betacaroteno, que el cuerpo convierte en vitamina A. Esta vitamina es esencial para la salud visual, la piel y el sistema inmunológico.</p>
        </div>


        <div class="menu-item">
            <div>
                <h3>Jugo de Fresa, Piña y Banano</h3>
                <p>Combinación deliciosa de fresa, piña y banano, lleno de antioxidantes.</p>
                <button onclick="showBenefits('benefit2')">Beneficios</button>
            </div>
            <div class="price">$30</div>
            <img src="https://th.bing.com/th/id/OIP.NEyI0-fw3N-6UlGMSJH3YQHaJe?rs=1&pid=ImgDetMain" alt="Jugo de Fresa, Piña y Banano">
        </div>

        <div id="benefit2" class="benefits">
            <p>Este jugo es una excelente fuente de vitamina C, especialmente de las fresas y la piña, que fortalece el sistema inmunológico y ayuda en la salud de la piel.</p>
        </div>


        <h3>Tés Herbales</h3>

        <div class="menu-item">
            <div>
                <h3>Té de Manzanilla</h3>
                <p>Té relajante de manzanilla, ideal para la digestión y la calma.</p>
                <button onclick="showBenefits('benefit2')">Beneficios</button>
            </div>
            <div class="price">$20</div>
            <img src="https://th.bing.com/th/id/OIP.aZpzFTlavGoLlBpcg1vRhwHaFE?rs=1&pid=ImgDetMain" alt="Té de Manzanilla">
        </div>

        <div id="benefit2" class="benefits">
            <p>La manzanilla es conocida por sus efectos relajantes. Puede ayudar a reducir la ansiedad y el estrés, lo que lo convierte en una excelente opción para disfrutar antes de dormir.</p>
        </div>


        <div class="menu-item">
            <div>
                <h3>Té de Menta</h3>
                <p>Té refrescante de menta, perfecto para después de las comidas.</p>
                <button onclick="showBenefits('benefit2')">Beneficios</button>
            </div>
            <div class="price">$22</div>
            <img src="https://th.bing.com/th/id/OIP.Qt0mL5J_HZ3yVmNfAIzP_AHaEk?rs=1&pid=ImgDetMain" alt="Té de Menta">
        </div>

        <div id="benefit2" class="benefits">
            <p>Inhalar el aroma del té de menta o beberlo puede ayudar a aliviar dolores de cabeza y migrañas, gracias a sus propiedades analgésicas y relajantes.</p>
        </div>

        <div class="menu-item">
            <div>
                <h3>Té de Jengibre</h3>
                <p>Té picante de jengibre, ideal para mejorar la circulación y la energía.</p>
                <button onclick="showBenefits('benefit2')">Beneficios</button>
            </div>
            <div class="price">$25</div>
            <img src="https://1.bp.blogspot.com/-9IS1lvzRIKk/XA7bbKu4X7I/AAAAAAAAAJ0/q7Zk_01EhfEGX2Zf2dDv8PyqSEtSiqz2wCLcBGAs/w1200-h630-p-k-no-nu/2222%2B%25281%2529.jpg" alt="Té de Jengibre">
        </div>

        <div id="benefit2" class="benefits">
            <p>El té de jengibre es conocido por su efectividad para aliviar las náuseas, ya sea por mareos, malestar estomacal o durante el embarazo (con el consentimiento del médico).</p>
        </div>

        <h3>Agua Fusionada</h3>

        <div class="menu-item">
            <div>
                <h3>Agua de Limón y Menta</h3>
                <p>Agua fresca con limón y un toque de menta, perfecta para hidratarte.</p>
                <button onclick="showBenefits('benefit2')">Beneficios</button>
            </div>
            <div class="price">$15</div>
            <img src="https://tiempo.hn/wp-content/uploads/2021/03/WhatsApp-Image-2021-03-23-at-3.13.12-PM-1.jpeg" alt="Agua de Limón y Menta">
        </div>

         <div id="benefit2" class="benefits">
            <p> Esta bebida es una forma deliciosa de mantenerse hidratado, lo que es esencial para el funcionamiento óptimo del cuerpo.</p>
        </div>

        <div class="menu-item">
            <div>
                <h3>Agua de Frutas</h3>
                <p>Agua infusionada con una mezcla de frutas frescas para un sabor natural.</p>
                <button onclick="showBenefits('benefit2')">Beneficios</button>
            </div>
            <div class="price">$18</div>
            <img src="https://www.losvinos.com.ar/wp-content/uploads/2020/07/infusiones-fruta-1024x595.jpg" alt="Agua de Frutas">
        </div>

        <div id="benefit2" class="benefits">
            <p>El agua de frutas ayuda a mantenerte hidratado, lo que es fundamental para el funcionamiento óptimo del cuerpo, especialmente en días calurosos o después de hacer ejercicio.</p>
        </div>

        <div class="menu-item">
            <div>
                <h3>Agua de Jengibre y Limón</h3>
                <p>Refrescante agua infusionada con jengibre y limón, ideal para desintoxicarte.</p>
                 <button onclick="showBenefits('benefit2')">Beneficios</button>
            </div>
            <div class="price">$20</div>
            <img src="https://www.cardamomo.news/__export/1675535011538/sites/debate/img/2023/02/04/agua_de_jengibre_con_limon.png_976912859.png" alt="Agua de Jengibre y Limón">
        </div>

        <div id="benefit2" class="benefits">
            <p>El jengibre puede ayudar a aliviar problemas digestivos, como la indigestión y las náuseas. Además, el limón estimula la producción de bilis, lo que favorece la digestión.</p>
        </div>

    </div>

     <div class="container" id="nosotros">
        <h2 class="section-title">Sobre Nosotros</h2>
        <p>En Comida Divina, nuestra misión es ofrecer soluciones alimentarias saludables y deliciosas que contribuyan al bienestar integral de nuestros clientes. Nos dedicamos a proporcionar alimentos frescos, naturales y nutritivos, elaborados con ingredientes orgánicos y de la más alta calidad, sin aditivos ni conservantes artificiales.</p>
    </div>

    <div class="container" id="contacto">
        <h2 class="section-title">Contacto</h2>
        <p><strong>Teléfono:</strong> 9231280393</p>
        <p><strong>Dirección:</strong> CALLE, PROLONGACION BRASCILO, COLONIA: KILOMETRO 2</p>
    </div>

        <div class="container" id="pedido">
    <h2 class="section-title">Realizar un Pedido</h2>
    <form id="pedido-form">
        <label for="nombre">Nombre completo:</label>
        <input type="text" id="nombre" name="nombre" placeholder="Tu nombre" required>

        <label for="direccion">Dirección de entrega:</label>
        <input type="text" id="direccion" name="direccion" placeholder="Tu dirección" required>

        <label for="telefono">Teléfono:</label>
        <input type="tel" id="telefono" name="telefono" placeholder="Tu número de teléfono" required>

        <label for="pedido">Selecciona tu pedido:</label>
        <select id="pedido" name="pedido" required>
            <option value="">Selecciona un platillo</option>
            <option value="yogurt">Yogurt Griego con Granola y Frutas</option>
            <option value="avena">Avena con Frutas y Nueces</option>
            <option value="ensalada_pollo">Ensalada de Pollo a la Parrilla</option>
            <option value="ensalada_quinoa">Ensalada de Quinoa y Verduras</option>
            <option value="jugo_naranja">Jugo de Naranja</option>
            <option value="jugo_zanahoria">Jugo de Zanahoria</option>
        </select>

        <label for="notas">Notas adicionales:</label>
        <textarea id="notas" name="notas" placeholder="Escribe cualquier detalle adicional"></textarea>

        <button type="submit">Enviar Pedido</button>
    </form>
    </div>


<div class="container" id="nosotros">
    <h2 class="section-title">Sobre Nosotros</h2>
    <p>En Comida Divina, nuestra misión es ofrecer soluciones alimentarias saludables y deliciosas...</p>
</div>

<footer class="footer">
    <p>&copy; 2025 Comida Divina. Todos los derechos reservados.</p>
</footer>

<script>
    document.getElementById('pedido-form').addEventListener('submit', function(e) {
        e.preventDefault();
        alert('¡Tu pedido ha sido enviado con éxito!');
    });
</script>

</body>
</html>
