# Arquitetura de Computadores


**Arquitetura de computadores** refere-se aos atributos de um sistema visíveis a um programador, ou em outras palavras, aqueles atributos que possui _impacto direto sobre a execução lógica de um programa_.

- Todo e qualquer programa tem que ser carregado na memoria para ser executado

- Faz parte tanto componentes de software quanto de hardware.

**Organização de computadores** refere-se às unidades operacionais e suas interconexões que realizam as especificações arquiteturais. Logo, uma organização de computadores precisa ser projetada para implementar determinada especificação arquitetural.

- Está relacionada a forma pela qual as coisas serão implementadas


**Função** refere-se a operação individual de cada componente como parta da estrutura. As funções que um computador pode realizar são:

- Aparato de movimentação de dados
- Mecanismo de controle
- Capacidade de armazenamento de dados
- Capacidade de processamento de dados

**Estrutura** refere-se ao modo como os componentes são inter-relacionados. Na estrutura de um computador existem 4 componentes principais que são:

- CPU
  - Registradores
  - ALU
  - Interconexão da CPU
  - Unidade de controle

- Entrada e saída
- Barramento do sistema
- Memoria

## Arquitetura de Von Neumann

É uma arquitetura de computador que se caracteriza pela possibilidade de armazenar programas (instruções/endereços) e dados no mesmo espaço de memória.

Características:

- **Barramento compartilhado** entre dados e endereços
- Baixo custo
- Desempenho limitado (gargalo de von neumann)

Funcionamento:

- Memória armazena dados e instruções
- CPU encarregada de buscar instruções e dados, decodificar e executar as instruções. Por fim, o resultado será armazenado na memória.


## Arquitetura de Harvard

- É uma arquitetura de computador que se distingue das outras por possuir duas memórias diferentes e independência em termos de barramento e ligação ao processador

Características:

- Separação de barramento de dados e endereços de instruções
- Aumento de custo
- Desempenho mais otimizado (permite que o processador possa acessar simultaneamente dados e instruções)

Funcionamento:

- Surgiu da necessidade de se obter uma arquitetura que pudesse trabalhar mais rapidamente
- A CPU pode ler uma instrução e executar um acesso de dado na memória ao mesmo tempo
