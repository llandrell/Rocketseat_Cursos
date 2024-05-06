
  

# Módulo Básico de HTML5 e CSS3:

## Introdução à HTML5:

  

> O HTML5 é a linguagem padrão para criar e estruturar páginas da web. Ele fornece elementos básicos para construir o conteúdo e a organização de um site, como títulos, parágrafos, imagens, listas e links. Com o HTML5, você pode criar sites responsivos e interativos que se adaptam a diferentes dispositivos, como smartphones e tablets.

  

### Estrutura Básica de um Documento HTML5:

  

    <!DOCTYPE  html> 
     <html>
	     <head>	 
		     <title>Título da Página</title>
			<meta  charset="utf-8">
			</head>
			<body>
			</body>
        </html>

​​


### Elementos HTML Básicos:

  

`<!DOCTYPE  html>:` Declaração obrigatória que informa ao navegador qual versão do HTML está sendo utilizada.

`<html>:` Elemento raiz que contém todo o conteúdo da página HTML.

`<head>:` Seção que contém informações sobre a página, como título, metadados e links para arquivos externos (CSS, JavaScript).

`<title>:` Define o título da página que aparece na barra de título do navegador.

`<meta  charset="utf-8">:` Define a codificação de caracteres da página como UTF-8, permitindo a acentuação e caracteres especiais.

`<body>:` Seção que contém o conteúdo principal da página que o usuário visualiza.

### Elementos de Conteúdo:

`<p>`: Cria um parágrafo de texto.

`<h1>, <h2>, ..., <h6>`: Definem títulos de diferentes níveis (h1 sendo o mais importante e h6 o menos importante).

`<a  href="URL">Texto do link</a>:` Cria um link para outra página ou recurso na web.

`<img  src="caminho/para/imagem.jpg"  alt="Descrição da imagem">:` Insere uma imagem na página.

`<ul>`: Cria uma lista não ordenada.

