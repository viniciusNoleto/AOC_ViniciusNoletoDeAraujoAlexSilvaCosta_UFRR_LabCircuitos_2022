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
<li><a href='http://www.cburch.com/logisim/pt/index.html'>Logisim</a>: Usado para criação, testes e obtenção de resultados de circuitos dirgitais.</li>
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
<img>
<h4>O modelo de Flip Flop utilizado foi o <i>Flip-Flop Mestre-Escravo</i>, pois outros modelos de Flip Flop resultaram em erro no programa Logisim. O modelo Mestre-Escravo possui um Flip Flop JK e um Flip Flip RS com o clock invertido, impedindo o que ocorra erro no caso <i>i11</i>.</h4>
<h2>Questão 3: Equivalencia de XOR</h2>
<img>
<h4>A porta lógica <i>XOR</i> possui como princípio que os dois valores sejam diferentes, logo basta comparar a negação de cada valor com o seu valor original e associar os valores a uma porta lógica <i>OU</i>.</h4>
<h2>Questão 2: Multiplexador</h2>
<img>
<h4>O Multiplexador funciona a partir de portas lógicas <i>E</i> encadeadas, onde as entradas são negadas para relacionarem-se com valores binários como '001', ou seja, as duas primeiras entradas desligadas e a última ligada.</h4>
