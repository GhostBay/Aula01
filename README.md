<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
      body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
            text-align: center;
            padding: 20px;
        }
        
        header {
            background-color: #333;
            color: white;
            padding: 10px;
        }
</style>
<body>
    <header>
        <h1>Meu Guia de CSS</h1>
    </header>
    <br>
    <a href="file:///C:/Users/Jhony/Desktop/blog/blog%20simples.html">Voltar</a>
    <br>

    <h2>Alterar Estilo:</h2>
    <button onclick="mudarFundo()">Alterar Fundo</button>
    <button onclick="mudarCabeçalho()">Alterar Cabeçalho</button>

    <h2>Introdução ao CSS:</h2>
    <p>O CSS (Cascading Style Sheets) é uma linguagem de estilo usada para controlar o design e a apresentação de páginas da web. Com o CSS, você pode definir cores, fontes, margens, tamanhos de texto e muito mais.</p>

</body>
<script>
function mudarFundo() {
            const corFundo = prompt("Digite uma cor de fundo (por exemplo, 'red' ou '#00ff00'): ");
            document.body.style.backgroundColor = corFundo;
        }

        function mudarCabeçalho() {
            const corCabeçalho = prompt("Digite uma cor para o cabeçalho: ");
            document.querySelector("header").style.backgroundColor = corCabeçalho;
        }

</script>
</html>