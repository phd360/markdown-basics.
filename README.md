# markdown-basics.

#Noções básicas de remarcação
[Markdown](http://daringfireball.net/projects/markdown/) permite  você escrever usando um formato de texto simples fácil-de-ler, fácil-de-escrever, que então se converte em HTML válida para visualização no GitHub

 ## 1.Escrita básica

###Parágrafos
Parágrafos em Markdown são apenas uma ou mais linhas de texto consecutivos seguido por uma ou mais linhas em branco.


Em 2 de julho, uma nave-mãe alienígena entrou em órbita da Terra e implantado várias dezenas de naves espaciais em forma de pires "destruidor", a cada 15 milhas (24 quilômetros) de largura.

Em 3 de julho, os Cavaleiros Negros, um esquadrão de Marine Corps F / A-18 Hornets, participou de um assalto em um destroyer perto da cidade de Los Angeles.

###Títulos

Você pode criar um título, adicionando um ou mais # símbolos antes de seu texto de título. O número de # você usa irá determinar o tamanho do título.

<code>#</code> O maior título (uma tag <h1>) 

<code>##</code> A segunda maior rubrica (uma <h2> tag) 

<code>######</code> O 6º maior título (uma <h6> tag)

###Blockquotes

Você pode indicar [blockquotes](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/blockquote) com um > .

Nas palavras de Abraham Lincoln: 

<code>></code> Pardon meu francês

###Estilo de Texto 

Você pode fazer o texto [**em negrito**](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/strong) ou [*itálico*](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/em).

<code>*</code>     Este texto será itálico    <code>*</code> 

<code>**</code>    Este texto vai ser ousado   <code>**</code>

Ambos **negrito** e _itálico_ pode usar um * ou um _ em torno do texto para o estilo. Isso permite que você combine os dois, em negrito e itálico, se necessário.

** Todos _deve_ participar da reunião às 5 horas de hoje. **
### 2.Listas

####Listas não ordenadas

Você pode fazer uma [lista desordenada] (https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul) precedendo itens da lista ou com um * ou um - .

<code>*</code>Item 

<code>*</code>Item

<code>*</code>Item 

<code>-</code>item 

<code>-</code>item 

<code>-</code>item

####Listas ordenadas

Você pode fazer uma [lista ordenada] (https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol) precedendo itens da lista com um número.

<code>1.</code> Item 1 
<code>2.</code> Número 2 
<code>3.</code> O item 3
Listas aninhadas

Você pode criar listas aninhadas pelo recuo itens da lista por dois espaços.

1. Item 1 
  1. Uma conclusão do item acima. 
  2. No entanto, outro ponto a considerar. 
2. Número 2 
  * Um resultado que não precisa ser solicitado. 
    * Este é recuado quatro espaços, porque é dois espaços mais longe do que o item acima. 
    * Você pode querer considerar fazer uma nova lista. 
3. Item 3

###A formatação do código

####Formatos em linha

Use backticks simples ( ` ) para formatar o texto em um formato especial monospace. Tudo dentro dos acentos graves aparecem como está, sem nenhuma outra formatação especial.

Aqui está uma idéia: por que não vamos pegar `SuperiorProject` e transformá-lo em` ** ** project` razoável.
####Várias linhas

Você pode usar acentos graves triplos ( `` ` ) para formatar o texto como seu próprio bloco distinto.

Confira este programa puro que eu escrevi: 

`` ` 
x = 0 
x = 2 + 2 
que é x 
`` `
###Links

Você pode criar uma ligação em linha por envolvimento link texto entre colchetes ( [] ), e, em seguida, envolver a ligação entre parênteses ( () ).

Por exemplo, para criar um hiperlink para [www.github.com](www.github.com) , com um texto de link que diz, Visita GitHub !, você escreveria isso em Markdown: [Visite GitHub!] (www.github.com) .

