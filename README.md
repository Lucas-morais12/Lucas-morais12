<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Loja de Materiais de Construção</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem 0;
        }

        h1 {
            margin: 0;
        }

        .container {
            width: 90%;
            margin: auto;
            padding: 20px;
        }

        .products {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: space-around;
        }

        .product {
            background-color: white;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 8px;
            width: 30%;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .product img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
        }

        .product h2 {
            font-size: 18px;
            margin: 15px 0;
        }

        .product p {
            font-size: 16px;
            color: #555;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem;
            margin-top: 40px;
        }
    </style>
</head>

<body>

    <header>
        <h1>Loja de Materiais de Construção</h1>
    </header>

    <div class="container">
        <h2>Confira nossos Produtos</h2>

        <div class="products">
            <div class="product">
                <img src="https://via.placeholder.com/300x200?text=Tijolo" alt="Tijolo">
                <h2>Tijolo 8 Furos</h2>
                <p>Preço: R$ 1,50/unidade</p>
            </div>

            <div class="product">
                <img src="https://via.placeholder.com/300x200?text=Cimento" alt="Cimento">
                <h2>Cimento CP II</h2>
                <p>Preço: R$ 25,00/saco</p>
            </div>

            <div class="product">
                <img src="https://via.placeholder.com/300x200?text=Piso+Cerâmico" alt="Piso Cerâmico">
                <h2>Piso Cerâmico 50x50cm</h2>
                <p>Preço: R$ 35,00/m²</p>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 Loja de Materiais de Construção - Todos os direitos reservados.</p>
    </footer>

</body>

</html>