`<li>`Item da lista</li>`: Adiciona itens à lista não ordenada.

`<ol>`: Cria uma lista ordenada.

`<li>Item da lista</li>`: Adiciona itens à lista ordenada.

`<p><strong>Texto importante</strong></p>`: Enfatiza o texto dentro de um parágrafo (negrito).

`<div>`: Define uma divisão ou seção na página, geralmente utilizada para agrupar e organizar outros elementos HTML.

### Tags Semânticas Adicionais:

 
`<header>`: Define o cabeçalho da página, geralmente contendo informações como logotipo, título do site e menu de navegação.

`<nav>`: Define uma seção de navegação, geralmente contendo links para diferentes páginas do site.

`<main`>: Define o conteúdo principal da página, onde o foco do usuário deve estar.

`<section>`: Define uma seção genérica na página, útil para organizar o conteúdo em diferentes áreas.

`<article>`: Define um conteúdo independente, como um post de blog ou um artigo de notícias.

`<footer>`: Define o rodapé da página, geralmente contendo informações como copyright, links para redes sociais e contato.

### Formulários HTML:

> Os formulários permitem que os usuários interajam com o site, enviando dados para serem processados. Eles são essenciais para coletar informações, realizar pesquisas, registrar usuários e muito mais.

  

Estrutura:
  

    HTML
    
    <form action = "URL" método = "POST/GET" >
    
    </form >



`<form>`: Define o formulário, especificando a URL para onde os dados serão enviados e o método de envio (POST ou GET).

  - como funciona os formularios: 

  - Expricacao do POST e GET no forms
    - GET: RECEBER e enviar recurso
      - é usado, os dados do formulário são anexados à URL como parte da string de consulta (query string). Isso significa que os dados são visíveis na própria URL. 
    - POST: ENVIAR recursos
      - Ao usar o método POST, os dados do formulário são enviados no corpo da solicitação HTTP, e não são visíveis na URL. Isso torna o método POST mais seguro para o envio de dados sensíveis
    - "query string" é uma parte de uma URL que contém dados enviados para o servidor quando uma solicitação é feita. Ela geralmente segue o caractere "?" na URL e consiste em pares de chave-valor separados por "&".

`type`: Especifica o tipo de dado que o elemento deve conter ou o comportamento do elemento. 

`name`: E usado para identificar os campos de entrada quando o formulário é enviado para o servidor, e define qual e o valor que vai ter no campo.

`type="hidden" ` é usado para criar um campo de entrada oculto em um formulário HTML. Este tipo de campo não é visível para o usuário na interface do formulário, mas seu valor é enviado junto com os outros dados do formulário quando ele é submetido.

`action`: Define a URL para onde os dados do formulário serão enviados.

`method`: Define o método de envio dos dados do formulário (POST ou GET).

`POST`: Envia os dados de forma oculta no corpo da requisição HTTP.

`GET`: Envia os dados como parte da URL (parâmetros de consulta).

`<label  for="nome" >nome</label>`: E usada para associar um rótulo descritivo a um campo de entrada e para acessibilidade, torna os formularios mais acessiveis e compreensíveis  
  <form>
    <label for="nome">Nome:</label>
    <input type="text" id="nome" name="nome">
    <br>
    <label for="email">Email:</label>
    <input type="email" id="email" name="email">
    <br>
    <button type="submit">Enviar</button>
  </form>

 -  Exemplos de Campos de Entrada:

  
 - tipos de imputs
    `<input  type="text"  id="nome"  name="nome" />`: Cria um campo de texto para entrada de nome.

    `<input  type="email"  id="email"  name="email"/>`: Cria um campo de email para entrada de endereço de email.

    `<input  type="password"  id="senha"  name="senha">:` Cria um campo de senha para entrada de senha.

    `<input type="checkbox" id="termos">`Usado para criar caixas de seleção que permitem aos usuários selecionar uma ou mais opções de um conjunto de opções. 
      
    `<select id="frutas" name="frutas">
        <option value="maca">Maçã</option>
    </select>` Option é usada dentro de um elemento <select> para definir as opções disponíveis em um menu suspenso 
    
    `<textarea id="mensagem" name="mensagem" rows="4" cols="50">`  E usado para criar uma área de texto multilinha em um formulário.

## Módulo Básico de CSS3: Estilizando Seu Conteúdo Web com Eficiência

> O CSS3 é a linguagem de estilização para páginas da web, permitindo controlar a aparência dos elementos HTML, como cores, fontes, tamanhos, espaçamentos, layouts e muito mais. Com o CSS3, você pode criar sites visualmente atraentes, responsivos e adaptáveis a diferentes dispositivos.

  

### Estrutura Básica de uma Regra CSS:

  

CSS

    seletor {
    
    propriedade1: valor1;
    
    propriedade2: valor2;
    
    ...
    
    }



- Seletor: Define o elemento HTML que será estilizado. Pode ser um tipo de elemento específico (p, h1, img), uma classe, um ID ou um seletor mais complexo com combinações e pseudo-classes.

	- Propriedade: Define o aspecto do elemento que será modificado, como cor, tamanho, tipo de letra, etc.

	- Valor: Define o valor da propriedade, como uma cor (#FF0000), um tamanho (16px), um tipo de letra (Arial), etc.

Exemplo:

  

    CSS
    
    p {
    
    cor azul;
    
    tamanho da fonte: 16px;
    
    }


### Propriedades CSS Comuns:

  

`color`: Define a cor do texto.

`font-family`: Define o tipo de letra do texto.

`font-size`: Define o tamanho do texto.

`text-align`: Define o alinhamento do texto (esquerda, centro, direita, justificado).

`background-color`: Define a cor de fundo do elemento.

`padding:` Define o espaço entre o conteúdo do elemento e suas bordas.

`margin:` Define o espaço entre o elemento e outros elementos ao seu redor.

`border:` Define a borda do elemento (estilo, largura, cor).

`width:` Define a largura do elemento.

`height:` Define a altura do elemento.

`display:` Define o tipo de display do elemento (bloco, inline, none).

`position:` Define a posição do elemento no layout da página (static, relative, absolute, fixed).

### Seletores CSS:

  

- Seletores por tipo de elemento: Utilizam o nome do elemento HTML (p, h1, img, etc.).

	 - Seletores por classe: Utilizam o atributo class do elemento HTML (.classe-nome).

	- Seletores por ID: Utilizam o atributo id do elemento HTML (#id-do-elemento).

	- Seletores descendentes: Combinam seletores para selecionar elementos dentro de outros elementos (p h1 { ... }).

	- Seletores de filho: Selecionam elementos que são filhos diretos de outro elemento (p > h1 { ... }).

	- Seletores de irmão: Selecionam elementos que são irmãos entre si (p + h1 { ... }).

- Pseudo-classes: Adicionam funcionalidades extras aos seletores (hover, focus, active, etc.).

Seletores de atributo: Selecionam elementos com base em seus atributos ([`href="link.com"], [data-atributo="valor"`]).

 - Combinando Seletores:

  

	> É possível combinar seletores para criar regras mais complexas e específicas. Por exemplo, você pode selecionar todos os parágrafos dentro de uma div com a classe conteudo:

  

    CSS
    
    div.conteudo p {
    
    cor: #333;
    
    tamanho da fonte: 14px;
    
    }


### Especificidade CSS:

  

> A especificidade define a prioridade de aplicação das regras CSS. Elementos, classes, IDs e estilos inline possuem diferentes níveis de especificidade. Quando várias regras se aplicam ao mesmo elemento, a regra com maior especificidade terá precedência.

  

 - Elementos: 1 ponto de especificidade.

- Classes e pseudo-classes: 100 pontos de especificidade.

- IDs: 1000 pontos de especificidade.

- Estilos inline: 10000 pontos de especificidade.

- Dicas para Escrever CSS Eficiente:

  

- Use nomes de classes descritivos e significativos.

- Organize seu código CSS em seções e blocos.

- Utilize comentários para explicar o que cada regra faz.

- Evite usar estilos inline sempre que possível.

- Crie um sistema de grid para organizar seus layouts.

- Utilize media queries para adaptar seus estilos a diferentes dispositivos.
