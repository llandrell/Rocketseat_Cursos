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
      -