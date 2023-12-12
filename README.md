# Receita-de-bolo-HTML-CSS
Codigo de receita de bolo em HTML5 e CSS3.

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bolo de Chocolate</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: burlywood;
            margin: 20px;
        }

        header {
            text-align: center;
            margin-bottom: 20px;
        }

        h1 {
            color: #6d0d0d;
        }

        p {
            line-height: 1.6;
            color: #333;
        }

        img {
            max-width: 40%;
            height: auto;
            display:flex;
            margin: 20px auto;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        li {
            margin-bottom: 10px;
        }

        a {
            color: #bf2727;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }
        footer{
            color: black;
            text-align: center;
        }
    </style>
</head>

<body>
    <header>
        <h1>Bolo de Chocolate</h1>
    </header>
    <main>
        <section>
            <img src="https://www.receitasnestle.com.br/sites/default/files/srh_recipes/6cf1bb7359f2dca08445c83ff58bf3bf.jpg" alt="Bolo de Chocolate">
            <h2>Como fazer um bolo de chocolate da receita do Gil.</h2>

         <h3>Ingredientes:</h3>
            <ul>
                <li>2 xícaras de farinha de trigo</li>
                <li>1 xícara de cacau em pó</li>
                <li>1 colher de chá de fermento em pó</li>
                <li>1/2 colher de chá de sal</li>
                <li>1 xícara de açúcar</li>
                <li>1 xícara de leite</li>
                <li>1/2 xícara de óleo vegetal</li>
                <li>2 ovos</li>
                <li>1 colher de chá de essência de baunilha</li>
                <li>1 xícara de água fervente</li>
            </ul>

            <h3>Modo de Preparo:</h3>
            <ol>
                <li>Pré-aqueça o forno a 180°C.</li>
                <li>Unte e enfarinhe uma forma.</li>
                <li>Em uma tigela grande, peneire a farinha, o cacau, o fermento e o sal.</li>
                <li>Adicione o açúcar, o leite, o óleo, os ovos e a baunilha à mistura seca.</li>
                <li>Misture bem.</li>
                <li>Acrescente a água fervente e misture até obter uma massa homogênea.</li>
                <li>Despeje a massa na forma preparada e leve ao forno por 35 minutos.</li>
                <li>Deixe esfriar antes de desenformar e decorar.</li>
            </ol>

            <p>Para mais receitas deliciosas, visite <a href="https://www.tudogostoso.com.br/" target="_blank">Tudo Gostoso.com</a>.</p>
        </section>
    </main>
    <footer>
        Receitas by GillPaganini.
    </footer>
</body>

</html>
