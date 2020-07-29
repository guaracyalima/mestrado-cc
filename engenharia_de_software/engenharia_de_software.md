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

## Modelos evolucionarios

- São modelos iterativos com caracteísticas que possibilitam desenvolver versões cada vez mais complexas do software
- Ex.: Prototipação, Espiral e Desenvolvimento concorrente

### Prototipação
- Auxilia o engenheio de software e o cliente a entederem melhor o que deve ser construido quando os requisitos estão confusos
- O prototipo serve como um mecanismo para a identificação dos requisitos de software

**Desvantagens**
- Os interessados enxergam o prototipo como um software operacional
- O engenheiro de software se compromete a colocar o software em produção rapidamente comprometendo a qualidade final do software

**Tipos de prototipos**
- **Prototipo exploratorio** , o qual é descartado quando fica pronto, tambem conhecido como prototipo para descarte
- **Prototipo evolutivo**, que gradualmente evolui para se tornar um sistema real

### Espiral

- Porposto por Boehm em 1988, combina a natureza iterativa da prototipagem com os aspectos controlados e sistematicos do modelo em cascata

- O software é desenvolvido numa serie de versões evolucionaria, as peimeiras iterações podem gerar modelos em papel ou prototipos

- Exige a consideração direta dos riscos técnicos em todos os estágios do projeto

- Pode ser adaptado para aplicação ao longo da vida do software

### Desenvolvimento concorrente

- É representado esquematicamente como uma série de atividades (levantamento de requisitos, análise, projeto, etc) e seus estados associados.

- Define uma série de eventos que vão disparar transições de estado para estado

- É aplicavel a todos os tipos de desenvolvimento de software e fornece uma imagem precisa do estado atual de um projeto

## Modelos especializados

- Desenvolvimento baseado em componentes
- Modelo de metodos formais .:
  - Baseados em modelos matematicos
  - Lento e dispendioso
  - Necessita treinamento extensivo
  - Cliente desesperados não entendem os modelos, dificultando a comunicação

- Desenvolvimento de software orientado a aspectos
  - Gestão de memória
  - Integridade
  - Segurança

## Desenvolvimento baseado em componentes

- Oferece beneficios inerentes em qualidade de software, produtividade dos desenvolvedores e custos globais do sistema

- É um processo que enfatiza o projeto e a construção de sistemas usando componentes de software reusaveis

- Semelhante ao modelo espiral

- Demanda uma abordagem iterativa

- Compõe aplicações a partir de componentes prontos

- As atividades de modelagem e construção começam com a identificação de componentes candidatos

- Os requisitos que não são atendidos pelos componentes são adaptados ou excluidos, quando possivel

## Engenharia dirigida a modelos - MDE

- É uma abordagem do desenvolvimento de software segundo a qual os modelos, em vez de programas, são as saidas principais do processo de desenvolvimento. Os programas são gerados automaticamente apartir dos modelos

- Aumenta o nivel de abstração na engenharia de software, e, dessa forma, os engenheiros não precisam mais se preocupar com detalhes da linguagem de programação ou com as especificidades das plataformas de execução

- Tem sua origem na arquitetura dirigida a modelos (MDA) proposta pela OMG em 2001, como um novo paragma de desenvolvimento de software

- MDA se concentra nos estágios de projeto e impelemtação
- MDE abrange todo o ciclo de desenvolvimento de software

**Vantagens**

- Permite que os engenheiros pensem em sistemas de alto nível de abstração, sem detalhes de implementação diminuindo a probabilidade de erros, acelerando o processo de projeto e implementação e permite a criação de modelos aplicaveis e reusáveis, indendentemente de plataformas

**Desvantagens**

- As abstrações apoiadas pelo modelo nem sempre são corretas para a implementação

- Independencia de plataforma são validas apenas para sistemas de grande porte e duradouros, em que as plataformas se tornam obsoletas ao longo do tempo de vida do sistema

## Arquitetura dirigida a modelos - MDA

Três modelos:

- Modelo de computação independente (CIM): modela as importante abstrações do domínio usado no sistema. Podem ser chamados de _modelos de domínio_

- Modelo independente de plataforma (PIM): modelo a operação do sistema sem referencia a sua implementação. O PIM geralmente é descrito por meio de modelos UML

- Modelo especifico de plataforma (PSM): são as transformações do PIM com um PSM separado para cada plataforma de aplicação
