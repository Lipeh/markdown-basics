## Markdown Basics 
<p><a href="http://daringfireball.net/projects/markdown/">Markdown </a> permite-lhe escrever usando um formato de texto simples, fácil para ler e escrever, do qual então se converte em HTML válido para visualização no GITHUB.</p>
### Escrita Básica 
####Parágrafos
<p>Parágrafos em Markdown são apenas uma ou mais linhas de texto consecutivos seguidos por uma ou mais linhas em branco.</p>
<pre><code>
Em 2 de julho, uma nave-mãe alienígena entrou em órbita da Terra e implantado várias dezenas nave espacial em forma de pires "destruidor", a cada 15 milhas (24 km) de largura. 

Em 3 de julho, os Cavaleiros Negros, um esquadrão de Marine Corps F / A-18 Hornets , participou de uma investida ao destruidor perto da cidade de Los Angeles.
</code></pre>
####Cabeçalhos
<p>Você pode criar um cabeçalho adicionando um ou mais <code>#</code> símbolos antes do seu texto de cabeçalho.</P>
 Número de <code>#</code> que você usa vão determinar o tamanho do seu cabeçalho.</p>
<pre><p># O maior título (uma tag <code>&lt;/h1&gt;</code>) 
## O segundo maior título  (uma tag <code>&lt;/h2&gt;</code>)
... 
###### O 6º maior título (uma tag <code>&lt;/h6&gt;</code> ) </p> </pre>
#### Bloco de Citação
<p> Você pode criar uma <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/blockquote">Bloco de Citação</a> com um <code>></code>.
<pre>Nas palavras de Abraham Lincoln:
<code>></code> Pardon My French</pre>
####Texto Styling
<p>Você pode fazer o texto <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/strong">**em negrito**</a> ou *itálico*. </p>
<pre> *Este texto pode ser itálico* **Este texto pode ser em negrito** </pre>
<p> Ambos <strong>negrito</strong> e <em>itálico</em> pode usar um <code>*</code> ou um <code>_</code> em torno do texto para o estilo. Isso permite que você combine os dois em negrito e itálico, se for necessário. </p>
** Todos_ devem_ participar da reunião ás 5 horas de hoje. **
Listas
Listas não ordenadas
Você pode fazer uma lista desordenada precedendo itens da lista ou com um * ou com um - .
* Item
* Item
* Item

- Artigo
- Artigo
- Artigo
Listas ordenadas
Você pode fazer uma lista ordenada precedendo alguns itens da lista com um número.
1. Item 1
2. O artigo 2
3. O artigo 3
Listas aninhadas
Você pode criar listas aninhadas pelo recuo dos itens da lista por dois espaços.
1. Item 1
2. No entanto, outro ponto a considerar.
2. O artigo 2
* Um corolário que não precisa ser solicitado.
 * Este é recuado em quatro espaços, porque dois espaços são mais longe do que o item acima.
 * Você pode querer fazer uma nova lista.
 3. O artigo 3
 A formatação do código
 Formatos em linha
 Use backticks (`) para formatar o texto em um formato especial monospace. Tudo dentro dos acentos graves, sem nenhuma formatação especial.
 Aqui está uma ideia: por que não vamos tomar `SuperiorProject`e transformá-lo em ` ** ** projeto razoável`.
 Várias linhas
 Você pode usar acentos graves triplos (```) para formatar o texto com o seu próprio bloco distinto.
 Confira este programa que eu  escrevi:
 `` `
 x = 0
 x = 2+2
 o que é x
 `` `
 Links
 Você pode criar uma ligação com uma linha por envolvimento de links texto entre colchetes ( [] ), em seguida, envolver uma ligação entre parênteses ( () ).
 Por exemplo, para criar um hiperlink para www.github.com, com o link que diz, Visite Github !, você escreveria isso em Markdown: [Visite Github !]  (www.github.com) .

