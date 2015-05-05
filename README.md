# markdown-basics.

#Noções básicas de remarcação
[Markdown](http://daringfireball.net/projects/markdown/) permite  você escrever usando um formato de texto simples fácil-de-ler, fácil-de-escrever, que então se converte em HTML válida para visualização no GitHub

##Escrita básica

###Parágrafos
Parágrafos em Markdown são apenas uma ou mais linhas de texto consecutivos seguido por uma ou mais linhas em branco.


> <code> Em 2 de julho, uma nave-mãe alienígena entrou em órbita da Terra e implantado várias dezenas de naves espaciais em forma de pires "destruidor", a cada 15 milhas (24 quilômetros) de largura. </code>

> <code> Em 3 de julho, os Cavaleiros Negros, um esquadrão de Marine Corps F / A-18 Hornets, participou de um assalto em um destroyer perto da cidade de Los Angeles. </code>

###Títulos

Você pode criar um título, adicionando um ou mais # símbolos antes de seu texto de título. O número de # você usa irá determinar o tamanho do título.

> <code>#</code> O maior título (uma tag h1) 

> <code>##</code> A segunda maior rubrica (uma h2 tag) 

> <code>###### O 6º maior título (uma h6 tag) </code>

###Blockquotes

Você pode indicar [blockquotes](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/blockquote) com um > .

> <code> Nas palavras de Abraham Lincoln: </code> 

> <code>></code> <code> Pardon meu francês </code>

###Estilo de Texto 

Você pode fazer o texto [**em negrito**](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/strong) ou [*itálico*](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/em).

> <code>* Este texto será itálico *</code> 

> <code>** Este texto vai ser ousado **</code>

Ambos **negrito** e _itálico_ pode usar um * ou um _ em torno do texto para o estilo. Isso permite que você combine os dois, em negrito e itálico, se necessário.

> <code> ** Todos _devem_ participar da reunião às 5 horas de hoje. ** </code>

###Listas

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

<code>1.</code>Item 1 

<code>2.</code>Número 2 

<code>3.</code>O item 3

####Listas aninhadas

Você pode criar listas aninhadas pelo recuo itens da lista por dois espaços.

 1. Item 1 

 <code> 1. </code> Uma conclusão do item acima. 
 
 <code> 2. </code> No entanto, outro ponto a considerar.  

2. Número 2

 <code> * </code> Um resultado que não precisa ser solicitado. 

 <code> * </code> Este é recuado quatro espaços, porque é dois espaços mais longe do que o item acima.  
  
 <code> * </code> Você pode querer considerar fazer uma nova lista.   
 
3. Item 3

###A formatação do código

####Formatos em linha

Use backticks simples ( <code>`</code>) para formatar o texto em um formato especial monospace. Tudo dentro dos acentos graves aparecem como está, sem nenhuma outra formatação especial.

> <code> Aqui está uma idéia: por que não vamos pegar `SuperiorProject` e transformá-lo em` ** ** project` razoável.</code>
####Várias linhas 

Você pode usar acentos graves triplos ( `` ` )  para formatar o texto como seu próprio bloco distinto.

> <code> Confira este programa puro que eu escrevi: </code> 

> <code> ``` </code>

> <code> x = 0 </code>

> <code> x = 2 + 2 </code>

> <code> que é x </code>

> <code> ``` </code>

###Links

Você pode criar uma ligação em linha por envolvimento link texto entre colchetes (  <code> [] </code> ), e, em seguida, envolver a ligação entre parênteses ( <code> () </code> ).

Por exemplo, para criar um hiperlink para [www.github.com](www.github.com) , com um texto de link que diz, Visita GitHub !, você escreveria isso em Markdown: [Visite GitHub!] (www.github.com) .

