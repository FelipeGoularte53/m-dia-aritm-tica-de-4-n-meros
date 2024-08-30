# média aritmética


1. HTML (index.html)
O HTML fornece a estrutura básica da página da web.

html
Copiar código
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
2. CSS (styles.css)
O CSS estiliza a página, controlando a aparência dos elementos HTML.

css
Copiar código
body {
    font-family: Arial, sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
    background-color: #f4f4f4;
}

.container {
    background: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    width: 300px;
}

h1 {
    text-align: center;
}

form {
    display: flex;
    flex-direction: column;
}

label {
    margin-top: 10px;
}

input {
    padding: 10px;
    margin-top: 5px;
    border: 1px solid #ddd;
    border-radius: 4px;
}

button {
    margin-top: 20px;
    padding: 10px;
    border: none;
    border-radius: 4px;
    background-color: #28a745;
    color: white;
    font-size: 16px;
    cursor: pointer;
}

button:hover {
    background-color: #218838;
}

#resultado {
    margin-top: 20px;
    font-size: 18px;
    font-weight: bold;
}
Explicação:

body: Define o estilo global do corpo da página.

font-family: Arial, sans-serif;: Define a fonte padrão como Arial.

display: flex; justify-content: center; align-items: center; height: 100vh;: Usa Flexbox para centralizar o conteúdo vertical e horizontalmente e garante que ocupe 100% da altura da janela de visualização.

background-color: #f4f4f4;: Define a cor de fundo da página.

.container: Estiliza o contêiner principal da página.

background: white;: Define o fundo do contêiner como branco.

padding: 20px;: Adiciona um espaço interno de 20 pixels.

border-radius: 8px;: Arredonda os cantos do contêiner.

box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);: Adiciona uma sombra leve ao redor do contêiner.

width: 300px;: Define a largura do contêiner.

h1: Estiliza o título principal.

text-align: center;: Centraliza o texto.

form: Estiliza o formulário.

display: flex; flex-direction: column;: Organiza os elementos do formulário em uma coluna.

label: Estiliza os rótulos dos campos de entrada.

margin-top: 10px;: Adiciona uma margem superior.

input: Estiliza os campos de entrada.

padding: 10px;: Adiciona um espaço interno.

margin-top: 5px;: Adiciona uma margem superior.

border: 1px solid #ddd;: Define uma borda fina e cinza.

border-radius: 4px;: Arredonda os cantos dos campos.

button: Estiliza o botão.

margin-top: 20px;: Adiciona uma margem superior.

padding: 10px;: Adiciona um espaço interno.

border: none;: Remove a borda padrão.

border-radius: 4px;: Arredonda os cantos do botão.

background-color: #28a745;: Define a cor de fundo do botão.

color: white;: Define a cor do texto como branco.

font-size: 16px;: Define o tamanho da fonte.

cursor: pointer;: Muda o cursor para uma mão quando passa sobre o botão.

button:hover: Define o estilo do botão quando o mouse passa sobre ele.

background-color: #218838;: Escurece a cor de fundo para um efeito de hover.

#resultado: Estiliza a área onde o resultado será exibido.

margin-top: 20px;: Adiciona uma margem superior.

font-size: 18px;: Define o tamanho da fonte.

font-weight: bold;: Torna o texto em negrito.
