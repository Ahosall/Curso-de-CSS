## Aula 4 - Curso de CSS - WPMasters · 20/01/2021

Nesta aula foi ensinado a como estilizar `Div's e Links`.

Exemplo :

```css
/* div */
.top-div {
	position: relative; /* isto irá deixar que ela fique totalmente relativa */
	width: 100%; /* isto deixara ela da largura do seu display*/
	height: 100px; /* isso da 100px de altura para a div*/
	border-bottom: 1px solid #000000; /* aqui adiciona uma borda de 1px, solido e preto em baixo da div*/
	background-color: #FF0000	; /*aqui muda a cor do background da div vermelho*/
}
```

```css
/* links */
a {
	text-decoration: none;
	font-family: Arial;
	color: white;
} 
```

bom, o link tbm tem as mesmas funções de texto do `<p>|<h1>|...`

### Atributos dos links
Os links possuem tributos sendo eles o `hover`(Quando um usuário passar o mouse por cima do link), o `activate`(Quando o usuário mantém o link pressionado), e o visited(Quando o usuário já acessou o link).

Exemplos
```css
a:hover {
	font-weight: bold;
	color: black;
} /* se o usuário passar o mouse por cima do link ele irá ficar negrito e preto */

a:activate {
	color: blue;
} /* se ele o manter pressionado o link irá ficar azul */

a:visited {
	color: yellow;
} /* agora se ele ja visitou o link ele irá ficar amarelo */
```

Aviso: recomendo você sempre der uma olhada dentoro dos arquivos HTML e CSS, lá pode conter umas surpresas ...