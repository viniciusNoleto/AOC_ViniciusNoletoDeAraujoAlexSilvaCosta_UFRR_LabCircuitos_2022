<h1>Arquitetura e Organização de Computadores: Avaliação de Barramento</h1>
<h6>Este repositório é refrente à Avaliação de Barramento da disciplina Arquitetura e Organização de Computadores (DCC301) e seus resultados desenvolvidos pelos alunos Vinícius Nolêto de Araújo e Alex Silva Costa.</h6>
<h2>Temas:</h2>
<ul>
<li>Arquitetura de Compuadores;</li>
<li>Circuitos Digitais;</li>
<li>Componentes Eletrônicos;</li>
<li>MIPS;</li>
<li>Números Binários;</li>
<li>Processador 8 bits.</li>
</ul>
<h2>Legenda de Leitura:</h2>
<ul>
<li>'s?': Resultado final igual a ?;</li>
<li>'i?': Valor ? passado como input;</li> 
<li>'o?': Valor ? como output;</li>
<li>'X': Valor de Input Output definido pelo funcionamento do circuito em tempo real;</li>
</ul>
<h2>Softwares Utilizados:</h2>
<ul>
<li><a href='http://www.cburch.com/logisim/pt/index.html'>Logisim</a>: Usado para criação, testes e obtenção de resultados de circuitos dirgitais. Versão Utilizada: 2.7.1.</li>
</ul>
<h2>Material de Pesquisa Utilizado:</h2>
<ul>
<li><a href='https://www.youtube.com/'>Youtube</a>:</li>
<ul>
<li>Canal <a href='https://www.youtube.com/@tellmoitas9661'>Tell Moitas</a>;</li>
<li>Canal <a href='https://www.youtube.com/@newtonlago7665'>Newton Lago</a>.</li>
</ul>
<li>Material de estudo disponibilizado pelo professor Hebert disponível na pasta 'doc' deste repositório;</li>
<li>Site <a href='https://www.filipeflop.com/blog/entendendo-o-flip-flops/'>Filipe Flop.</li>
</ul>
<h2>Observações:</h2>
<h4>Os resultados não seguem a ordem das questões da Avaliação de Barramento, ao invés disto, a ordem de complexidade foi utilizada para ordenção.</h4>
<hr>
<h1 align='center'>RESULTADOS:</h1>
<br>
<h2>Questão 1: Flip Flop JK e Flip Flop D</h2>
<img hre="https://user-images.githubusercontent.com/85528669/204176646-9daa7f9a-0fc5-492c-868a-e45910cb7692.png">
<img hre="https://user-images.githubusercontent.com/85528669/204176692-1e90504d-7f31-4ce8-b783-f2c353f35bc1.png">
<h4>O modelo de Flip Flop utilizado foi o <i>Flip-Flop Mestre-Escravo</i>, pois outros modelos de Flip Flop resultaram em erro no programa Logisim. O modelo Mestre-Escravo possui um Flip Flop JK e um Flip Flip RS com o clock invertido, impedindo o que ocorra erro no caso <i>i11</i>.</h4>
<h2>Questão 3: Equivalencia de XOR</h2>
<img>
<h4>A porta lógica <i>XOR</i> possui como princípio que os dois valores sejam diferentes, logo basta comparar a negação de cada valor com o seu valor original e associar os valores a uma porta lógica <i>OU</i>.</h4>
<h2>Questão 2: Multiplexador</h2>
<img>
<h4>O Multiplexador funciona a partir de portas lógicas <i>E</i> encadeadas, onde as entradas são negadas para relacionarem-se com valores binários como '001', ou seja, as duas primeiras entradas desligadas e a última ligada.</h4>
<h2>Questão 11: Extensão de Sinal</h2>
<img>
<h4>O extensor de sinal aumenta o tamanho de um input, por exemplo, 'i1001' transforma-se em 'o00001001', transformando 4bits para 8bits.</h4>
<h2>Questão 4: Somador com número 4</h2>
<img>
<h4>O Somador funciona passando a corrente caso os valores de entrada sejam diferentes ou caso o resto da soma anterior seja igual a 1, neste caso o valor de soma é fixo, sendo ele, igual a 4.</h4>
<h2>Questão 7: Banco de Registradores</h2>
<img>
<h4>O Banco de Registradores funciona por meio da criação de diversos registradores organizados por endereços. Os registradores são 8 Flip Flops D ordenados e conectados a saída, gerando um número de 8bits e guardando-o. O Banco de Registradores recebe três inputs, um valor de 1bit que designa se um valor será lido ou escrito no Banco, o valor a ser guardado (caso vá escrever um registrador) e o endereço que ele será guardado ou lido.</h4>
<h2>Questão 13: Contador Síncrono</h2>
<img>
<h4>O Contador Síncrono funciona por meio do uso de Flip Flops D relacionados por meio de portas lógicas <i>E</i>, alterando o próximo valor apenas no caso de todos os anteriores sejam iguais a 1.</h4>
  <h2>Questão 6: Memória RAM</h2>
<img>
<h4>.</h4>
  <h2>Questão 5: Memória ROM</h2>
<img>
<h4>.</h4>
