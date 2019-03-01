
<h1>Markdown</h1>

<h2>O que é Markdown?</h2>

Makrdown é uma linguagem de marcação (markup language) leve, escrita em 2004 em Perl por John Gruber e colaboração de Aaron Swartz. Focado no usuário markdown foi criada para ser uma ferramenta fácil para escrever, fácil para ler. Seu design permite a conversão para muitos formatos de saída. Markdown tem grande uso para criação de conteúdo em Fóruns, rich text e arquivos Readme, sua sintaxe de comandos é:
    
<h2>1-Títulos </h2>

 # Título nível 1		
 ## Título nível 2		
 ### Título nível 3			
 #### Título nível 4			
 ##### Título nível 5		
 ###### Título nível 6	
	
</blockquote>
Saída

# Título nível 1
## Título nível 2
### Título nível 3
#### Título nível 4
##### Título nível 5
###### Título nível 6

<h2>2-Parágrafos e quebras de linha</h2>
    <p> Esta é uma linha. </p>	
	  <p> Este é o primeiro parágrafo br e este o segundo parágrafo.</p>

Saída
<p> Esta é uma linha.</p>
<p> Este é o primeiro parágrafo<br> e este o segundo parágrafo.</p>
<h2>3-Ênfase</H2>
	    
    <Strong> Data Sciente é fantástico. </strong>
	Data Sciente é <strong> fantástico. </strong>
    <em>Data Science é fantástisco. </em>
    Data Science é <em> fantástico. </em>
	Data Science é _fantástico._
    <strong>_Data Science é fantástico._</strong> 
    *Data Science é fantástico.*
    Data Science é <em>**fantástico.**</em>


Saída

<strong> Data Sciente é fantástico. </strong>

Data Sciente é <strong> fantástico. </strong>

<em>Data Science é fantástisco. </em>

Data Science é <em> fantástico. </em>

Data Science é _fantástico._

<strong>_Data Science é fantástico._</strong> 

*Data Science é fantástico.*

Data Science é <em>**fantástico.**</em>

<h2>4-Links</h2>

    [Site da DSA](https://www.datascienceacademy.com.br)
    [Site da DSA](https://www.datascienceacademy.com.br "Clique e conheça")
	<a href=https://www.datascienceacademy.com.br>DSA</a>
	<roberts.oliveira@outlook.com>
	<a href="mailto:roberts.oliveira@outlook.com.com">Este é meu email</a>
   	
    obs: O clique e conheça pode ser visto passando o mouse sobre o link
Saída

[Site da DSA](https://www.datascienceacademy.com.br)

[Site da DSA](https://www.datascienceacademy.com.br "Clique e conheça")

<a href="https://www.datascienceacademy.com.br">DSA</a>

<roberts.oliveira@outlook.com>

<a href="mailto:roberts.oliveira@outlook.com.com">Este é meu email</a>

<h2>5-Bloco de citação </h2>

    <blockquote> </blockquote>, >

    blockquote>
    	Aqui você pode inserir seus comentarios<br> sobre o projeto de Data Science
    </blockquote>
    
    >Quando precisar mudar de linha use **br**<br> para não ter problema 
Saída

<blockquote>
	Aqui você pode inserir seus comentarios<br> sobre o projeto de Data Science
</blockquote>

>Quando precisar mudar de linha use **br**<br> para não ter problema 

<h2>6-Listas</h2>

As listas podem ser ordenadas e não ordenadas, veja abaixo que todos os exemplos estão na sequência 1,3,2 nas listas não ordenadas a classificação é feita pelo nome definido, na lista ordenada o index mostra a sequência correta.

	
	Cria lista não ordenada
    * item1
    * item3
    * item2
    
	Cria lista não ordenada
    <ul>
    	<li>item1</li>
    	<li>item3</li>
    	<li>item2</li>
    </ul>
    
	Cria lista ordenada
    <ol>
    	<li>item1</li>
    	<li>item3</li>
    	<li>item2</li>
    </ol>
Saída

* item1
* item3
* item2

<ul>
	<li>item1</li>
	<li>item3</li>
	<li>item2</li>
</ul>

<ol>
	<li>item1</li>
	<li>item3</li>
	<li>item2</li>
</ol>

<h2>7-Imagens</h2>
    

    ![leitura](http://www.gifs-animados.es/gifs-imagenes/b/biblioteca/gifs-animados-biblioteca-6190163.gif)
    <img src="http://www.gifs-animados.es/gifs-imagenes/b/biblioteca/gifs-animados-biblioteca-3116081.gif" alt = "Leitura"/>
Saída
<p><br></p>
![leitura](http://www.gifs-animados.es/gifs-imagenes/b/biblioteca/gifs-animados-biblioteca-6190163.gif)
<p><br></p>

<img src="http://www.gifs-animados.es/gifs-imagenes/b/biblioteca/gifs-animados-biblioteca-3116081.gif" alt = "Leitura"/>

<h2>Tabelas</h2>
    - [] 
Inserir um hífen, espaço e depois colchetes[]

    - [X]texto 1 
    - [ ]texto 2
    - [ ]texto 3
Saída
  
- [X]texto 1 
- [ ]texto 2
- [ ]texto 3


<h2>Caracter escape</h2>

Caracteres que podem ser impressos na tela com a \ 

    \   backslash (barra invertida)
    `   backtick (crase)
    *   asterisk (asterisco)
    _   underscore
    {}  curly braces (chaves)
    []  square brackets (colchetes)
    ()  parentheses (parênteses)
    #   hash mark (sustenido / hash / jogo da velha)
    +   plus sign (sinal de "mais" ou somar)
    -   minus sign (hyphen) (sinal de menos ou hífen)
    .   dot (ponto)
    !   exclamation mark (ponto de exclamação)

    \*asterisco\*
    \(parênteses\)


Saída

\*asterisco\*

\(parênteses\)

<h2>Barras horizontais</h2>

    * * * 
    ***
    ******
    ---
    - - -
    ----------------------------

Saída

* * * 
***
******
---
- - -
----------------------------


-----------------------------------------------------------------------------------------
All examples were described using MarkdownPad2

[MarkdownPad2](http://markdownpad.com/)

[Download MarkdownPad2](http://markdownpad.com/download.html)

Copyright © 2011-2019 Evan Wondrasek / Apricity Software LLC 

-----------------------------------------------------------------------------------------
[Markdown](https://daringfireball.net/projects/markdown/)

Markdown is free software, available under the terms of a BSD-style open source license.

License

Copyright © 2004, John Gruber
http://daringfireball.net/
All rights reserved.
