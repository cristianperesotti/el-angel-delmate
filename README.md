# el-angel-delmate
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>El Ángel del Mate</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #5e4033;
            color: #fff;
            text-align: center;
            padding: 30px 0;
        }
        .container {
            max-width: 1200px;
            margin: auto;
            padding: 20px;
        }
        .product {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            margin-top: 30px;
        }
        .product-item {
            background: #fff;
            border: 1px solid #ddd;
            border-radius: 12px;
            padding: 20px;
            margin: 10px;
            width: 280px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            text-align: center;
        }
        .product-item img {
            width: 100%;
            border-radius: 8px;
        }
        .product-item h3 {
            margin: 15px 0 5px;
        }
        .product-item p {
            color: #555;
            margin-bottom: 10px;
        }
        .price {
            font-size: 1.3em;
            font-weight: bold;
            color: #5e4033;
        }
        .buy-button {
            background-color: #8b5e3c;
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 6px;
            text-decoration: none;
            display: inline-block;
            margin-top: 10px;
        }
        .buy-button:hover {
            background-color: #6f4229;
        }
    </style>
</head>
<body>

    <header>
        <h1>El Ángel del Mate</h1>
        <p>Calidez artesanal en cada sorbo</p>
    </header>

    <div class="container">
        <div class="product">
            <!-- Producto 1 -->
            <div class="product-item">
                <img src="mate1.jpg" alt="Mate de Madera">
                <h3>Mate de Madera</h3>
                <p>Tradicional, rústico y bien criollo. Ideal para cebadas largas.</p>
                <p class="price">$1200</p>
                <a class="buy-button" href="https://pagar.ualabis.com.ar/order/08a2b11a4d56923fef74db4d78536c1e403010771588d4e4" target="_blank">Comprar</a>
            </div>

            <!-- Producto 2 -->
            <div class="product-item">
                <img src="mate2.jpg" alt="Mate de Cerámica">
                <h3>Mate de Cerámica</h3>
                <p>Elegante y fácil de limpiar. Perfecto para regalar.</p>
                <p class="price">$1500</p>
                <a class="buy-button" href="https://pagar.ualabis.com.ar/order/08a2b11a4d56923fef74db4d78536c1e403010771588d4e4" target="_blank">Comprar</a>
            </div>

            <!-- Producto 3 -->
            <div class="product-item">
                <img src="mate3.jpg" alt="Mate de Acero">
                <h3>Mate de Acero Inoxidable</h3>
                <p>Moderno y resistente. Mantiene la temperatura por más tiempo.</p>
                <p class="price">$1800</p>
                <a class="buy-button" href="https://pagar.ualabis.com.ar/order/08a2b11a4d56923fef74db4d78536c1e403010771588d4e4" target="_blank">Comprar</a>
            </div>
        </div>
    </div>

</body>
</html>