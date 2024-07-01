<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pop Color T-Shirts</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #ff4081;
            color: white;
            padding: 1em;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #ff80ab;
            padding: 0.5em;
        }
        nav a {
            margin: 0 1em;
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        .container {
            max-width: 1200px;
            margin: 2em auto;
            padding: 0 1em;
        }
        .hero {
            text-align: center;
            margin-bottom: 2em;
        }
        .hero img {
            max-width: 100%;
            height: auto;
        }
        .catalog {
            display: flex;
            flex-wrap: wrap;
            gap: 2em;
            justify-content: center;
        }
        .product {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            width: calc(33% - 2em);
            max-width: 300px;
        }
        .product img {
            width: 100%;
            height: auto;
        }
        .product-info {
            padding: 1em;
            text-align: center;
        }
        .product-info h3 {
            margin: 0.5em 0;
            color: #ff4081;
        }
        .product-info p {
            margin: 0.5em 0;
            color: #555;
        }
        .product-info button {
            background-color: #ff4081;
            color: white;
            border: none;
            padding: 0.5em 1em;
            cursor: pointer;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }
        .product-info button:hover {
            background-color: #e73370;
        }
        footer {
            background-color: #ff4081;
            color: white;
            text-align: center;
            padding: 1em;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Pop Color T-Shirts</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#catalog">Catalogo</a>
    </nav>
    <div class="container" id="home">
        <div class="hero">
            <img src="https://via.placeholder.com/1200x400.png?text=Pop+Color+T-Shirts" alt="Pop Color T-Shirts">
            <h2>Le t-shirt più colorate e pop</h2>
            <p>Scopri la nostra collezione esclusiva di t-shirt dai colori vivaci e design unici!</p>
        </div>
    </div>
    <div class="container" id="catalog">
        <h2>Catalogo</h2>
        <div class="catalog">
            <div class="product">
                <img src="https://via.placeholder.com/300.png?text=T-Shirt+1" alt="T-Shirt 1">
                <div class="product-info">
                    <h3>T-Shirt 1</h3>
                    <p>Descrizione della T-Shirt 1</p>
                    <button>Acquista</button>
                </div>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300.png?text=T-Shirt+2" alt="T-Shirt 2">
                <div class="product-info">
                    <h3>T-Shirt 2</h3>
                    <p>Descrizione della T-Shirt 2</p>
                    <button>Acquista</button>
                </div>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300.png?text=T-Shirt+3" alt="T-Shirt 3">
                <div class="product-info">
                    <h3>T-Shirt 3</h3>
                    <p>Descrizione della T-Shirt 3</p>
                    <button>Acquista</button>
                </div>
            </div>
            <!-- Aggiungi altri prodotti qui -->
        </div>
    </div>
    <footer>
        &copy; 2024 Pop Color T-Shirts
    </footer>
</body>
</html>
