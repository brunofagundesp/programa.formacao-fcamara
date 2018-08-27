# programa.formacao-fcamara
Processo de seleção Fcamara - Front-end

1) A melhor forma de integrar 5 diferentes arquivos de estilo em um site seria da seguinte forma: colocar um <link> para cada página que necessitasse de um css específico, ex: 
login.html receberia o estilo-login.css .
Isso para casos específicos, caso não, poderia colocar todos os estilos em uma só página.

2) 1ª forma: colocar os <script> no final da página.
  2ª forma: otimizar os códigos css, tornando eles mais pequenos e mais conciso.
  3ª forma: utilizar arquivos de estilos e de escripts em diretórios separados da página, pois assim os mesmos ficam em cache no browser, diminuindo os pedidos HTTP.
  
  3) Uma das ferramentas seria o Loadster, w3c validator, porém conheço também o NeoLoad.
  
  4) Os blocos de construção de uma página HTML5 são: head, body, e dentro desses os principais são HEADER,
 FOOTER,
 NAV,
 ASIDE,
 ARTICLE,
 SECTION.
 
 5) A principal diferença entre os métodos GET e POST são a questão da visibilidade, em quanto o método GET a informação é anexada na URL e visível aos que estão acessando o site o método POST é enviado e encapsulado no corpo da requisição HTTP e não pode ser vista. 


6) block, inline, inline-block, none, list-item e table.

7) A Diferença é que no inline não pode ser definido weight e width, enquanto no inline-block é possível.

8)Relativa: é possível pocisionar com: top, right, left, bottom, e mesmo utilizando essas propriedados ele vai se mover, porém a sua posição original é preservada e o elemento seguinte não ocupa esse espaço, Fixa: O elemento é posicionada de forma fixa não se movendo conforme o rolar da página, e é sempre renderizado no canto superior esquerdo da página, Absoluta: essa propriedade retira o elemento da sua posição original, sendo assim o elemento a seguir irá ocupar o seu espaço, Estática: nada acontece com essa opção os elementos continuam onde foram renderizados.

9) Os métodos call e apply facilitam que você escreva um método e componha outros objetos, uma boa definição é que esta feature  proporciona emprestar um método, onde você pode definir uma função atribuída no contexto global sem mesmo ter um objeto ou classe como owner, e você pode tomar emprestado métodos de outros objetos ou classes.

10)O "==" compara "resultados", já o "===" compara valores e tipos sendo assim uma condição só seria true se a comparacação fosse com true.
