# Jogo da Forca em C

Este projeto é uma implementação do clássico jogo da forca em C. O objetivo do jogo é adivinhar uma palavra oculta antes de ficar sem tentativas.

## Funcionalidades

- **Escolha de palavras:** O jogo lê uma palavra aleatória de um arquivo de texto.
- **Tentativas e erros:** O jogador tem um número limitado de erros antes de perder.
- **Desenho da forca:** O jogo desenha a forca e mostra a palavra com letras adivinhadas e lacunas.
- **Adição de palavras:** Permite adicionar novas palavras ao banco de dados do jogo.

## Pré-requisitos

- GCC (ou outro compilador C)
- Arquivo `palavras.txt` contendo a lista de palavras
- Arquivo de cabeçalho `forca.h`

## Compilar o jogo

Para compilar o jogo, execute o comando:

```bash
gcc -o forca forca.c
```
## Executar o jogo

Após compilar o jogo, execute-o com:
```bash
./forca
```
