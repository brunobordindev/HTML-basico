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
        - [3º passo – criando a primeira sessão com artigos](#html-básico)
        - [4º passo – criando nossa segunda sessão com iframes e uma tabela](#html-básico)
        - [5º passo – criando a terceira sessão com um formulário de “contato”](#html-básico)
        - [6º passo – criando o rodapé da página](#html-básico)
        - [7º passo – ajustes finais](#html-básico)

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

# Criando uma página com elementos do HTML básico

Neste momento, se você leu e acompanhou os tópicos anteriores, já pode dizer que compreende o básico do HTML. Porém, assim como qualquer linguagem de computação, seja de marcação ou programação, uma das coisas mais importantes a se fazer é praticar. Portanto, vamos agora colocar em prática nossos estudos.

Vamos criar uma página utilizando o básico do HTML passo a passo. Observe que não vamos utilizar o CSS e nem o JavaScript. Porém, com essa estrutura, a  página já estará pronta para depois receber uma estilização e interações, através do CSS e do JavaScript.

## HTML básico:
### 1º passo – criando uma página

Inicialmente, vamos criar um documento com a extensão **.html**. Vamos utilizar como exemplo o arquivo **index.html**. Posteriormente vamos iniciar criando uma estrutura básica do HTML e incluindo um título. Observe que vamos incluir um atributo **lang** com o valor **pt-br** à tag **```<html>```**. Dessa forma, o navegador e os mecanismos de busca entenderão que o nosso documento HTML se trata de um documento no idioma português do Brasil (**pt-br**). Portanto, vejamos o código da página abaixo:

```html
<!DOCTYPE html>

<html lang="pt-br">

<head>
    <title>Aprendendo o HTML Básico</title>
    <meta charset="utf-8">
</head>

<body>


</body>

</html>
```

### 2º passo – criando o cabeçalho

Agora que já criamos a estrutura básica, vamos criar a primeira divisão da página HTML. Inicialmente vamos criar um header básico no HTML, contendo apenas um título com uma descrição e um menu, em forma de lista não ordenada. Porém, por enquanto, vamos manter no menu a lista contendo apenas itens sem descrição. Ao finalizar nosso projeto, voltamos a mexer nessa parte.

Dessa forma, nosso código agora será:

```html
<!DOCTYPE html>

<html lang="pt-br">

<head>
    <title>Aprendendo o HTML Básico</title>
    <meta charset="utf-8">
</head>

<body>

    <header>
        <h1>Minha primeira página HTML</h1>
        <p>Aprendendo HTML Básico com exercicio prático</p>
        <br/>
        <nav>
            <p>Menu:</p>
            <ul>
                <li>item 1</li>
                <li>item 2</li>
                <li>item 3</li>
            </ul>
        </nav>
    </header>

</body>

</html>
```
Portanto, nossa página já começa a ganhar vida. Se abrir o arquivo no navegador, já podemos visualizar a página como na imagem abaixo:

<img src="https://user-images.githubusercontent.com/72177982/104849854-c5cb3880-58ca-11eb-898f-2d7856884ff5.png" width="100%">

### 3º passo – criando a primeira sessão com artigos

Agora que já criamos o cabeçalho, vamos continuar a formatação da página inserindo elementos de texto. Inicialmente vamos incluir uma divisão **```<main>```** pois conterá o conteúdo principal da página. Posteriormente vamos criar uma sessão e dentro dela, vamos incluir dois artigos, sendo que um deles conterá também a imagem abaixo, que deverá ser salva na mesma pasta do documento HTML.:

<img src="https://user-images.githubusercontent.com/72177982/104850149-260eaa00-58cc-11eb-8f1d-a68b56c874c6.png" width="1000%">

Portanto, vamos acrescentar ao nosso código:

```html
<main>

    <section id="sessao_principal">

        <h2>Sobre o artigo HTML Básico</h2>

        <article>
            <h3>O que aprendi com o artigo HTML Básico</h3>
            <p>Inicialmente, aprendi sobre o Que é HTML</p>
            <p>Posteriormente aprendi como funciona o HTML e sua estrutura básica</p>
            <p>Posteriormente aprendi sobre as Tags do HTML</p>
            <p>Posteriormente aprendi sobre classes e IDs</p>
            <p>...</p>
            <img src="img_exemplo.jpg">
        </article>

        <article>
            <h3>O que estou aprendendo agora:</h3>
            <p>Agora estou fazendo exercicios práticos para criar uma página HTML!</p>
        </article>

    </section>

</main>
```
Agora nossa página já começa a ganhar uma complexidade maior. Vejamos na imagem abaixo como deve ficar a página com os exemplos do código:

![image](https://user-images.githubusercontent.com/72177982/104850205-7b4abb80-58cc-11eb-9e35-ce1f574a93bc.png)

### 4º passo – criando nossa segunda sessão com iframes e uma tabela

Agora que já criamos o conteúdo principal, vamos criar uma segunda sessão utilizando os recursos de **iframes** e também contendo **uma tabela** contendo as tags de título. Portanto, vejamos abaixo a continuação do nosso código:


```html
<section id="sessao_2">

    <div class="divisao">
        <h2>Onde aprender mais sobre HTML Básico</h2>
        <p>Para aprender mais sobre HTML Básico e outros conteúdos podemos acessar o blog da Homehost</p>
        <iframe width="400px" height="400px" src="https://www.homehost.com.br/blog/"></iframe>
        <p><a href="https://www.homehost.com.br/blog/">Site do blog da Home Host</a></p>
    </div>

    <br>
    <div>

        <h2>Minha primeira tabela</h2>
        <p>Minha tabela contendo as tags de título</p>

        <table>
            <tr>
                <th>tag</th>
                <th>descrição</th>
                <th>exemplo</th>
            </tr>
            <tr>
                <td>h1</td>
                <td>Título 1</td>
                <td><h1>exemplo</h1></td>
            </tr>
            <tr>
                <td>h2</td>
                <td>Título 2</td>
                <td><h2>exemplo</h2></td>
            </tr>
            <tr>
                <td>h3</td>
                <td>Título 3</td>
                <td><h3>exemplo</h3></td>
            </tr>
            <tr>
                <td>h4</td>
                <td>Título 4</td>
                <td><h4>exemplo</h4></td>
            </tr>
            <tr>
                <td>h5</td>
                <td>Título 5</td>
                <td><h5>exemplo</h5></td>
            </tr>
            <tr>
                <td>h6</td>
                <td>Título 6</td>
                <td><h6>exemplo</h6></td>
            </tr>
        </table>

    </div>

</section>
```

Dessa forma, esta sessão da página ficará como no exemplo da imagem abaixo:

![image](https://user-images.githubusercontent.com/72177982/104855087-76e0cb80-58e9-11eb-98d3-0b79b1c1e8d5.png)

### 5º passo – criando a terceira sessão com um formulário de “contato”

Anteriormente **criamos sessões contendo** textos, imagem e até mesmo iframe. Nesta sessão, vamos atribuir um ID contato. Portanto, vamos incluir nela um formulário de contato.

Neste artigo, por se tratar de HTML básico, não vamos explicar muito a respeito de como enviar um formulário. Porém, posteriormente você pode aprofundar estas questões no nosso artigo sobre **formulários HTML**. Desta forma você estará apto a incluir formulários com envio para e-mail.

Vamos continuar com a página de HTML básico, criando agora a seguinte sessão contendo formulário:

```html
<section id="contato">

    <h2>Entre em contato</h2>
    <p>Preencha o formulário abaixo para poder entrar em contato!</p>

    <form method="get">

        <div>
            <span>Nome:</span>
            <input type="text" name="nome">
        </div>
        <div>
            <span>Email:</span>
            <input type="email" name="email">
        </div>
        <div>
            <span>Mensagem:</span>
            <textarea></textarea>
        </div>
        <div>
            <input type="submit" value="enviar">
        </div>

    </form>

</section>
```

Com esse código, agora vamos verificar que ao abrir a página ela conterá um formulário ao final. O resultado será como na imagem de exemplo abaixo:

![image](https://user-images.githubusercontent.com/72177982/104855212-346bbe80-58ea-11eb-954e-45207104b252.png)

### 6º passo – criando o rodapé da página

Agora que já criamos toda a estrutura da página, vamos finalizar incluindo nela um rodapé. Este rodapé conterá apenas uma mensagem. Portanto, vejamos o código do nosso rodapé abaixo:

```html
<footer>

    <p>Todos os direitos reservados</p>

</footer>
```

Com isso, logo abaixo do nossa sessão contato, temos então o rodapé conforme a imagem abaixo:

![image](https://user-images.githubusercontent.com/72177982/104855279-93313800-58ea-11eb-8616-c0918cb4e3c8.png)

### 7º passo – ajustes finais

Ao chegar até aqui, significa que já concluímos toda nossa página. Porém lembra-se que criamos em nosso cabeçalho um menu que modificaríamos depois?

Pois bem, você deve ter percebido que incluímos um ID a todas nossas sessões. Dessa forma, vamos agora modificar o menu, incluindo um link que ao ser clicado redirecione diretamente às sessões. Portanto, nosso cabeçalho da página HTML agora será como no código do exemplo abaixo:

```html
<header>

        <h1>Minha primeira página HTML</h1>
        <p>Aprendendo HTML Básico com exercicio prático</p>
        <br/>

        <nav>

            <p>Menu:</p>

            <ul>
                <li><a href="#sessao_principal">Sobre o artigo HTML Básicol</a></li>
                <li><a href="#sessao_2">Onde aprender mais sobre HTML Básico</a></li>
                <li><a href="#contato">Entre em Contato</a></li>
            </ul>

        </nav>

    </header>
```
Portanto, o cabeçalho conterá agora um menu conforme o da imagem abaixo:

![image](https://user-images.githubusercontent.com/72177982/104855345-fb801980-58ea-11eb-9349-52aca464f5b8.png)

Observe que agora, ao clicar em qualquer um dos itens da lista, a página será direcionada diretamente para a posição dos IDs referenciados no link.

Finalizamos então a nossa página contendo elementos de HTML básico.

Dessa forma, você pode utilizar o código final para estudar e modificar. O mesmo se encontra no exemplo abaixo:

```html

<!DOCTYPE html>

<html lang="pt-br">

<head>
    <title>Aprendendo o HTML Básico</title>
    <meta charset="utf-8">
</head>

<body>

    <header>
        <h1>Minha primeira página HTML</h1>
        <p>Aprendendo HTML Básico com exercicio prático</p>
        <br/>
        <nav>
            <p>Menu:</p>
            <ul>
                <li><a href="#sessao_principal">Sobre o artigo HTML Básicol</a></li>
                <li><a href="#sessao_2">Onde aprender mais sobre HTML Básico</a></li>
                <li><a href="#contato">Entre em Contato</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="sessao_principal">
            <h2>Sobre o artigo HTML Básico</h2>
            <article>
                <h3>O que aprendi com o artigo HTML Básico</h3>
                <p>Inicialmente, aprendi sobre o Que é HTML</p>
                <p>Posteriormente aprendi como funciona o HTML e sua estrutura básica</p>
                <p>Posteriormente aprendi sobre as Tags do HTML</p>
                <p>Posteriormente aprendi sobre classes e IDs</p>
                <p>...</p>
                <img src="img_exemplo.jpg">
            </article>
            <article>
                <h3>O que estou aprendendo agora:</h3>
                <p>Agora estou fazendo exercicios práticos para criar uma página HTML!</p>
            </article>
        </section>
    </main>

    <br/>
    <br/>

    <section id="sessao_2">

        <div class="divisao">
            <h2>Onde aprender mais sobre HTML Básico</h2>
            <p>Para aprender mais sobre HTML Básico e outros conteúdos podemos acessar o blog da Homehost</p>
            <iframe width="400px" height="400px" src="https://www.homehost.com.br/blog/"></iframe>
            <p><a href="https://www.homehost.com.br/blog/">Site do blog da Home Host</a></p>
        </div>

        <br>

        <div>

            <h2>Minha primeira tabela</h2>
            <p>Minha tabela contendo as tags de título</p>
            <table>

                <tr>
                    <th>tag</th>
                    <th>descrição</th>
                    <th>exemplo</th>
                </tr>
                <tr>
                    <td>h1</td>
                    <td>Título 1</td>
                    <td><h1>exemplo</h1></td>
                </tr>
                <tr>
                    <td>h2</td>
                    <td>Título 2</td>
                    <td><h2>exemplo</h2></td>
                </tr>
                <tr>
                    <td>h3</td>
                    <td>Título 3</td>
                    <td><h3>exemplo</h3></td>
                </tr>
                <tr>
                    <td>h4</td>
                    <td>Título 4</td>
                    <td><h4>exemplo</h4></td>
                </tr>
                <tr>
                    <td>h5</td>
                    <td>Título 5</td>
                    <td><h5>exemplo</h5></td>
                </tr>
                <tr>
                    <td>h6</td>
                    <td>Título 6</td>
                    <td><h6>exemplo</h6></td>
                </tr>
            </table>

        </div>

    </section>

    <section id="contato">

        <h2>Entre em contato</h2>
        <p>Preencha o formulário abaixo para poder entrar em contato!</p>

        <form method="get">

            <div>
                <span>Nome:</span>
                <input type="text" name="nome">
            </div>
            <div>
                <span>Email:</span>
                <input type="email" name="email">
            </div>
            <div>
                <span>Mensagem:</span>
                <textarea></textarea>
            </div>
            <div>
                <input type="submit" value="enviar">
            </div>

        </form>

    </section>

    <footer>
        <p>Todos os direitos reservados</p>
    </footer>

</body>

</html>
```

Neste artigo, você já pode aprender bastante a respeito do HTML. Iniciamos com explicações teóricas, e posteriormente aliamos a exemplos práticos. Portanto, passamos por todo o conteúdo básico do HTML.

Font: https://www.homehost.com.br/blog/tutoriais/html-basico/