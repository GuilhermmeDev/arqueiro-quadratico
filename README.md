# 🏹 Arqueiro Quadrático 🏰

Um jogo arcade minimalista e baseado em física (cinemática de projéteis) onde o jogador deve encontrar a equação quadrática correta para acertar um alvo a partir de uma torre.

## 🎯 Objetivo do Jogo

O objetivo é acertar a maçã (alvo) ajustando os **coeficientes $A$ e $B$** da equação quadrática que define a trajetória da flecha.

A equação da trajetória é dada por:

$$y = Ax^2 + Bx + C$$

* **$C$ (Altura da Torre):** É a altura inicial da flecha, definida pela altura da torre (valor aleatório em cada rodada).
* **$A$ (Gravidade/Concavidade):** Controla a curvatura da parábola. Geralmente é um valor negativo para simular a gravidade.
* **$B$ (Velocidade/Ângulo Inicial):** Controla o ângulo e a velocidade de lançamento da flecha.

## 🕹️ Como Jogar

1.  **Ajuste os Coeficientes:** No painel de controle, use os campos de input para modificar os valores de **$A$** e **$B$**.
2.  **Linha de Simulação:** Uma linha **verde pontilhada** mostra a trajetória da flecha com base nos coeficientes inseridos.
3.  **Dispare:** Quando a linha de simulação estiver alinhada com o alvo, clique em **"DISPARAR!"**.

### Regras da Partida

* **Duração da Partida:** Quem atingir **3 pontos** primeiro vence o jogo.
* **Timer:** Você tem **15 segundos** por rodada para ajustar os coeficientes e disparar.

## 📊 Placar e Pontuação

O jogo utiliza um sistema de placar entre o **Jogador** e o **Inimigo (CPU)**:

| Ação do Jogador | Resultado | Placar |
| :--- | :--- | :--- |
| **Acertar o alvo** dentro do tempo. | **Ponto para o Jogador** | Jogador avança. |
| **Errar o alvo** (cair no chão, sair da tela). | **Ponto para o Inimigo** | Inimigo avança. |
| **Tempo esgotar** antes do disparo. | **Ponto para o Inimigo** | Inimigo avança. |

## 💻 Tecnologias Utilizadas

Este projeto foi construído puramente com tecnologias front-end para facilitar a execução em qualquer navegador, seguindo o estilo *Pixel Art* em Canvas.

* **HTML5:** Estrutura base e elementos de interface.
* **CSS3:** Estilização Pixel Art e telas de Menu/HUD.
* **JavaScript:** Toda a lógica de jogo, física da parábola, animação do projétil, timer e gestão de estados (`MENU`, `PLAYING`, `ENDED`).
* **HTML Canvas API:** Utilizado para desenhar o cenário (torre, arqueiro, alvo) e animar a trajetória da flecha.

## 🚀 Executando o Projeto

O projeto consiste em um único arquivo HTML.

1.  Clone o repositório para sua máquina local.
2.  Abra o arquivo `index.html` (ou o nome que você usou) diretamente no seu navegador.

---
Feito com 💚 e 📐.
