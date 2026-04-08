<!DOCTYPE html>
<html>
<head>
    <style>
        body {
            font-family: Arial;
            background-color: #fce4ec;
            text-align: center;
        }

        .container {
            background-color: white;
            width: 300px;
            margin: 50px auto;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }

        h1 {
            color: #d81b60;
        }

        p {
            font-size: 20px;
            color: #333333;
        }

        button {
            background-color: #d81b60;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        button:hover {
            background-color: #ad1457;
        }
    </style>
</head>

<body>

    <div class="container">
        <h1>Minha primeira página</h1>
        <p id="mensagem">Esse é um parágrafo de exemplo.</p>
        <button onclick="acaoBotao()">Começar</button>
    </div>

    <script>
        function acaoBotao() {
            const paragrafo = document.getElementById('mensagem');
            paragrafo.innerText = "¡Botón pulsado correctamente!";
            paragrafo.style.fontWeight = "bold";
            paragrafo.style.color = "#d81b60";
        }
    </script>

</body>
</html>
