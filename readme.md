<h1>Comentarios e marcações</h1>
<br>
<br>

## sass --watch syle.scss:style.css 
( assiste o arquivo sass e compila o css)
<hr>

## "!" no html
(faz com que ele crie a estrutura do html)
<hr>

## $purple : #a050be;
($nomeVariavel)
<hr>

## comentario do tipo /**/ aparece no css
<hr>

## comentarios do tipo // nao aparece no css
<hr>

## &__img substitui o header__img
(esse é um exemplo do parent selector que faz com que melhoremos a performace do nosso codigo)
<hr>
## width: calc(100% - # { $variavel } );
(estrutura de exemplo de uma interpolação)
<hr>
<br>
<b>O que é Nesting, e quais as suas vantagens em comparação ao CSS: </b>
 A tradução literal de Nesting é “aninhamento”, assim, ele permite colocarmos elementos um dentro do outro, evitando a repetição, facilitando na manutenção e deixando o código CSS mais curto.
<hr>
<br>
<b>Como usar o Parent Selector:</b>
O Parent Selector é um seletor & que permite referenciar o elemento “pai”. Sendo possível adicionar pseudo-classes como &:hover, pseudo_elementos como &:before, e também sufixos para as classes. No CSS uma classe que seria: .component .component__text {}, no Sass fica: .component { &__text {} }.
<hr>
<br>
<b>O que é Interpolação e como fazê-lo.</b>
Interpolação é usada para injetar valores em expressões como variáveis e funções nos nossos seletores. Isso pode ser muito útil ao se passar parâmetros que podem ser alterados.
<hr>
<br>