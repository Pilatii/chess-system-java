# Chess System Java

Implementação de um jogo de xadrez em Java, executado diretamente pelo terminal. O projeto explora conceitos de Programação Orientada a Objetos, estruturas de dados, encapsulamento e organização em camadas, utilizando as regras tradicionais do xadrez.

## Tecnologias

- **Java** – Linguagem principal.
- **OOP** – Aplicação de conceitos de Programação Orientada a Objetos.

## Funcionalidades

- **Movimentação de peças:** Implementação das regras de movimentação de cada peça.
- **Validação de jogadas:** Verificação de movimentos válidos e posições disponíveis.
- **Controle de turnos:** Alternância entre jogadores durante a partida.
- **Captura de peças:** Registro e exibição das peças capturadas.
- **Xeque e Xeque-mate:** Identificação de situações de ameaça ao rei e encerramento da partida.
- **Movimentos especiais:** Implementação de roque, en passant e promoção de peões.
- **Tratamento de exceções:** Validação de entradas e prevenção de operações inválidas.

## Conceitos aplicados

- Encapsulamento e abstração.
- Herança e polimorfismo.
- Classes abstratas e métodos sobrescritos.
- Enumerações.
- Tratamento de exceções.
- Matrizes e listas.
- Separação de responsabilidades e organização em camadas.

## Organização do projeto

| Pacote | Responsabilidade |
|---|---|
| `application/` | Inicialização e interação com o usuário. |
| `boardgame/` | Estrutura do tabuleiro, posições e peças genéricas. |
| `chess/` | Regras específicas do xadrez, partidas e movimentações. |

## Executando o projeto

**Pré-requisitos:**
- Java JDK 11 ou superior.

Clone o repositório:

```console
git clone https://github.com/Pilatii/chess-system-java.git
```

Entre no diretório:

```console
cd chess-system-java
```

Abra o projeto na sua IDE Java ou compile e execute utilizando a configuração de execução correspondente à estrutura do código.

## Objetivo

Projeto desenvolvido para praticar Programação Orientada a Objetos com Java, aplicando conceitos de modelagem de domínio, abstração, herança, polimorfismo e estruturas de dados na implementação de um jogo de xadrez.
