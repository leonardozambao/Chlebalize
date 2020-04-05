<h1>Chlebalize</h1>

Framework pessoal de css/javascript com várias classes e resets de css para economizar tempo no desenvolvimento, com foco em flex-box layout. <br>
CSS escrito usando SCSS para escrita mais rápida e gerar automatico um arquivo css minificado com ajuda de plugin do VSCODE.<br>
Inspirado no modo do bootstrap mas sem excesso de atributos em todas as coisas, que acaba atrapalhando mais do que ajudando na maioria dos casos quando precisa seguir um layout pré-definido.<br>

<h2>Classes principais<h2>
 <p>
 flex - já está pré-definido para que qualquer classe que tenha o texto 'flex' será aplicado o display: flex;<br>
 flex-between - justify-content: space-between;<br>
 flex-center - justify-content: center;<br>
 flex-align-center - align-items: center;<br>
 only-desktop - oculta elementos em telas menores do que 861px<br>
 only-mobile - oculta elementos em telas maiores do que 860px<br>
 </p>
  
<h2>Implementar no código</h2>
<p>
Existe um arquivo starter.html já com as referências necessárias
<script src="js/jquery-3.4.1.min.js"></script>
<script src="js/lazysizes.min.js"></script>
<script src="js/chlebalize.js"></script>
<link rel="stylesheet" href="css/chlebalize.min.css">
</p>
