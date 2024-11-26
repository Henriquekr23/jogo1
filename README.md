## **Funcionalidades**

- Escolha entre quatro níveis de dificuldade:
  1. Fácil
  2. Médio
  3. Difícil
  4. Insano

- Operações matemáticas disponíveis:
  - Soma
  - Subtração
  - Multiplicação
  - Divisão

- Sistema de pontuação:
  - Resposta correta: +10 pontos
  - Resposta errada: -10 pontos

- Possibilidade de jogar várias rodadas ou encerrar o jogo a qualquer momento.

---

## **Pré-requisitos**

- Um compilador C instalado, como `gcc`.
- Ambiente para executar o programa, como um terminal ou IDE compatível com C.

---

## **Regras do Jogo**

1. O jogador escolhe um nível de dificuldade:
   - Fácil: Números de 0 a 9
   - Médio: Números de 0 a 99
   - Difícil: Números de 0 a 999
   - Insano: Números de 0 a 9999

2. Um problema matemático aleatório será gerado com base no nível escolhido.
3. O jogador deve inserir o resultado da operação.
4. Pontos serão atribuídos com base na resposta:
   - Resposta correta: +10 pontos
   - Resposta errada: -10 pontos

5. O jogo continua até o jogador optar por sair.

---

## **Estrutura do Código**

### **Principais Funções**

- **Funções matemáticas**
  - `soma`: Realiza a soma de dois valores.
  - `subtracao`: Realiza a subtração de dois valores.
  - `multiplicacao`: Realiza a multiplicação de dois valores.
  - `divisao`: Realiza a divisão de dois valores, com validação para divisão por zero.

- **Funções do jogo**
  - `calcular`: Verifica a resposta do usuário e ajusta a pontuação.
  - `aleatoriedade`: Gera uma operação aleatória e solicita a resposta ao jogador.
  - `jogar`: Controla o fluxo principal do jogo, incluindo seleção de dificuldade e controle de rodadas.

---
