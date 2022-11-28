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
<h4>O documento chamado <i>Relatório Avaliação Laboratório</i> de Circuitos presente neste repositório destrincha com maior especificidade o funcionamento de cada circuito presente nas questões posteriormente expostas.</h4>
<hr>
<h1 align='center'>RESULTADOS:</h1>
<br>
<h2>Questão 1: Flip Flop JK e Flip Flop D</h2>
<div>
<img src="https://user-images.githubusercontent.com/85528669/204176692-1e90504d-7f31-4ce8-b783-f2c353f35bc1.png" width="270px" height="180px">
<img src="https://user-images.githubusercontent.com/85528669/204176646-9daa7f9a-0fc5-492c-868a-e45910cb7692.png" width="270px" height="180px">
</div>
<h4>O modelo de Flip Flop utilizado foi o <i>Flip-Flop Mestre-Escravo</i>, pois outros modelos de Flip Flop resultaram em erro no programa Logisim. O modelo Mestre-Escravo possui um Flip Flop JK e um Flip Flip RS com o clock invertido, impedindo o que ocorra erro no caso <i>i11</i>.</h4>
<h2>Questão 3: Equivalencia de XOR</h2>
<img src="https://user-images.githubusercontent.com/85528669/204176771-7c0f2eb2-754f-459e-a3ae-9614f2e68328.png" width="380px" height="180px">
<h4>A porta lógica <i>XOR</i> possui como princípio que os dois valores sejam diferentes, logo basta comparar a negação de cada valor com o seu valor original e associar os valores a uma porta lógica <i>OU</i>.</h4>
<h2>Questão 2: Multiplexador</h2>
<img src="https://user-images.githubusercontent.com/85528669/204176740-c70fc79d-8d32-422f-9169-6f790453e1da.png" width="280px" height="300px">
<h4>O Multiplexador funciona a partir de portas lógicas <i>E</i> encadeadas, onde as entradas são negadas para relacionarem-se com valores binários como '001', ou seja, as duas primeiras entradas desligadas e a última ligada.</h4>
<h2>Questão 11: Extensão de Sinal</h2>
<img src="https://user-images.githubusercontent.com/85528669/204177775-79588be6-df55-400b-8340-b46fbacc5850.png" width="300px" height="180px">
<h4>O extensor de sinal aumenta o tamanho de um input, por exemplo, 'i1001' transforma-se em 'o00001001', transformando 4bits para 8bits.</h4>
<h2>Questão 4: Somador com número 4</h2>
<div>
<img src="https://user-images.githubusercontent.com/85528669/204176813-d60a9dbd-70e5-4f1f-aafb-ea2c613bb949.png" width="600px" height="180px">
<div align="center">
<img src="https://user-images.githubusercontent.com/85528669/204176877-f75b42d5-36bf-4a47-8891-f82d95db73cc.png" width="300px" height="180px">
</div>
</div>
<h4>O Somador funciona passando a corrente caso os valores de entrada sejam diferentes ou caso o resto da soma anterior seja igual a 1, neste caso o valor de soma é fixo, sendo ele, igual a 4.</h4>
<h2>Questão 7: Banco de Registradores</h2>
<div>
<img src="https://user-images.githubusercontent.com/85528669/204188148-ba84c16b-cb02-4649-8ad5-7e43ad4e4eb2.png" width="200px" height="260px">
<img src="https://user-images.githubusercontent.com/85528669/204188262-65bb93d4-6c27-4d93-9b86-5ecd00d999fa.png" width="250px" height="260px">
</div>
<h4>O Banco de Registradores funciona por meio da criação de diversos registradores organizados por endereços. Os registradores são 8 Flip Flops D ordenados e conectados a saída, gerando um número de 8bits e guardando-o. O Banco de Registradores recebe três inputs, um valor de 1bit que designa se um valor será lido ou escrito no Banco, o valor a ser guardado (caso vá escrever um registrador) e o endereço que ele será guardado ou lido.</h4>
<h2>Questão 13: Contador Síncrono</h2>
<img src="https://user-images.githubusercontent.com/85528669/204189262-0761f4d8-c24d-43c4-b6ac-66bf8aa14058.png" width="260px" height="200px">
<h4>O Contador Síncrono funciona por meio do uso de Flip Flops T relacionados por meio de portas lógicas <i>E</i>, alterando o próximo valor apenas no caso de todos os anteriores sejam iguais a 1.</h4>
<h2>Questão 6: Memória RAM</h2>
<div>
<img src="https://user-images.githubusercontent.com/85528669/204177218-d3d5c01b-2ac4-495a-84c3-359ee94829d8.png" width="220px" height="340px" align="top">
<img src="https://user-images.githubusercontent.com/85528669/204177286-85fcc191-8c47-46e7-9727-ef273d2befb2.png" width="350px" height="150px">
</div>
<h4>.</h4>
<h2>Questão 5: Memória ROM</h2>
<img src="https://user-images.githubusercontent.com/85528669/204176965-1f790004-9ac6-4558-bb23-fbac454414cd.png" width="220px" height="340px" align="top">
<img src="https://user-images.githubusercontent.com/85528669/204177055-b5869b42-3eb3-4c2f-8a0b-8558fe602fd9.png" width="350px" height="150px">
<h4>.</h4>
