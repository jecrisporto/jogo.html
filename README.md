# jogo.html
Estudando JavaScript
<!doctype html>
<html>
<head>
   <meta charset="utf-8">
   <title>Jogo Iroman</title>
   <style>
   	canvas {
   		position: absolute;
   		top: 0px,
   		bottom: 0px;
   		left: 0px;
   		right: 0px;
   		margin: auto;
   	}
   </style>

</head>
<body>

	<script>
		//Variáveis do jogo
		var canvas, ctx, ALTURA, LARGURA, frames = 0;


		function clique(event) {
			alert("clicou");
		}

		function main() {
			ALTURA = window.innerHeight;
			LARGURA = window.innerWidth;

			if (LARGURA >= 500) {
				LARGURA = 600;
				ALTURA = 600;

			}

			canvas = document.createElement("canvas");
			canvas.width = LARGURA
			canvas.height =ALTURA
			canvas.style.border: = "1px solid #000";


            ctx = canvas.getContext("2d");
			document.body.appendChild(canvas);

			document.addEventListener("mousedown", clique);
 
		}

		function roda() {}

		function atualiza() {}

		function desenha() {}


		//inicializa o jogo
	</script>

</body>
</html>
