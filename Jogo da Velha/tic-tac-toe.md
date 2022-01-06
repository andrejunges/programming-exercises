# JOGO DA VELHA

O jogo da velha, ou tic tac toe, é um jogo para duas pessoas no qual o objetivo é formar uma linha com três elementos da mesma forma, podendo ser na vertical, horizontal ou na diagonal.

Regras: https://www.tibiawiki.com.br/Tic_Tac_Toe

O desafio consiste na implementação de um jogo da velha 3x3. Os requisitos constam a seguir.


### Requisitos

Escreva uma classe chamada `JogoDaVelha` que possua os seguintes métodos:
`Jogar(int x, int y): void`
Receberá uma posição (x, y) e deve inserir a forma da vez na posição. O jogo deve começar com “X”. Caso a posição já esteja ocupada, o método deve disparar uma `InvalidOperationException`. Caso a posição seja inválida, o método deve disparar uma `ArgumentOutOfRangeException`.

`ObterVencedor(): string`
Retornará o vencedor do jogo, podendo ser: `O`, `X` e `null` (sem vencedor).
Este método pode ser chamado a qualquer momento do jogo.

A implementação de uma interface gráfica é opcional.

Pode ser utilizada qualquer linguagem, framework e plataforma.

É importante respeitar a assinatura dos métodos mencionados acima para que seja possível rodar os testes automatizados.
