# Database of Facial Expression Paper

<div>
  <article>
    O presente repositório apresenta a base de dados utilizada no trabalho de aquisição e classificação de expressões faciais utilizando sinais de Eletromiografia.
    <br>
    Outras informações sobre o projeto podem ser obtidas: https://github.com/raulfontenele/Facial_Expression_Classification
  </article>
  <div>
    O trabalho desenvolvido pelos seguintes autores: 
    <ul>
      <li>Paulo Cirillo S. Barboza</li>
      <li>Raul F. Santana</li>
      <li>George A. P. Thé</li>
    </ul>
  </div>
</div>

## Overview do Projeto
<div>
  O projeto consiste em um processo de aquisição de dados de 5 expressões faciais, utilizando sensores de Eletromiografia acoplados nos músculos da face. Baseado em um conjunto    de dados previamente adquirido e tratado, com a utilização de algoritmos de inteligência computacional, espera-se realizar a classificação das expressões escolhidas.
</div>
<div>
  <h3> As expressões utilizadas: </h3>
  <figure>
  <img height="300em" src="https://github.com/raulfontenele/Facial_Expression_Classification/blob/master/Images%20Overview/GestosC.jpg"/>
    <p>Fonte: <i>Ekman, P. (2002).  Facial action coding system (facs).A human face</i> </p>
    </figure>
  <article>
    As expressões foram escolhidas baseadas nos grupos musculares que as mesmas abrangem, onde buscou-se expressões com grupos musculares em comum, de forma a minimizar a             limitação na quantidade de sensores.
  </article>
</div>

<div>
  <h3> Sinais dos sensores: </h3>
  <div>
    <figure>
      <img height="320em" src="https://github.com/raulfontenele/Facial_Expression_Classification/blob/master/Images%20Overview/posicionamento2.png"/>
      <p>Fonte: Autores </p>
     </figure>
     <article>
       A imagem a cima apresenta o posicionamento utilizado para a aquisição de dados. Nota-se que existiam somente dois sensores disponíveis.
    </article>
  </div>
  <div>                                                                                                                                              
    <figure>
      <img height="320em" src="https://github.com/raulfontenele/Facial_Expression_Classification/blob/master/Images%20Overview/sinaisDepoisLG.png"/>
      <p>Fonte: Autores </p>
     </figure>
    <article>
       Na imagem estão apresentados os sinais adquiridos a partir dos dois sensores utilizados para a criação do <i>dataset</i> utilizado para a classificação, para cada uma das          expressões previamente definidas.
    </article>
  </div>                                                                                                                                               
</div>

<div>
  <h3> <i>Dataset</i>s: </h3>
  <figure>
    <img height="320em" src="https://github.com/raulfontenele/Facial_Expression_Classification/blob/master/Images%20Overview/dataset_aquisicaoLG2.png"/>
    <p>Fonte: Autores </p>
  </figure>
  <article>
    A imagem apresenta dois gráficos do tipo espalhamento de dados, de modo que em "a" são apresentados os dados referentes a "Aquisicao_02" desse repositório, com as cinco expressões previamente informadas, com um total 50.000 amostras adquiridas com a expressão mantida ao longo da janela de aquisição. Em "b" são apresentados os dados referente ao <i>dataset</i> gerado, com uma amostragem aleatória de 10% em relação a "Aquisicao_02", para cada uma das 5 expressões faciais, totalizando 5.000 amostras.
  </article>
</div>
