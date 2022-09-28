# Jogo pong em JS

*Projeto realizado através do curso Lógica de programação: comece em lógica com o jogo Pong e Javascript pela, plataforma de cursos [Alura](https://www.alura.com.br/ "Alura")

Usado biblioteca e editor [p5.js](https://p5js.org/ "p5.js") 

 Clicando [AQUI](https://editor.p5js.org/elieljrdl1/full/M5hkODn-e  "AQUI") o projeto finalizado
 
Clicando [AQUI ](https://editor.p5js.org/elieljrdl1/sketches/M5hkODn-e "AQUI ")o código fonte no editor p5

## Jogando multiplayer
Para jogar multiplayer, será necessário  substituir o conteúdo dentro da     `function movimentaRaqueteOponente()` 
    Segue abaixo:
    
    `function movimentaRaqueteOponente(){
      if (keyIsDown(87)){
        yRaqueteOponente -= 10;
      }
      if (keyIsDown(83)){
        yRaqueteOponente += 10;
      }
    }`
    
Apertando a tecla "w" move a raquete do oponente para cima e "s" para baixo.

