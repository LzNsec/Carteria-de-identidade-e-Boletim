Descrição do Projeto
Este repositório contém o código-fonte HTML e CSS para duas páginas web simples: uma página de Carteira de Identidade e uma página de Boletim de Notas. As páginas foram projetadas usando HTML para estruturação e conteúdo e CSS para estilização.

Página de Carteira de Identidade
HTML (index.html)
html
Copy code
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Carteira de Identidade</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Carteira de Identidade</h1>
    </header>
    <section id="identidade">
        <img src="/image/calabreso.jpg" alt="Foto da Pessoa">
        <p><strong>Nome:</strong> Toninho Furacão</p>
        <p><strong>Data de Nascimento:</strong> 01/01/1999</p>
        <p><strong>Curso:</strong> Delicio</p>
        <p><strong>RA:</strong> 12345</p>
        <p><strong>Data de Ingresso:</strong> 01/04/2020</p>
        <p><strong>Faculdade:</strong> Universidade Federal Dos Calabresos</p>
    </section>
    <a href="boletim.html">Ver Boletim de Notas</a>
</body>
</html>
CSS (styles.css)
css
Copy code
/* Estilos gerais do body */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

/* Estilos para o cabeçalho */
header {
    background-color: #007bff;
    color: #fff;
    text-align: center;
    padding: 10px 0;
}

/* Estilos para o título h1 */
h1 {
    margin: 0;
}

/* Estilos para seção de identidade */
#identidade {
    background-color: #f7f7f7;
    border: 2px solid #aaa;
    border-radius: 10px;
    padding: 19px;
    max-width: 325px;
    margin: 1 auto;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
}

/* Estilos para a imagem de identidade */
#identidade img {
    width: 100px;
    margin-right: 20px;
    border: 2px solid #aaa;
    border-radius: 5px;
}

/* Estilos para parágrafos de identidade */
#identidade p {
    margin: 0;
    font-size: 14px;
    display: block;
}

/* Estilos para links */
a {
    display: block;
    text-align: center;
    margin: 20px;
    font-weight: bold;
}

/* Estilos para o link de voltar */
a {
    text-decoration: none;
    color: #007bff;
    border: 2px solid #007bff;
    border-radius: 5px;
    padding: 10px;
}

a:hover {
    background-color: #007bff;
    color: #fff;
}
Página de Boletim de Notas
HTML (boletim.html)
html
Copy code
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Boletim de Notas</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Boletim de Notas</h1>
    </header>
    <section id="notas">
        <!-- Conteúdo da tabela de notas -->
    </section>
    <a href="index.html">Voltar para a Carteira de Identidade</a>
</body>
</html>
