<!DOCTYPE html>
<html lang="en">
    <head>
        <meta cahrset="UTF-8">
        <meta name="viewport">
        <title>Yemek Menüsü</title>
        <style>
            body {
                font-family:Arial, Helvetica, sans-serif;
                margin: 0;
                padding: 0;
                background: white;
                color: #333;
            }

            header {
                text-align: center;
                padding: 20px;
                background: #6c757e;
                color: white;
                font-size: 1.5rem;
            }

            main {
                max-width: 800px;
                margin: 20px auto;
                display: grid;
                grid-template-columns: 1fr 1fr;
                gap:20px
            }

            .menu-section {
                background: white;
                padding: 15px;
                border-radius: 8px;
                box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            }

            .menu-section {
                text-align: center;
                font-size: 1.2rem;
                margin-bottom: 10px;
                color: #6c757e;
            }

            .menu-item {
                padding: 10px 0;
                border-bottom: 1px solid white;
            }

            .menu-item: {
                border-bottom: none;
            }

            .menu-item span {
                float: right;
                font-weight: bold;
                color: #495057;
            }

            footer {
                text-align: center;
                padding: 10px;
                background: #6c757e;
                color: white;
                font-size: 0.9rem;
            }

            footer a {
                color: white;
                text-decoration: none;
            }

            footer a:hover {
                text-decoration: underline;
            }
        </style>
    </head>
    <body>
        <header>
            <h1>Yemek Menüsü</h1>
        </header>
        <main>
            <div class="menu-section">
                <h2>Çorbalar</h2>
                <div class="menu-item">Mercimek Çorbası<span>35₺</span></div>
                <div class="menu-item">Ezogelin Çorbası<span>40₺</span></div>
                <div class="menu-item">Tavuk Çorbası<span>45₺</span></div>
            </div>
            <div class="menu-section">
                <h2>Ana Yemekler</h2>
                <div class="menu-item">Kebap<span>85₺</span></div>
                <div class="menu-item">Izgara Tavuk<span>75₺</span></div>
                <div class="menu-item">Mantı<span>65₺</span></div>
            </div>
            <div class="menu-section">
                <h2>Salatalar</h2>
                <div class="menu-item">Çoban Salata<span>30₺</span></div>
                <div class="menu-item">Sezar Salata<span>40₺</span></div>
                <div class="menu-item">Mevsim Salata<span>35₺</span></div>
            </div>
            <div class="menu-section">
                <h2>Tatlılar</h2>
                <div class="menu-item">Baklava<span>50₺</span></div>
                <div class="menu-item">Sütlaç<span>40₺</span></div>
                <div class="menu-item">Künefe<span>55₺</span></div>
            </div>
        </main>
        <footer>
            Hazırlayan: <a href="#">İkra Gürsoy</a>
        </footer>
    </body>
</html>
