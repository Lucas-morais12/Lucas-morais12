<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loja de Materiais de Construção</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #3E8E41;
            color: white;
            padding: 15px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #2C6F2D;
            padding: 10px;
        }
        nav a {
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            text-transform: uppercase;
            font-weight: bold;
        }
        nav a:hover {
            background-color: #45a049;
        }
        .container {
            padding: 20px;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .product {
            background-color: white;
            margin: 15px;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
            width: 30%;
        }
        .product img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }
        .product h3 {
            margin: 10px 0;
            color: #333;
        }
        .product p {
            color: #666;
        }
        footer {
            background-color: #3E8E41;
            color: white;
            text-align: center;
            padding: 20px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .contact-form {
            background-color: #fff;
            padding: 20px;
            margin-top: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }
        .contact-form label {
            display: block;
            margin: 10px 0 5px;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border-radius: 5px;
            border: 1px solid #ddd;
        }
        .contact-form button {
            background-color: #3E8E41;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .contact-form button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

<header>
    <h1>Construções ABC</h1>
    <p>A melhor loja de materiais de construção da região</p>
</header>

<nav>
    <a href="#">Início</a>
    <a href="#">Produtos</a>
    <a href="#">Sobre Nós</a>
    <a href="#">Contato</a>
</nav>

<div class="container">
    <h2>Nossos Produtos</h2>
    <div class="products">
        <div class="product">
            <img src="tijolo.jpg" alt="Tijolos">
            <h3>Tijolos</h3>
            <p>Alta qualidade e durabilidade para a sua construção.</p>
        </div>
        <div class="product">
            <img src="cimento.jpg" alt="Cimento">
            <h3>Cimento</h3>
            <p>O melhor cimento para qualquer obra, resistente e duradouro.</p>
        </div>
        <div class="product">
            <img src="telha.jpg" alt="Telhas">
            <h3>Telhas</h3>
            <p>Proteja seu projeto com nossas telhas de alta qualidade.</p>
        </div>
    </div>

    <h2>Fale Conosco</h2>
    <div class="contact-form">
        <form action="submit_form.php" method="post">
            <label for="name">Nome:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Mensagem:</label>
            <textarea id="message" name="message" rows="4" required></textarea>

            <button type="submit">Enviar</button>
        </form>
    </div>
</div>

<footer>
    <p>&copy; 2024 Construções ABC. Todos os direitos reservados.</p>
</footer>

</body>
</html>
