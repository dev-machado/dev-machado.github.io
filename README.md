# dev-machado.github.io
<html lang="pt-br">
<head>
  <title>Bom dia flor do dia</title>
  <style>
    * {
      margin: 0;
      padding: 0;
    }

    body {
      background-color: #fff;
    }

    .pop-up {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(0, 0, 0, 0.5);
      display: none;
      background-image: url("");
      background-repeat: no-repeat;
      background-position: center center;
      background-size: cover;
    }

    .pop-up .content {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      width: 400px;
      height: 200px;
      background-color: #fecfcc;
      border-radius: 10px;
      padding: 20px;
      text-align: center;
    }

    .pop-up .content h1 {
      font-size: 20px;
    }

    .pop-up .content p {
      font-size: 16px;
    }

    .pop-up .content button {
      position: absolute;
      bottom: 10px;
      right: 10px;
      background-color: #000;
      color: #fff;
      font-size: 16px;
      padding: 10px;
      border-radius: 5px;
      cursor: pointer;
    }
  </style>
</head>
<body>


  <div class="pop-up">
    <div class="content">
      <h1>Bom dia flor do dia ♥</h1>
      <button onclick="fechar()">Fechar</button>
	<img src="kuromi-getting-shy-pdlhnu9yza2zw3ml.gif" width="200"> 
    </div>
  </div>

  <script>
    function abrir() {
      document.querySelector(".pop-up").style.display = "block";
    }

    function fechar() {
      document.querySelector(".pop-up").style.display = "none";
    }

    window.addEventListener("load", abrir);
  </script>
</body>
</html>
