<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Página</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Minha Clínica Odontológica</h1>
        <nav>
            <ul>
                <li><a href="#">Página Inicial</a></li>
                <li><a href="#">Serviços</a></li>
                <li><a href="#">Contato</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2>Seja bem-vindo à nossa clínica!</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam fringilla, justo sit amet ultrices vehicula, lacus felis tempor ex, non maximus ligula felis sed magna.</p>
        </section>
        <section>
            <h2>Nossos Serviços</h2>
            <ul>
                <li>Limpeza Dental</li>
                <li>Extração de Dentes</li>
                <li>Implantes Dentários</li>
            </ul>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Minha Clínica Odontológica. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    margin: 0;
    padding: 0;
}
header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1rem;
}
header nav ul {
    list-style-type: none;
    padding: 0;
}
header nav ul li {
    display: inline;
    margin-right: 10px;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
}
main {
    padding: 1rem;
    max-width: 800px;
    margin: 0 auto;
}
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 0.5rem;
    position: fixed;
    bottom: 0;
    width: 100%;
}

