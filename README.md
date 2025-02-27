<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8"> 
    <title>Promoção de Passagens Aéreas</title>
    <style> 
        /* Estilizando a página */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        h1 {
            background-color: #8c91da;
            color: rgb(5, 7, 121);
            padding: 20px;
            margin: 0;
        }
        h2 {
            color: blue;
        }
        .azul2 { 
            color: rgb(2, 2, 44);
        }
        .imagem {
            width: 1000px; 
            height: 200px; 
            object-fit: cover; 
            display: block; 
            margin: 0 auto;
        }
        .galeria {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin: 20px;
            flex-wrap: wrap;
        }
        .destino {
            background: white;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.2);
            overflow: hidden;
            width: 300px;
            text-align: center;
            padding-bottom: 15px;
        }
        .destino img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .destino h2 {
            color: #0313f5;
            margin: 10px 0;
        }
        .destino p {
            padding: 0 15px;
            color: #666;
        }

    </style>
</head>
<body>

    <h1>Promoção de Passagens Aéreas</h1>

    <h2 class="azul">Liberdade</h2>

    <img src="imagens/v.jpg" class="imagem" alt="Promoção de passagens">

    <h2 class="azul2"><b>Melhores ofertas para sua viagem!</b></h2>

    <!-- Galeria de Destinos -->
    <h2 class="azul2">Galeria de Destinos</h2>
    <div class="galeria">
        <!-- Destino 1 -->
        <div class="destino">
            <img src="can.jpg" alt="Cancun">
            <h2>Cancun, Mexico</h2>
            <p>O lugar das festas</p>
        </div>

        <!-- Destino 2 -->
        <div class="destino">
            <img src="bonito.jpg" alt="Cachoeira Queda">
            <h2>Bonito, MGS</h2>
            <p>Cachoeiras da cor do mar, corpo e alma junto a natureza.</p>
        </div>

        <!-- Destino 3 -->
        <div class="destino">
            <img src="bar.jpg" alt="Barilhoce">
            <h2>Barilhoce</h2>
            <p>Cidade do frio, da nave.</p>
        </div>
    </div>
</body>
</html>

