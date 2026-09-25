# ♟️ Sistema de Jogo de Xadrez em C# (Console)

Projeto desenvolvido como objeto de estudo durante o curso **"[C# COMPLETO Programação Orientada a Objetos + Projetos](https://www.udemy.com/course/programacao-orientada-a-objetos-csharp/)"** do Prof. Nelio Alves (Udemy).

## 🚀 Sobre o Projeto

Este sistema é um jogo de xadrez completo executado no terminal (console). O projeto foi construído passo a passo com o objetivo de aplicar na prática os pilares da Programação Orientada a Objetos (POO), a modelagem de domínio e a construção de soluções para problemas lógicos complexos.

## ⚙️ Funcionalidades e Regras de Negócio Implementadas

O jogo contempla as mecânicas tradicionais do xadrez, organizadas de forma modular:

* **Controle da Partida:** Sistema de turnos alternados entre peças brancas e pretas, com exibição do histórico de peças capturadas.
* **Validação de Movimentos:** Bloqueio de movimentos inválidos para cada peça específica, garantindo que o jogador escolha uma peça válida na origem e um destino permitido.
* **Estados de Jogo:** Lógica para detecção e alerta automático de **Xeque** e **Xequemate**.
* **Jogadas Especiais:**
  * **Roque:** Implementação das variações de Roque Pequeno e Roque Grande.
  * **En Passant:** Captura especial e complexa exclusiva dos peões.
  * **Promoção:** Transformação do peão em outra peça (como Rainha) ao atingir a extremidade oposta do tabuleiro.

## 🧠 Conceitos e Tecnologias Aplicadas

A construção deste sistema exigiu a aplicação de conceitos fundamentais da linguagem C# e da arquitetura de software:

* **Linguagem:** C# (.NET)
* **Programação Orientada a Objetos (POO):** Modelagem rigorosa utilizando classes, encapsulamento, herança, polimorfismo, sobrecarga e composição.
* **Estrutura de Dados:** Uso extensivo de matrizes bidimensionais para representar a malha do tabuleiro e organizar as posições.
* **Tratamento de Exceções:** Criação de classes de exceção personalizadas (`TabuleiroException`) para tratar violações das regras do jogo sem interromper a execução abruptamente.
* **Design de Software:** Separação de responsabilidades (Camada de Tabuleiro, Camada de Peças e Camada de Lógica da Partida).

## 💻 Como executar o projeto

1. Certifique-se de que tem o [.NET SDK](https://dotnet.microsoft.com/download) instalado no seu sistema.
2. Clone este repositório:

   ```bash
   git clone https://github.com/aguiar-vitor/Projeto-Sistema-de-jogo-de-xadrez.git