﻿## Temporary help, delete once is done
# Projeto 1 cheat sheet

### Composição do programa

#### Link para [Diagrama]:https://drive.google.com/file/d/1dL46pckbe5K2Tr9PMW4zzPoOEJy25Hhi/view?usp=sharing

- Enumeração para os estados possíveis de 1 célula.

- Class de posição com propriedades Coluna e Linha para guardar 
	a posição de cada célula

- Class Board para guardar a parte central do jogo, tabuleiro, em que contem
	a matriz do tabuleiro de valores ESTADO (enumeracao), 
	funcoes de pedir estado, mudar estados de células e uma forma de keep track
	do turno em que se está.

- Class Player que controla os inputs feitos pelos jogadores 
	(maybe arranjar forma de o fazer com rato?) 
	ex: public Position GetPosition(Board currentState)

- Class WinChecker, isto é uma class unicamente para verificar o estado do jogo
	através do tabuleiro, funcao para ver se alguem ganhou, e uma para ver se
	há algum empate.
	ex: public StateCheck(Board currentState)
	public bool DrawCheck(Board currentState)

- Class Renderer para desenhar o estado do jogo, tabuleiro, e quem ganha
	a partir do tabuleiro.
