<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Tienda en línea de ropa, accesorios y peluches">
    <title>Mi Tienda</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #e0f7fa; /* Fondo azul claro */
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #0288d1; /* Azul oscuro */
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #0277bd;
            padding: 15px;
            text-align: center;
        }
        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
        }
        .hero {
            background-color: #0288d1;
            color: #fff;
            padding: 100px 20px;
            text-align: center;
        }
        .hero h1 {
            font-size: 3rem;
            margin: 0;
        }
        .hero p {
            font-size: 1.5rem;
            margin: 20px 0;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 50px 20px;
        }
        .product {
            background-color: #fff;
            border: 1px solid #ccc;
            border-radius: 10px;
            margin: 20px;
            padding: 20px;
            width: 300px;
            text-align: center;
        }
        .product img {
            width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .product h2 {
            color: #0288d1;
        }
        .product p {
            color: #666;
        }
        footer {
            background-color: #0277bd;
            color: #fff;
            text-align: center;
            padding: 20px;
            margin-top: 50px;
        }
        .yellow-highlight {
            color: #ffeb3b; /* Amarillo */
        }
        button {
            background-color: #ffeb3b;
            color: #000;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            border-radius: 5px;
            margin-top: 10px;
        }
        button:hover {
            background-color: #fbc02d;
        }
    </style>
</head>
<body>

    <header>
        <h1>Bienvenido a Mi Tienda</h1>
    </header>

    <nav>
        <a href="#">Inicio</a>
        <a href="#">Productos</a>
        <a href="#">Contacto</a>
    </nav>

    <section class="hero">
        <h1>Encuentra tu estilo <span class="yellow-highlight">perfecto</span></h1>
        <p>Ropa, accesorios y peluches a tu alcance</p>
        <button>Comprar ahora</button>
    </section>

    <section class="products">
        <div class="product">
            <img src="https://via.placeholder.com/300x300" alt="Producto 1">
            <h2>Camiseta Azul</h2>
            <p>$20.00</p>
            <button>Agregar al carrito</button>
        </div>

        <div class="product">
            <img src="https://via.placeholder.com/300x300" alt="Producto 2">
            <h2>Gorro de Lana</h2>
            <p>$15.00</p>
            <button>Agregar al carrito</button>
        </div>

        <div class="product">
            <img src="https://via.placeholder.com/300x300" alt="Producto 3">
            <h2>Peluche Oso</h2>
            <p>$25.00</p>
            <button>Agregar al carrito</button>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Mi Tienda. Todos los derechos reservados.</p>
    </footer>

</body>
</html>
