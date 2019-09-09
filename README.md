# html-introducao

* Introdu��o ao HTML

# O que � HTML?

* � uma linguagem utilizada para constru��o de p�ginas na web, sendo uma linguagem de programa��o e marca��o de texto

# Criando sua primeira p�gina

* Digite o c�digo abaixo em algum editor de texto (bloco de notas, notepad++, sublime, etc) e Salve o arquivo com o nome `meu_primeiro_site.html`

~~~html
<!DOCTYPE html>
<html>
 
    <head>
 
        <title>Hello</title>
 
    </head>
    
    <body>
 
        <p>Ol�, mundo!</p>
    
    </body>
 
</html>
~~~

# Resultado

![example](./resources/image1.png)

# Vamos evoluir nosso c�digo

* Crie o arquivo `index.html`

* Declare o tipo do arquivo `DOCTYPE` e o idioma
~~~html
<!DOCTYPE html>
<html lang="pt-br">
~~~

* Preparando nossa p�gina
~~~html
<head>
	<meta charset="utf-8">
	<title>Minha p�gina</title>
</head>
~~~

* Preenchendo nossa p�gina e inserindo uma imagem
~~~html
<body>
	<h1>Minha p�gina</h1>
	<hr>
	<h3>Sobre</h3>
	<p>Abaixo possui uma imagem.</p>
	<img src="image2.png">
</body>
~~~

* Inserindo uma lista ordenada no `body`
~~~html
<ol>

	<li>T�tulo da p�gina</li>
	<li>Primeiro par�grafo</li>
	<li>Inser��o de uma imagem</li>

</ol>
~~~

* Inserindo links no `body`
~~~html
<hr>
<a href="https://www.devmedia.com.br/comandos-e-tags-html5/23618"><h4>Mais sobre Comandos e TAGS no HTML</h4></a>
~~~


* Fechando a nossa p�gina inserindo a tag `</html>`
~~~html
</html>
~~~
