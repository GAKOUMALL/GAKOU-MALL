# GAKOU-MALL                                                                                                                   
 <!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profil Personnel - Gakou Ousmane</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Gakou Ousmane</h1>
            <nav>
                <ul>
                    <li><a href="#biographie">Biographie</a></li>
                    <li><a href="#realisations">Réalisations</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="biographie" class="container">
        <h2>Biographie</h2>
        <p>Je m'appelle Gakou Ousmane. Je suis passionné par le football, la médecine, l'informatique, l'ingénierie en robotique, et le commerce. J'ai toujours été fan de la robotique et, à partir de mes 16 ans, j'ai décidé de me tourner vers le commerce pour gagner de l'argent. Cela est rapidement devenu une passion pour moi, me plaçant ainsi dans un dilemme de choix entre mes différentes passions.</p>
    </section>

    <section id="realisations" class="container">
        <h2>Réalisations</h2>
        <h3>GAKOU MALL</h3>
        <p>GAKOU MALL est une entreprise innovante spécialisée dans le commerce en ligne. Fondée avec l'objectif de révolutionner l'expérience d'achat, GAKOU MALL propose une vaste gamme de produits allant de l'électronique aux vêtements, en passant par les articles de maison et les produits de beauté. Grâce à une interface utilisateur intuitive et à des services de livraison rapide, GAKOU MALL s'efforce de rendre les achats en ligne plus faciles, plus rapides et plus agréables pour ses clients. La création de GAKOU MALL a été un petit succès, marquant le début de mon aventure entrepreneuriale.</p>
    </section>

    <section id="contact" class="container">
        <h2>Contact</h2>
        <p>Email: <a href="mailto:gobusiness032@gmail.com">gobusiness032@gmail.com</a></p>
        <p>Twitter: <a href="https://twitter.com/gakoumall">@gakoumall</a></p>
    </section>

    <footer>
        <p>&copy; 2024 Gakou Ousmane. Tous droits réservés.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
body {
    font-family: 'Roboto', sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

.container {
    width: 80%;
    margin: auto;
    overflow: hidden;
}

header {
    background: linear-gradient(90deg, #50b3a2, #e8491d);
    color: #fff;
    padding-top: 30px;
    min-height: 70px;
    border-bottom: #e8491d 3px solid;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

header a {
    color: #fff;
    text-decoration: none;
    text-transform: uppercase;
    font-size: 16px;
    transition: color 0.3s ease;
}

header a:hover {
    color: #e8491d;
}

header ul {
    padding: 0;
    list-style: none;
    text-align: center;
}

header li {
    display: inline;
    padding: 0 20px 0 20px;
}

header #branding {
    float: left;
    font-size: 24px;
    font-weight: bold;
}

header nav {
    float: right;
    margin-top: 10px;
}

section {
    padding: 20px;
    margin-top: 20px;
    background: #fff;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    border-radius: 8px;
    transition: transform 0.3s ease;
}

section:hover {
    transform: translateY(-10px);
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
    margin-top: 20px;
    position: fixed;
    bottom: 0;
    width: 100%;
}
// script.js
