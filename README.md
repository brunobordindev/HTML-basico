# HTML Básico: iniciando no desenvolvimento web com HTML

<img src="https://user-images.githubusercontent.com/72177982/104813897-b70d5480-57ea-11eb-801a-a3467616fce7.png" width="100%">

![Version](https://img.shields.io/badge/Version-1.0.0-FF0000) ![Language](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)

Se você pretende criar um site, aprender o HTML básico é uma das melhores coisas que você pode fazer! Independentemente de pretender trabalhar com wordpress, web designer ou desenvolvimento web, conhecer o básico do HTML é essencial. Esse conhecimento permite compreender como funciona uma página web e seus elementos. Dessa forma, você pode criar seus próprios documentos e **páginas HTML**. Além disso, no futuro poderá também fazer uso desses recursos para fazer alterações e manutenções em páginas já existentes.

Ao final deste artigo, você terá um conhecimento do HTML básico. Portanto, conhecerá o suficiente para realizar as sugestões acima. Dessa forma, também será possível avançar seus estudos a um nível intermediário e avançado para começar a criar páginas profissionais.

Este artigo está dividido nos seguintes tópicos:

- [O que é o HTML](#o-que-é-o-html)
- [Como funciona o HTML](#como-funciona-o-html)
- [As tags do HTML](#as-tags-do-html)
- [Estrutura básica de um documento HTML](#estrutura-básica-de-um-documento-html)
- [Tags importantes para o HTML básico](#tags-importantes-para-o-html-básico)
- [Classes e IDs no HTML](#classes-e-ids-no-html)
    - [Classes](#classes)
    - [IDs](#ids)
    - [Mesclando classes e IDs](#mesclando-classes-e-ids)
- [Criando uma página com elementos do HTML básico](#criando-uma-página-com-elementos-do-html-básico)
    - [HTML básico:](#html-básico)
        - [1º passo – criando uma página](#html-básico)
        - [2º passo – criando o cabeçalho](#html-básico)

## O que é o HTML ?

O **HTML** (HyperText Markup Language) não é uma linguagem de programação, mas sim de marcação. Portanto, isso significa que não podemos usar o HTML para criar funcionalidades dinâmicas. Entretanto, o HTML possibilita a organização e formatação de documentos, de forma similar ao que fazemos em editores de texto, como o Microsoft Word.

O HTML é uma linguagem de marcação de HiperTexto utilizada para estruturar um documento ou página para a web. Ou seja, ao visualizar uma página na internet, você verá a renderização de um código criado em HTML em conjunto com outras linguagens.

Ou seja, a linguagem ***HTML permite criarmos um código que será renderizado pelos navegadores***. Portanto, será mostrado o resultado dessa renderização ao cliente. Dessa forma, todas as páginas que você acessar pela internet são códigos escritos em linguagem de máquina. Os pilares básicos do desenvolvimento web Front End são as linguagens **HTML**, **CSS** e **JavaScript**.

O ***HTML é utilizado para marcar os elementos da página, ou seja, para estruturar*** a página. O CSS permite que possamos aplicar estilos aos elementos através de estilo em cascata. Ou seja, com o CSS, temos controle e modificamos a apresentação visual da página.  Já o JavaScript é uma linguagem de programação que permite adicionar interação dentro da sua página.

Portanto, se você deseja **criar qualquer página da internet**, deve saber pelo menos o HTML básico é muito importante.

Atualmente o **HTML** se encontra na ***versão HTML5***, e é padronizada pela ***W3C (World Wide Web Consortium)***, uma organização internacional responsável por estabelecer padrões para a internet, como as linguagens **XML**, **CSS** e o **SOAP**.

## Como funciona o HTML

Um documento **HTML** nada mais é que um documento contendo a extensão **.html**. A partir deste documento, o navegador faz a leitura do arquivo e renderiza o seu conteúdo para que o usuário final possa visualizá-lo. Portanto, os arquivos .html podem ser visualizados em qualquer navegador (como Google Chrome, Opera, Safari, Mozilla Firefox, etc).

Geralmente um ***site é composto por diversas páginas HTML***, como por exemplo: um website que contenha três páginas (uma homepage, uma página de contato e uma página de produtos) receberá ao menos três documentos .html distintos, sendo um para cada página do website.

Dentro desse documento, são escrito diversas linhas de códigos de marcação, ou seja, elementos do HTML. Esses elementos se dividem entre as tags HTML e o seu conteúdo.

**Para poder criar ou editar um documento HTML**, o único recurso que você precisa é de um editor de texto, como o próprio bloco de notas. Porém, para o desenvolvimento recomenda-se utilizar editores especializados, como o ***Sublime Text***, o ***Notepad++***, o ***Visual Studio Code***, entre outros. Portanto, verifique qual o editor de texto que mais se adapta ao seu gosto e utilize-o para criar seus códigos.

Cada página consiste em uma série de **tags** (também chamados de elementos) que podem ser consideradas os blocos de construção das páginas. Portanto, esses blocos são a maneira com a qual o HTML faz a marcação dos conteúdos, criando a hierarquia e a estrutura do mesmo, dividido entre seções, parágrafos, cabeçalhos, e outros.

## As tags do HTML

<img src="https://user-images.githubusercontent.com/72177982/104815118-7402af80-57f1-11eb-8165-34bde301ce70.png" width="100%">

As tags são parte dos elementos do HTML. São usadas para informar ao navegador a estrutura do site. Ou seja: quando se escreve um código em HTML, as tags serão interpretadas pelo navegador, produzindo assim a estrutura e o conteúdo visual da página.

A principal característica das tags é estarem sempre dentro dos sinais de chevron (sinal de “maior que” e “menor que”), ou seja: **< >**.

As tags HTML são divididas em dois tipos: as que precisam de fechamento e as que não precisam de fechamento. As tags que precisam de fechamento possuem a sintaxe ```<tag> …</tag>```, já as que não precisam de fechamento possuem como estrutura ```<tag/>```.

Além disso, uma mesma tag pode receber um ou mais atributos, que possuirá um valor que modifica sua estrutura ou funcionalidade. Os atributos nada mais são que propriedades capazes de modificar e personalizar a funcionalidade de uma tag. Portanto, podemos utilizar diversos atributos, como largura, altura, dentre outros. Com a versão do HTML5, boa parte dos atributos referente a estilização deixaram de ser utilizados, passando a ser estilizado através do **CSS**.

## Estrutura básica de um documento HTML

A estrutura básica de um documento HTML, ou seja, de uma página da web, é realizada da seguinte forma:

```html
<!DOCTYPE html>

<html>
<head>
    <meta charset="utf-8">
    <title></title>
</head>

<body>

</body>
</html>
```

A partir desse código, podemos desenvolver toda a nossa página, estruturando como precisarmos. Mas primeiro, é bom compreender o que está sendo feito até o momento:

- **```<!DOCTYPE html>```** - A declaração do doctype informa ao navegador que está sendo utilizado a linguagem HTML . Hoje em dia, o doctype basicamente é necessário apenas para garantir que o documento se comporte corretamente. Caso queira saber mais a respeito, leia o artigo sobre ***doctype HTML***.

- **```<html></html>```** — O elemento ```<html>``` envolve todo o conteúdo da página HTML.

- **```<head></head>```** — O elemento ```<head>``` é o local no qual você irá incluir todos os elementos que deseja incluir na página mas que não deve ser renderizado. Dentre eles, podemos utilizar os metadados, o título, as tags ```<link>``` para adicionar folhas de estilos, entre outras.

- **```<meta charset=”utf-8″>```** — Esse elemento de metadados serve para definir o conjunto de caracteres que seu documento deve usar para o utf-8.

- **```<title></title>```** — O elemento ```<title>``` serve para definir o título de sua página. Portanto, é aqui que se define o título que é mostrado na guia do navegador.

- **```<body></body>```** — Finalmente, neste elemento, ficarão todos os elementos que serão renderizados pelo navegador, ou seja, todo o corpo da sua página HTML.

## Tags importantes para o HTML básico

Atualmente, ***no HTML5, já é possível encontrar mais que 140 tags HTML***. Porém, boa parte dessas não são muito utilizadas, e no dia a dia do desenvolvimento, geralmente encontraremos as mesmas tags sendo utilizadas. Vejamos abaixo uma tabela contendo as tags mais utilizadas e mais importantes para dominar o HTML básico:

Tag | Descrição
----|----------
 ```<style> </style>``` | Introduz um código CSS ao documento HTML.
 ```<script> </script>``` | Introduz um código de Script, como JavaScript, ao documento HTML.
 ```<link/>``` | Possibilita fazer uma linkagem com documentos locais ou globais, como por exemplo fontes ou folhas de estilos.
 ```<meta/>``` | Possibilita incluir metadados na página.
 ```<h1> </h1> até <h6> </h6>``` | Tags para definir um título e subtítulos, variando de 1 a 6, sendo h1 o título mais importante e h6 o de menor importância.
 ```<p> </p>```| Tag para definir um parágrafo.
 ```<span> </span>``` | Define um span.
 ```<br/>``` | Realiza uma quebra de linha.
 ```<a> </a>``` | 	Tag de link, junto ao atributo href=”…” é responsável pela principal característica da web.
 ```<header> </header>``` | Define um cabeçalho – tag estrutural e semântica.
 ```<section> </section>``` | Define uma seção – tag estrutural e semântica.
 ```<article> </article>``` | Define um artigo – tag estrutural e semântica.
 ```<div> </div>``` | Define uma divisão – tag estrutural.
 ```<footer> </footer>``` | 	Define um rodapé – tag estrutural e semântica.
 ```<nav> </nav>``` | Define uma área de navegação (como menus) – tag estrutural e semântica.
 ```<table> </table>```  | Define uma tabela.
 ```<tr> </tr>``` | Define uma linha da tabela.
 ```<td> </td>``` | Define uma célula da tabela.
 ```<ol> </ol>``` | Define uma lista ordenada.
 ```<ul> </ul>``` | Define uma lista não ordenada.
 ```<li> </li>``` | Define o item de uma lista.
 ```<form> </form>``` | Define um formulário.
 ```<input>``` | 	Define os campos do formulário.
 ```<textarea> </textarea>```| Define uma área para o usuário digitar um texto.
 ```<button> </button>``` | Define um botão.
 ```<img/>``` | 	Permite inserir uma imagem no seu documento.
 ```<iframe> </iframe>```  | Define um quadro com conteúdo de outra página.
 ```<video> </video>```| Define um campo de vídeo.

## Classes e IDs no HTML

<img src="https://user-images.githubusercontent.com/72177982/104822040-c0b0af80-581e-11eb-8ff0-b703402f4a1f.png" width="100%">

As classes e os IDs são amplamente utilizados dentro dos elementos HTML. Eles definem um classe ou um ID único a uma ou mais tags HTML. Sua maior utilidade é para manipulação dos elementos, tanto através do CSS quanto de scripts. Portanto, entender como funcionam é uma das prioridades para se entender o básico do HTML.

#### Classes

Para atribuir uma ou mais classes ao elemento, basta incluir o atributo **class=”…”**.

Por exemplo, se temos diversos elementos de parágrafo, e queremos que os dois primeiros recebam a classe “blue” e os dois últimos a classe “red”, podemos fazer conforme o código abaixo:

```html
<p class="blue">Paragrafo da classe blue</p>
<p class="blue">Paragrafo da classe blue</p>
<p class="red">Paragrafo da classe red</p>
<p class="red">Paragrafo da classe red</p>
```

Digamos também que queiramos que o primeiro elemento das classes acima receba também uma classe chamada “primeiro”. Para isto, basta acrescentar a classe “primeiro”, separada apenas com um espaçamento entre ela e as demais classes:

```html
<p class="blue primeiro">Paragrafo da classe blue</p> 
<p class="blue">Paragrafo da classe blue</p> 
<p class="red primeiro">Paragrafo da classe red</p> 
<p class="red">Paragrafo da classe red</p>
```
Portanto, podemos incluir uma ou mais classes a qualquer elemento, e além disso, vários elementos podem receber uma mesma classe.

No CSS, JavaScript e outros, para poder reconhecer e selecionar uma classe, utilizamos um ***“.”*** e o nome da classe. Ou seja, nos casos acima, utilizaríamos “***blue***“, “***red***” e “***primeiro***“.

#### IDs

Já os IDs são parecidos com as classes, porém eles são únicos. Só podem ser utilizados em um único elemento, portanto não podem ser repetidos. Para declarar o ID, basta chamar o atributo **id=”…”**. Portanto, digamos que o código tenha três **```<div>```** e desejamos que a primeira receba o ID do **“primeira_div“**, para isso basta usar o código abaixo:

```html
<div id="primeira_div"> </div>

<div> </div>

<div> </div>
```

Portanto, ao declarar a id **“primeira_div”** à primeira **```<div>```**,  nenhum outro elemento do HTML, mesmo que referente a outra tag, deverá receber este ID. Ele é único e exclusivo deste elemento.

Diferentemente das classes, um ID é reconhecido e selecionado no CSS, JavaScript e outros através do **“#“**. Ou seja, no exemplo acima, o id seria reconhecida no **CSS** por **“#primeira_div“**.

Um elemento pode receber mais que um ID, porém recomenda-se utilizar apenas um único ID em um mesmo elemento.

#### Mesclando classes e IDs

Apesar de terem utilidades parecidas, porém diferentes, as classes e os IDs são atributos que podem ser utilizados em conjunto. Um elemento que receba um ID também pode receber uma ou mais classes. Além disso, uma classe pode receber o mesmo nome que um ID, e vice-versa, sem que isso afete sua funcionalidade. Porém, para melhor organização, é recomendado evitar essa prática e manter os nomes sempre diferentes entre IDs e classes.

Vejamos então o exemplo abaixo:

```html
<div id="primeira_div"> </div>

<div class="divisao"> </div>

<div id="terceira_div" class="divisao"> </div>

<div id="quarta_div" class="quarta_div"> </div>
```

Font: https://www.homehost.com.br/blog/tutoriais/html-basico/