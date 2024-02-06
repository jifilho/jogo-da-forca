# Jogo da Forca

Este é um jogo da forca simples em Python que pode ser jogado em dupla. Um jogador digita uma palavra e o outro tenta adivinhar qual é essa palavra.

## Como Jogar

1. O programa solicitará que um jogador digite uma palavra para ser adivinhada. A palavra deve ter no mínimo 3 caracteres.
2. Uma vez que a palavra é escolhida, o jogo começa.
3. O jogador que tenta adivinhar a palavra digitará uma letra por vez.
4. Se a letra estiver na palavra escolhida, ela será revelada na posição correta. Caso contrário, uma parte do boneco será desenhada, indicando que uma tentativa foi perdida.
5. O jogo continua até que o jogador adivinhe a palavra ou o boneco seja completamente desenhado, indicando que todas as tentativas foram esgotadas.

## Interface Gráfica

O jogo possui uma interface gráfica simples em ASCII, mostrando o estado atual da forca e as letras adivinhadas até o momento.

## Atualizações

**24/01:**
- Adicionada validação para evitar que o jogador digite mais de uma letra por vez.
- Reduzidas redundâncias no código.
- Corrigido erro que exibia "Letra não encontrada. Tente novamente" mesmo quando não havia tentativas restantes.
- Adicionada interface gráfica em ASCII para tornar o jogo mais visualmente atraente.
- Criptografada a palavra escolhida usando a biblioteca `getpass`.
- Implementada verificação para garantir que a palavra tenha pelo menos 3 letras.

**26/01:**
- A lista de palavras criptografadas agora é exibida no início do jogo.
- Adicionada validação para impedir que o jogador repita uma letra já tentada anteriormente.

**29/01:**
- Criada função para reiniciar o jogo.
- O código principal foi encapsulado em uma função e um loop `while` foi adicionado no final para permitir múltiplos jogos.
