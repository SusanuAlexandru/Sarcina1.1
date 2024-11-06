<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site Simplu HTML</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            background-color: #444;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .content {
            padding: 20px;
            background-color: white;
            max-width: 800px;
            margin: 20px auto;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bine ați venit pe site-ul meu</h1>
    </header>
    <nav>
        <a href="#home">Acasă</a>
        <a href="#about">Despre</a>
        <a href="#services">Servicii</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="content">
        <h2>Despre noi</h2>
        <p>Acesta este un exemplu de pagină web simplă creată cu HTML și CSS. Puteți personaliza acest template adăugând mai multe pagini, imagini și conținut specific nevoilor dumneavoastră.</p>
        <h3>Serviciile noastre</h3>
        <p>Oferim servicii de web design, dezvoltare web și optimizare SEO pentru afacerea dvs. Nu ezitați să ne contactați pentru mai multe detalii!</p>
    </div>
    <footer>
        <p>&copy; 2024 Site-ul Meu. Toate drepturile rezervate.</p>
    </footer>
</body>
</html>
