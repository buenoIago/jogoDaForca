# Jogo da Forca

![Demonstração aplicativo](WindowsTerminal_shx1M0XdLZ.gif)

## Projeto

Desenvolvido durante o curso Fullstack da [Academia do Programador](https://www.academiadoprogramador.net) 2026

## Introdução

O sistema selecionará, de forma aleatória, um termo entre diversas opções*, e o participante deverá tentar adivinhá-lo inserindo uma letra por vez.

Os jogadores devem digitar uma única letra no console a cada tentativa. Caso a letra exista na palavra, ela será exibida nas posições corretas. Se a letra não fizer parte da palavra, um elemento do desenho da forca será acrescentado.

Se o jogador errar mais de 5 tentativas, ele será derrotado.

## Funcionalidades

- **Escolha de Palavra Secreta**: Um termo é definido de maneira aleatória no começo de cada partida.
- **Representação da Forca**: O desenho da forca vai sendo montado gradualmente no console a cada erro cometido pelo participante.
- **Feedback Visual**: As letras acertadas aparecem em suas posições corretas, enquanto as ainda não identificadas continuam escondidas.
- **Contagem de Erros**: O sistema registra a quantidade de erros do jogador e encerra a partida quando o limite máximo é atingido.

## Como utilizar o programa

1. Clone o repositório ou baixe o código comprimido em .zip.
2. Abra o emulador de terminal e navegue até a pasta raiz.
3. Utilize o comando abaixo para restaurar as dependências do projeto.

   ```
   dotnet restore
   ```

4. Em seguida compile e execute o projeto com o comando:

   ```
   dotnet run --project jogoDaForca.ConsoleApp
   ```

## Requisitos

- .NET SDK 10.0