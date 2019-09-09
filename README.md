# html-introducao

* Introdução ao HTML

# O que é HTML?

* É uma linguagem utilizada para construção de páginas na web, sendo uma linguagem de programação e marcação de texto

# Criando sua primeira página

* Digite o código abaixo em algum editor de texto (bloco de notas, notepad++, sublime, etc) e Salve o arquivo com o nome `meu_primeiro_site.html`

~~~html
<!DOCTYPE html>
<html>
 
    <head>
 
        <title>Hello</title>
 
    </head>
    
    <body>
 
        <p>Olá, mundo!</p>
    
    </body>
 
</html>
~~~

# Resultado

![example](./resources/image1.png)

# Vamos evoluir nosso código

* Crie o arquivo `index.html`

* Declare o tipo do arquivo `DOCTYPE` e o idioma
~~~html
<!DOCTYPE html>
<html lang="pt-br">
~~~

* Preparando nossa página
~~~html
<head>
	<meta charset="utf-8">
	<title>Minha página</title>
</head>
~~~

* Preenchendo nossa página e inserindo uma imagem
~~~html
<body>
	<h1>Minha página</h1>
	<hr>
	<h3>Sobre</h3>
	<p>Abaixo possui uma imagem.</p>
	<img src="image2.png">
</body>
~~~

* Inserindo uma lista ordenada no `body`
~~~html
<ol>

	<li>Título da página</li>
	<li>Primeiro parágrafo</li>
	<li>Inserção de uma imagem</li>

</ol>
~~~

* Inserindo links no `body`
~~~html
<hr>
<a href="https://www.devmedia.com.br/comandos-e-tags-html5/23618"><h4>Mais sobre Comandos e TAGS no HTML</h4></a>
~~~


* Fechando a nossa página inserindo a tag `</html>`
~~~html
</html>
~~~
