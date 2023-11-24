# Chess System Java ♟ 
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/samuelmsilva2v/chess-system-java/blob/main/LICENSE) 

Projeto de um sistema de Jogo de Xadrez desenvolvido em Java durante o [curso de Java do Prof. Nélio Alves](https://www.udemy.com/course/java-curso-completo/). 
O projeto incorpora um modelo de domínio bem definido e uma estrutura de camadas lógicas.

## Modelo conceitual
![concept-model](https://github.com/acenelio/chess-system-design/blob/master/chess-system-design.png?raw=true)

## Como executar o projeto:

```bash
# clonar repositório
git clone git@github.com:samuelmsilva2v/chess-system-java.git

# entrar na pasta do projeto
cd chess-system-java
cd bin

# executar o projeto
java application/Program
```

## Funcionalidades
1️⃣ Representação do tabuleiro: O tabuleiro de xadrez é representado como uma matriz de dados adequada para facilitar a manipulação das peças e suas posições.

2️⃣ Peças de xadrez: Cada tipo de peça (rei, rainha, bispo, cavalo, torre e peão) são representados por uma classe que define suas características e movimentos legais.

3️⃣ Regras de movimento: Implementação das regras de movimento específicas de cada peça de xadrez. Por exemplo, o movimento em L do cavalo, a diagonal do bispo e a reta da torre.

4️⃣ Validação de jogadas: Verifica se as jogadas feitas pelos jogadores são válidas de acordo com as regras do xadrez.

5️⃣ Controle de turnos: Alterna entre os jogadores e garante que apenas o jogador correto possa fazer uma jogada em um determinado momento.

6️⃣ Detecção de xeque e xeque-mate: Verifica se o rei de um jogador está em xeque ou em xeque-mate após cada jogada.

7️⃣ Movimentos especiais: Movimentos especiais como roque, en passant, promoção de peão e empate por repetição de movimentos.

8️⃣ Interface do usuário: Criada uma interface gráfica para que os jogadores possam interagir com o tabuleiro, realizar jogadas e receber feedback sobre o estado do jogo.

# Autor

Samuel Maciel da Silva

www.linkedin.com/in/samuelmsilva2v
