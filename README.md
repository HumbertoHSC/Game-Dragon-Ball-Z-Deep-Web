# Dragon Ball-Z Deep Web

- Desenvolvemos esta aplicação como parte do projeto final da disciplina de Introdução a Programação.

# Sobre o Jogo:

- O enredo se desenrola no planeta Terra após a chegada de Freeza e Majin Boo, determinados a se vingar de Goku por derrotas passadas. Seu objetivo é eliminar Goku e, em seguida, destruir o planeta. Goku assume a missão de derrotar esses inimigos formidáveis e proteger o planeta da iminente ameaça que representam.

- O jogador, no papel de Goku, deve impedir que os inimigos, representados por Freeza e Majin Boo, passem por ele. Se algum inimigo conseguir chegar ao final da tela, o jogador perderá uma vida, das 7 disponíveis. No entanto, é possível recuperar vidas coletando as Esferas do Dragão espalhadas pelo jogo.


# Como iniciar o jogo:

- Baixe os arquivos do repositório, Abra a IDE (VScode ou Pycharm) com a biblioteca do Pygames instalada, abra a pasta onde salvou os arquivos baixados anteriormente com a IDE, inicie o arquivo “.Py” da pasta e aperte “Run”. 

# Organização do Código:

- Class Game: Classe principal onde cria o Loop do jogo e chama todas as funções necessárias para o funcionamento do código. 

- Class Player: Cria a imagem do Jogador no jogo, adiciona função a de colisão do Jogador com outras instâncias do jogo, função de movimentação.

- Class Inimigo: Cria a imagem do inimigo no jogo, adiciona função a de colisão do inimigo com outras instâncias do jogo, função de respawn e movimentação, função de vida do jogador.

- Class Tiro: Cria imagem do tiro na mão do jogador, função de colisão com inimigo, função de respawn, e contagem de pontos.

- Class Esfera: Cria imagem de esfera do dragão na tela, a ocorrência dela após algumas condições, spawn das esferas e adição de vida.


