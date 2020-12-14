# Pilares-Ejemplo1
Ejemplo con código HTML
<!DOCTYPE html>
<html>
<head>
	<title>Enlaces</title>
	<link rel="stylesheet" type="text/css" href="estilos.css">
  <style type="text/css">
  a{
    font-size:20px; 
	text-decoration:none;
	margin:10px 10px 10px 10px;
	display:inline-block;
	background:#ccc;
	box-shadow: 0px 10px 10px #1d6A67;/sombra de micaja/
   border:1 solid #00ffff;
} 
a:hover{
	box-shadow: 0px 5px 5px #1D6A;
	background:#000;
	color:#fff;
}
a:active{
	box-shadow:none;</style>
</head>
<body>
<h1>Enlaces con css</h1>
<h3>Los estados de un enlace</h2>
<p>Lo primero que hay que entender es el concepto de estados de un enlace (diferentes estados en los que pueden estar los enlaces, que pueden diseñarse usando diferentes pseudoclases)</p>

<p>Link (no visitado): El estado predeterminado que presenta un enlace cuando no está en ningún otro estado. Se puede especificar usando la pseudoclase :link.
Visited: Un enlace cuando ya se ha visitado (está grabado en el historial del navegador); se le aplica otro formato con la pseudoclase :visited.
Hover: Un enlace cuando se le pasa el cursor por encima; se le aplica otro formato con la pseudoclase :hover.
Focus: Un enlace cuando tiene el foco (por ejemplo, se salta a este con la tecla Tab del teclado o se le da el foco mediante programación usando HTMLElement.focus()); se le aplica un formato diferente con la pseudoclase :focus.
Active: Un enlace cuando se activa (por ejemplo, se hace clic encima); se le aplica un formato diferente con la pseudoclase.</p>
<br>
<a href="https://developer.mozilla.org/es/docs/Learn/CSS/Styling_text/Styling_links">funte de infromacion</a>
<a href="https://developer.mozilla.org/es/docs/Learn/CSS/Styling_text/Styling_links">funte de infromacion</a>
<a href="https://developer.mozilla.org/es/docs/Learn/CSS/Styling_text/Styling_links">funte de infromacion</a>
<a href="https://developer.mozilla.org/es/docs/Learn/CSS/Styling_text/Styling_links">funte de infromacion</a>
<a href="https://uniwebsidad.com/libros/css/capitulo-7">funte de infromacion 2</a>
</body>
</html>
