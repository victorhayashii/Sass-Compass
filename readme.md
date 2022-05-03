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

## %no-decoration{text-decoration: none;}
(placeholder selector : Acima há um exemplo onde fazemos o placeholder selector, que funciona quando voce quer inserir um comportamento especifico a uma classe e nao quer que seja renderizado no css, é aconselhado usar os placeholders quando nao tiver variaveis sendo usadas dentro dele. )
<hr>
<br>

## mixins
@mixin reset-list {<br>
    margin: 0;<br>
    padding: 0;<br>
    list-style: none;<br>
}<br>
(exemplo da criacao de um mixin que serve quando voce tem uma repeticao de codigos iguais e cria um mixin que retorna essas variaveis para sua classe)
<hr>
<br>

## @mixin for-tablet-only{
##    @media(min-width: 768px) and (max-width:1199.98px){
##       @content;} }
(exemplo de um mixin com o media para tornar o css responsavel)
<hr>
<br>

## @function calculateRem($size){
##    @return $size/ 16px *1rem;
## }
(exemplo de função que altera pix para rem)

<hr>
<br>
## @import 'header';
(exemplo de importacao do scss)
<hr>
<br>

## @import 'header','footer','about','article';
(exemplo da importacao de varios arquivos scss)



## estrutura do if e else
    @if $half-post {
        width: $half-width;
    } @else{
        width: $full-width;
    }