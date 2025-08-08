
# Projeto: Jogo Secreto

## Descrição

O **Jogo Secreto** é um simples jogo de adivinhação em que o jogador tenta descobrir um número secreto aleatório entre 1 e 10. O jogo conta com feedbacks dinâmicos e um contador de tentativas. O número secreto é gerado aleatoriamente a cada nova partida e o jogador é informado se o número escolhido é maior ou menor do que o número secreto.

O jogo também usa a **ResponsiveVoice API** para fazer o texto ser falado, proporcionando uma experiência mais interativa.

## Funcionalidades

- O jogador escolhe um número entre 1 e 10.
- O sistema gera um número secreto aleatório.
- O jogador recebe feedback sobre o chute, informando se o número é maior ou menor que o secreto.
- O jogo conta o número de tentativas até o acerto.
- O jogador pode reiniciar o jogo ao acertar o número.

## Tecnologias Usadas

- **HTML**: Estrutura básica do jogo.
- **CSS**: Estilização do jogo e layout.
- **JavaScript**: Lógica do jogo, geração de números aleatórios e manipulação do DOM.
- **ResponsiveVoice API**: Utilizada para vocalizar as mensagens exibidas no jogo.

## Como Rodar o Projeto Localmente

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/projeto-jogo-secreto.git
```

### 2. Navegue até o diretório do projeto

```bash
cd projeto-jogo-secreto
```

### 3. Abra o arquivo `index.html` no seu navegador

Basta abrir o arquivo `index.html` diretamente no seu navegador para começar a jogar.

## Estrutura de Arquivos

```
projeto-jogo-secreto/
├── index.html        # Arquivo principal HTML
├── style.css         # Arquivo de estilos
├── app.js            # Lógica do jogo em JavaScript
└── img/              # Pasta com imagens do jogo

## Como Funciona o Jogo

- O número secreto é gerado aleatoriamente dentro do intervalo de 1 a 10.
- O jogador deve digitar um número no campo de entrada e clicar no botão "Chutar".
- Caso o número esteja correto, o jogo exibe uma mensagem de sucesso e o número de tentativas.
- Caso o número esteja incorreto, o jogo fornece dicas: "O número secreto é maior" ou "O número secreto é menor".
- O jogador pode reiniciar o jogo clicando no botão "Novo Jogo".

## Curso de Formação

Este projeto foi desenvolvido como parte de um **curso de formação em introdução à linguagem de programação da Alura com a Oracle Next Education*. Através deste curso, foi possível aprender os conceitos fundamentais de programação, como estruturas condicionais, loops, manipulação de DOM com JavaScript, além de aplicar práticas essenciais como controle de versão com Git e desenvolvimento de projetos web simples.
