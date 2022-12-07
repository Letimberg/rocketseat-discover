# Selectors

Conecta um elemento HTML com o CSS

## Tipos

- Global selector `*`
- Element/Type selector `h1, h2, p, div`
- Id Selector `#box, #container`
- Class Selector `.red, .m-4`
- Attribute selector, Pseudo-class, Pseudo-element, e outros

HTML

<div id="container" class="m-40">
	<h1>Título</h1>
	<h2>Subtitulo</h2>
</div>
CSS
/* ID selector */
#container {
	width: 200px;
}

/_ Class selector _/
.m-40 {
margin: 40px;
}

/_ Element/Type selector + Agrupamento de seletores _/
h1, h2 {
color: blue;
font-size: 60px;
background: gray;
}
