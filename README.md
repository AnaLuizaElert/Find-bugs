# Documento auxiliar para encontrar os bugs 

<h1>Itens auxiliar para escanear</h1>
<a href="https://find-bugs.vercel.app">Link para o vercel</a>
<img src="https://github.com/AnaLuizaElert/Find-bugs/assets/107824361/174b2413-f916-4715-8a5c-27547acaeb36">

<h1>Regra de negócio:</h1>
A página de pontuação deverá atualizar automaticamente a pontuação dos níveis que o jogador tiver jogado, caso o jogador perca um nível a pontuação deverá permanecer a anterior.
A página do jogo deverá conter a quantidade maior ou igual de inimigos propostos inicialmente, porém só deverão ser mortos a quantidade que foi requisitada na página de informações do jogo. Ademais, a cada segundo deverá mudar a quantidade de tempo restante para um segundo a menos.
Ao clicar em um inimigo utilizando o cursor, após dois segundos, este deverá desaparecer e adicionar um à quantidade de inimigos restantes.
Ao clicar em um amigo utilizando o cursor, após dois segundos, deverá ser retirado um coração do jogador.
Ao perder todos os corações, deverá ser mostrada a página de derrota, com seu respectivo background e apenas o botão para voltar para a tela inicial.
Ao matar todos os inimigos, deverá ser mostrada a página de vitória, com a sua pontuação sendo mostrada na tela, além dela ser atualizada na página de pontuação. Além disso, deve ser mostrado o botão para a página inicial e o seu background.

<h1>Bugs conhecidos:</h1>
Sempre é colocado personagens a mais na tela, pois o MindAR some com alguns personagens aleatórios do array.
Por vezes, o cursor não aparece na tela, é só recarregar a tela para consertar o problema.
Às vezes, aparece uma barra branca do lado da tela quando inicia o jogo em si, é só recarregar a tela para consertar o problema; 


<h1>Requisitos funcionais:</h1>
Em cada página deverá ter cada um dos itens pertinentes a ela, a seguir serão mostrados esses itens.

<h2>Página inicial</h2>
<p align="center">
  <li>Nome do jogo: “You’re Dead”</li>
  <li>Background</li>
  <li>Botão para ver a pontuação</li>
  <li>Botão para começar a jogar</li>
  <br>
  <img src="https://github.com/AnaLuizaElert/Find-bugs/assets/107824361/d997d0a3-4200-4b81-bdda-45728b7b1409" height="300px">
</p>

<h2>Página de pontos</h2>
<p align="center">
  <li>Botão de voltar para a tela inicial</li>
  <li>Título: “Pontuacao”</li>
  <li>Quatro cards de pontuação de cada nível: “Impossible - Ouros”, “Hard - Espadas”, “Medium - Paus”, “Easy - Copas”</li>
  <br>
  <img src="https://github.com/AnaLuizaElert/Find-bugs/assets/107824361/15aac619-ed6c-4962-b84f-7b102fcabf13" height="300px">
</p>

<h2>Página do scanner</h2>
<p align="center">
  <li>Legenda: “Escaneie o nivel que deseja jogar”</li>
  <li>Scanner de nível</li>
  <li>Background da câmera</li>
  <br>
  <img src="https://github.com/AnaLuizaElert/Find-bugs/assets/107824361/493e2c87-62b8-461c-bcf4-23e4f49b1318" height="300px">
</p>

<h2>Página das informações do nível</h2>
<p align="center">
  <li>Carta do nível</li>
  <li>Símbolo do nível</li>
  <li>Nome do nível</li>
  <li>Quantidade de inimigos para matar</li>
  <li>Tempo de duração</li>
  <li>Descrição do nível</li>
  <li>Botão de voltar para a página do scanner</li>
  <li>Botão de jogar</li>
  <br>
  <img src="https://github.com/AnaLuizaElert/Find-bugs/assets/107824361/5511af18-9ae8-47c0-9c29-a2844bf77995" height="300px">
  <img src="https://github.com/AnaLuizaElert/Find-bugs/assets/107824361/f10ad27e-2b8f-495c-a657-76b31bc75449" height="300px">
  <img src="https://github.com/AnaLuizaElert/Find-bugs/assets/107824361/73b71e01-4728-4868-b8f1-27ae4e492d52" height="300px">
  <img src="https://github.com/AnaLuizaElert/Find-bugs/assets/107824361/a337a816-2c91-48ba-aaec-af97da4569dc" height="300px">
</p>


<h2>Página do jogo</h2>
<p align="center">
  <li>Contagem regressiva do tempo do jogo</li>
  <li>Contagem de inimigos mortos em relação a quantidade geral de inimigos no nível</li>
  <li>Três corações (vidas), que somem conformes a quantidade de amigos mortos</li>
  <li>Cursor roxo</li>
  <li>Inimigos e amigos espalhados pela tela</li>
  <br>
  <img src="https://github.com/AnaLuizaElert/Find-bugs/assets/107824361/79078345-9ba5-4ef0-8855-e3794a7541eb" height="300px">
</p>


<h2>Página de derrota</h2>
<p align="center">
  <li>Background</li>
  <li>Título: “Game Over”</li>
  <li>Botão para voltar para a tela inicial</li>
  <br>
  <img src="https://github.com/AnaLuizaElert/Find-bugs/assets/107824361/e7210988-2907-44b3-b789-2c6308565912" height="300px">
</p>

<h2>Página de vitória</h2>
<p align="center">
  <li>Botão para voltar para a tela inicial</li>
  <li>Texto: "Parabens! Voce ganhou!!”</li>
  <li>Pontuação adquirida na partida</li>
  <li>Background</li>
  <br>
  <img src="https://github.com/AnaLuizaElert/Find-bugs/assets/107824361/60bb26ea-8008-49e1-a276-2cec75b059a2" height="300px">
</p>
