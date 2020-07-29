# Engenharia de software

## Modelos de processos de software
- Modelo sequencial linear
- Modelos incrementais
- Modelos evolucionarios
- Modelos especializados
- Engenharia dirigida a modelos
- RUP

### Modelo sequencial linear

**Modeo em cascata - classico**

- Levantamento de requisitos (comunicação): tem por objetivo propiciar que usuario e desenvolvedores tenham a mesma compreensão do proble a a ser resolvido

- Analise (planejamento): Tem por objetivo consturi modelos que determinam qual é o prlbema para o qual estamos tentando conceber uma solução de software

- Projeto (): Estagio no qual o modelo de analise terá de ser adaptado de tal modo que o possa servir coo base para implementação no ambiente alvo.

- Codificação (implementação): a codificação do sistema é efetivamente executada

- Teste: consiste na verificação do software

- Implantação: entrada em produção

Problemas
- Projetos raramente seguem fluxos sequenciais
- Mudança de requisitos podem causar confusões
- É dificil para o cliente estabelecer todas as necessidades no inicio do Projeto
- Uma versão do software só estará disponivel proximo ao fim do projeto
- Dificulta o gerenciamento de riscos

Pode ser utilizado quando os requisitos são bem conhecidos e razoavelmente estaveis


### Modelo V

É uma variação do modelo cascata. Este modelo descreve o paralelismo entre as atividades de desenvolvimento e teste de softare


## Modelos incrementais

- Aplica sequenciais lineares, de forma iterativa, à medida que o tempo avança. Cada sequencia linear (cascata) gera _incrementos_  entregaveis do software. Seu foco consiste na entrega de um produto operacional a cada incrementeo

**Vantagens:**
- Custo de acomodar mudanças de requisitos é reduzido
- Facilita o feedback do cliente
- Todo incremento gera uma entrega

**Desvantagens**
- Processo não visivel
- A estrutura do sistema tende a degradar com a adição de novos incrementos (rexige refatoração)

## Modelo RAD (Rapid Application Development)

- É um modelo de processo de software incremental que enfatiza um ciclo de desenvolvimento curto
- É uma adaptação de _alta velocidade_ do modelo em cascata, no qual o desenvolvimento rapido é conseguido com o uso de uma abordagem de construção baseada em compoentes

**Desvantagens**
- Projetos grandes precisam de muitas equipes
- Exige comprometimento dos clientes ce desenvolvedores
- Sistemas não modularizados são problematicos
- Não é adequado para projetos com grandes riscos tecnicos
