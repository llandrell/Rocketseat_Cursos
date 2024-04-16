# Modulo Basico de HTML 5 e CSS
---

- Revisao basica (HyperText Markup Language).
    - <p>Parágrafo de texto.</p>
      <h1>Título de nível 1</h1>
      <h2>Título de nível 2</h2>
      ...
      <h6>Titulo de nivel 6</h6>
      <a href="https://www.exemplo.com">Link para exemplo.com</a>
      <img src="caminho/para/imagem.jpg" alt="Descrição da imagem">
      <ul>
          <li>Item da lista não ordenada</li>   
            <li>Outro item da lista não ordenada</li>
      </ul>
        <ol>
            <li>Item da lista ordenada</li>
            <li>Outro item da lista ordenada</li>
        </ol>
      <p>Este é um <strong>texto importante</strong> em um parágrafo.</p>
      - tag DIV Funcionalidade
        - Sua função principal é criar divisões ou seções na página, por si só, a <div> não possui nenhum significado semântico específico, mas é utilizada para agrupar e organizar outros elementos HTML.

- Formularios HTML
  Os formulários em HTML são uma maneira poderosa de interação entre os usuários e os sites, permitindo a coleta de informações e o envio de dados para processamento adicional 
  1. Use <label> para cada campo de entrada:
  2 . Use atributos id e for para associar rótulos a campos de entrada: 
  - <form>: Essa é a tag principal que define um formulário em HTML.
      -<form action="/enviar_dados" method="post">
    - Estrutura do FORM: 
      - action: para onde o formulario vai ser enviado, method e a forma que vai ser enviado (verbos) get e post, get receber e envia recursos pela URL e post envia pelo corpo 
    - <input>: Esta é a tag mais fundamental usada para criar campos de entrada em um formulário. O atributo type especifica o tipo de entrada, como texto, email, senha, número, etc. Outros atributos como name, id, e value podem ser usados para identificar e definir os valores dos campos.
      - types 
        * text: Campo de texto simples.
        * password: Campo de senha, onde os caracteres são ocultados.
        * email: Campo de entrada para endereço de e-mail.
        * number: Campo de entrada para números.
        * checkbox: Caixa de seleção (checkbox).
        * radio: Botão de opção (radio button).
        * file: Campo para upload de arquivos.
        * submit: Botão de envio de formulário.
        * reset: Botão para redefinir o formulário.
        * button: Botão genérico.
          etc.
    - <label>: Essa tag é usada para associar um rótulo descritivo a um campo de entrada. 
      - <label for="nome">Nome:</label>
        <input type="text" id="nome" name="nome">
    - <textarea>: Esta tag é usada para criar uma área de texto multilinha
    - <select> e <option>: Usadas juntas, essas tags criam menus suspensos (também conhecidos como listas de seleção). <select> define a lista suspensa, enquanto <option> define as opções dentro dessa lista.
    - <button>: Esta tag é usada para criar botões dentro de um formulário. Ela pode ser usada para enviar um formulário (type="submit"), limpar os campos do formulário (type="reset"), ou simplesmente executar um script JavaScript quando clicada (type="button").
    - <fieldset> e <legend>: Essas tags são usadas para agrupar elementos relacionados em um formulário. <fieldset> cria uma área visualmente destacada ao redor do grupo de elementos, enquanto <legend> fornece um título ou legenda para esse grupo.
      - <fieldset>
          <legend>Dados Pessoais</legend>
          <label for="nome">Nome:</label>
    - <datalist> e <option>: Essas tags são usadas para criar listas de opções personalizadas para campos de entrada do tipo texto. Os elementos <option> dentro de <datalist> definem as opções que aparecerão quando os usuários digitarem no campo de texto.
      - <label for="frutas">Escolha uma fruta:</label>
        <input list="lista_frutas" id="frutas" name="frutas">
        <datalist id="lista_frutas">
          <option value="Maçã">
          <option value="Banana">

  
    
- CSS (Cascading Style Sheets).
  - p {
      color: blue;
      font-size: 16px;
      }
  - especificidade CSS
      Elementos, pseudo-elementos e pseudo-classes: Cada elemento HTML tem uma especificidade básica de 1.

      Classes, pseudo-classes e atributos: Cada classe, pseudo-classe (como :hover) ou atributo adiciona +10 à especificidade.

      IDs: Cada ID adiciona +100 à especificidade.

      Estilos em linha: Estilos inline (definidos diretamente em um elemento HTML usando o atributo style) têm a maior especificidade, +1000.

    - Para definir a cor do texto em CSS, você pode usar a propriedade color 
      -  p {
              color: red;
            }  



    - Aluguns elementos css
      -font-family é usada para definir a fonte ou lista de fontes a serem usadas para exibir o texto em um elemento HTML.
      -font-size é usada para definir o tamanho do texto em um elemento HTML.
      -line-height é usada para definir a altura da linha em um elemento
      -font-weight é usada para especificar a espessura da fonte 
      -color é usada para definir a cor do texto em um elemento 
      -width é usada para definir a largura de um elemento
      -margin é usada para definir o espaçamento entre um elemento HTML e os elementos ao seu redor. Ela permite especificar valores para o espaçamento nas quatro direções: superior, direita, inferior e esquerda
        - margin: 0 auto 72px; define um elemento com margem superior e inferior de 0 pixels, margem lateral automática para centralizar horizontalmente e uma margem inferior de 72 pixels.
      -border é usada para definir a borda de um elemento. Ela pode ser usada para especificar a largura, estilo e cor da borda em torno de um elemento HTML.
        -order 1px red solid; cria uma borda ao redor de um elemento HTML com uma largura de 1 pixel, cor vermelha e estilo sólido.
      