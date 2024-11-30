<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Carinhoso Bordados</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Geral */
body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f5;
    margin: 0;
    padding: 0;
}

/* Cabeçalho */
header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    background-color: #fff;
    padding: 10px 20px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.logo {
    font-family: 'Cursive', sans-serif;
    color: rgb(238, 20, 129);
    font-size: 24px;
    font-weight: bold;
}

.search-bar {
    flex: 1;
    margin: 0 20px;
    display: flex;
}

.search-bar input {
    width: 100%;
    padding: 5px 10px;
    border: 1px solid #ccc;
    border-radius: 4px 0 0 4px;
}

.search-bar button {
    padding: 5px 15px;
    background-color: rgb(240, 15, 131);
    border: none;
    color: #fff;
    border-radius: 0 4px 4px 0;
    cursor: pointer;
}

.user-options {
    display: flex;
    align-items: center;
    gap: 15px;
}

.user-options a {
    text-decoration: none;
    color: rgb(232, 9, 146);
    font-size: 14px;
}

.whatsapp-btn {
    background-color: #25d366;
    color: #fff;
    padding: 5px 10px;
    border-radius: 5px;
    text-decoration: none;
}

.cart {
    position: relative;
    font-size: 18px;
    color: pink;
}

.cart-count {
    position: absolute;
    top: -10px;
    right: -10px;
    background-color: rgb(209, 14, 131);
    color: #fff;
    font-size: 12px;
    padding: 2px 5px;
    border-radius: 50%;
}

/* Barra de Navegação */
.category-bar {
    background-color: rgb(243, 15, 140);
    padding: 10px 0;
}

.category-bar ul {
    list-style: none;
    display: flex;
    justify-content: center;
    gap: 20px;
    margin: 0;
    padding: 0;
}

.category-bar li {
    position: relative;
}

.category-bar a {
    text-decoration: none;
    color: #fff;
    font-weight: bold;
}

.category-bar ul ul {
    position: absolute;
    top: 100%;
    left: 0;
    background: pink;
    padding: 10px;
    display: none;
}

.category-bar li:hover ul {
    display: block;
}

/* Produtos */
.product-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
    padding: 20px;
}

.product {
    background: #fff;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 8px;
    width: 200px;
    text-align: center;
}

.product img {
    max-width: 100%;
    height: auto;
    margin-bottom: 10px;
}

/* Rodapé */
footer {
    background-color: rgb(235, 15, 162);
    color: #fff;
    text-align: center;
    padding: 10px 0;
}

    </style>

</head>
<body>
    <!-- Cabeçalho -->
    <header>
        <div class="logo">Carinhoso Bordados</div>
        <div class="search-bar">
            <input type="text" placeholder="O que você procura?">
            <button>Pesquisar</button>
        </div>
        <div class="user-options">
            <a href="#">Cadastre-se</a>
            <a href="#">Minha Conta</a>
            <a href="https://wa.me/5516994260246" target="_blank">Tire suas dúvidas no WhatsApp</a>
            <a href="https://wa.me/5516994260246" target="_blank" class="whatsapp-btn">WhatsApp</a>
            <div class="cart">
                <span class="cart-icon">🛒</span>
                <span class="cart-count">0</span>
            </div>
        </div>
    </header>

    <!-- Barra de Navegação -->
    <nav class="category-bar">
        <ul>
            <li><a href="#">Todas as Categorias</a></li>
            <li><a href="#">Cama</a>
                <ul>
                    <li><a href="#">Lençol com Elástico</a></li>
                    <li><a href="#">Lençol sem Elástico</a></li>
                    <li><a href="#">Fronhas</a></li>
                    <li><a href="#">Cobre Leito</a></li>
                    <li><a href="#">Colchas</a></li>
                    <li><a href="#">Travesseiro</a></li>
                </ul>
            </li>
            <li><a href="#">Mesa</a>
                <ul>
                    <li><a href="#">Toalha de Mesa</a></li>
                    <li><a href="#">Cortina</a></li>
                    <li><a href="#">Pano de Prato</a></li>
                </ul>
            </li>
            <li><a href="#">Banho</a>
                <ul>
                    <li><a href="#">Toalha de Banho</a></li>
                    <li><a href="#">Toalha de Rosto</a></li>
                </ul>
            </li>
        </ul>
    </nav>

    <!-- Menu de Produtos -->
    <main>
        <h1>Produtos em Destaque</h1>
        <div class="product-grid">
            <div class="product">
                <img src="file:///C:/Users/aline/Pictures/Screenshots/Captura%20de%20tela%202024-11-30%20114759.png" alt="Produto 1">
                <h3>Lençol com Elástico</h3>
                <p>Descrição do Produto.</p>
                <button>Comprar</button>
            </div>
            <div class="product">
                <img src="placeholder.jpg" alt="Produto 2">
                <h3>Toalha de Banho</h3>
                <p>Descrição do Produto.</p>
                <button>Comprar</button>
            </div>
            <div class="product">
                <img src="placeholder.jpg" alt="Produto 3">
                <h3>Pano de Prato</h3>
                <p>Descrição do Produto.</p>
                <button>Comprar</button>
            </div>
        </div>

    <!-- Formas de Pagamento e Entrega -->
    <section class="payment-delivery">
        <h2>Formas de Pagamento</h2>
        <p>Cartão, Boleto, Pix</p>
        <h2>Entrega</h2>
        <p>Rápida e confiável para todo o Brasil</p>
    </section>

    <!-- Rodapé -->
    <footer>
        <p>&copy; 2024 Carinhoso Bordados. Todos os direitos reservados.</p>
    </footer>
</body>
</html>



<!--
**carinhosobordados/CarinhosoBordados** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
