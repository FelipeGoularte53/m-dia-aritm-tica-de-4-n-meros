# média aritmética
Entendi! Vou explicar o código que criei anteriormente para calcular a média aritmética de quatro números. O código é dividido em três partes principais: HTML, CSS e JavaScript. Vamos detalhar cada uma dessas partes.

1. HTML (index.html)
O HTML fornece a estrutura básica da página da web.
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculadora de Média Aritmética</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Calculadora de Média Aritmética</h1>
        <form id="mediaForm">
            <label for="num1">Número 1:</label>
            <input type="number" id="num1" required>
            
            <label for="num2">Número 2:</label>
            <input type="number" id="num2" required>
            
            <label for="num3">Número 3:</label>
            <input type="number" id="num3" required>
            
            <label for="num4">Número 4:</label>
            <input type="number" id="num4" required>
            
            <button type="button" onclick="calcularMedia()">Calcular Média</button>
        </form>
        <div id="resultado"></div>
    </div>
    <script src="script.js"></script>
</body>
</html>

Explicação:
<!DOCTYPE html>: Declara o tipo de documento e a versão do HTML. É a primeira linha de um documento HTML5.
<html lang="pt-BR">: Define o início do documento HTML e especifica que o idioma da página é português do Brasil.
<head>: Contém metadados sobre o documento, como o conjunto de caracteres e o título da página.
<meta charset="UTF-8">: Define a codificação de caracteres para UTF-8, suportando uma ampla gama de caracteres.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Faz com que a página se ajuste corretamente em dispositivos móveis.
<title>: Define o título da página que aparece na aba do navegador.
<link rel="stylesheet" href="styles.css">: Inclui o arquivo CSS para estilizar a página.
<body>: Contém o conteúdo visível da página.
<div class="container">: Um contêiner para centralizar e estilizar o conteúdo.
<h1>: Título principal da página.
<form id="mediaForm">: Define um formulário para entrada de dados.
<label for="num1">: Rótulo para o campo de entrada do primeiro número.
<input type="number" id="num1" required>: Campo de entrada para o primeiro número. O atributo required faz com que o campo seja obrigatório.
<button type="button" onclick="calcularMedia()">: Botão que, quando clicado, chama a função calcularMedia() definida no JavaScript.
<div id="resultado">: Divisão onde o resultado será exibido.
<script src="script.js"></script>: Inclui o arquivo JavaScript que contém a lógica para calcular a média.
