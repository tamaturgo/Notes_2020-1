# Processos

# Por que Engenharia de Software?

- Análise /versus/ síntese de um problema
- Método ou técnica: procedimento para a produção de um resultado
- Ferramenta: instrumento ou sistema automatizado para realizar alguma coisa
- Procedimento: receita de combinação de ferramentas e técnicas
- Paradigma: estilo de fazer algo

# Qualidade

## Terminologias

- Erro: erro humano
- Defeito: resultado do erro evidenciado em algum desenvolvimento ou manutenção do produto
- Falha: divergência entre o comportamento requerido para o sistema e o comportamento real

## Perspectivas de Garvin sobre qualidade

- Visão transcedental: algo que podemos reconhecer, mas não definir
- Visão do usuário: conveniência para propósito retendido
- Visão do fabricante: conformidade com especificaçao
- Visão do produto: relação com as características inerentes ao produto
- Visão do mercado: dependência de quanto os consumidores estão dispostos a pagar

# Abordagem de sistemas

- Identificar atividades e objetos
- Definir as relações e fronteiras do sistema
- Considerar sistemas inter-relacionados

# Construindo uma _casa_ _versus_ um _software_

## Casa

- Identificar e analisar os requisistos
- Produzir e documentar todo o projeto
- Detalhar as especificações
- Identificar e projetar os componentes
- Construir cada componente
- Testar cada componente
- Integrar os componentes
- Fazer as modificações finais
- Manutenção contínua

## Software

- Análise e definição de requisitos
- Projeto do sistema
- Projeto do programa
- Escrever os programas
- Testes das unidades
- Teste de integração
- Teste do sistema
- Entrega do sistema
- Manutenção

# Fatores-chave que mudaram a prática da engenharia de software

- Aspecto crítico do tempo para entrega do produto ao mercado, no caso de produtos comerciais
- Mudanças na economia da computação (redução dos custos de hardware e aumento nos custos de desenvolvimento e manutenção)
- Disponibilidade poderosa da computação em desktops
- Aumento das redes locais e remotas
- Disponibilidade e adoção da tecnologia orientada a objetos
- Uso de interfaces gráficas
- Imprevisibilidade do modelo de desenvolvimento de software cascata

# Disciplina de engenharia de software de Wasserman

- Abstração
- Métodos e notações de análise e projeto
- Protótipo da interface com o usuário
- Arquitetura de software
- Processo de software
- Reúso
- Medição
- Ferramentas e ambientes integrados

# Exemplos de sistema de informação

- Piccadily Television: TV regional britânica
- Anunciante comercial tem diversas alternativas
  - Propagandas de bebidas alcoólicas só podem ser apresentadas das 21 horas
  - Se um atore está em um programa, então um anúncio com o mesmo ator não pode ser transmitido antes de 45 minutos após o término do programa
  - Se um anúncio para a classe de produtos está programado para um dado intervalo comercial, então nenhum outro anúncio para outro produto dessa mesma classe pode ser apresentado nesse intervalo

# Processo de software

- Modelos de processo de software
- Atividades de processo
- Lidando com mudanças
- Rational Unified Process (RUP)
- Um exemplo de um processo de desenvolvimento de software moderno

## O processo de software

- Um conjunto estruturado de atividades necessárias para desenvolver um sistema de software
- Existem vários processos de desenvolvimento de software diferentes, mas todos envolvem:
  - Especificação: definição do quê o sistema deve fazer
  - Projeto e implementação: definição da organização do sistema e implementação do sistema
  - Validação: checagem de que o sistema faz o que o cliente deseja
  - Evolução: evolução em resposta a mudanças nas necessidades do cliente
- Um modelo de processo de desenvolvimento de software é uma representação abstrata de um processo. Ele apresenta uma descrição do processo de uma perspectiva em particular

## Descrições de processo de software

- Quando descrevemos e discutimos processos, geralmente falamos sobre as atividades desses processos, tais como especificação de modelo de dados, desenvolvimento de interface de usuário, etc e organização dessas atividades
- Descrições de processos também podem incluir:
  - Produtos, que são os resultados de uma atividade do processo
  - Papéis, que refletem as responsabilidades das pessoas envolvidas no processo
  - Pré e pós-condições, que são declarações que são verdadeiras antes e depois de uma atividade do processo ser executado, ou um produto produzido

# Processos dirigidos a planos e ágeis

- Processos dirigidos a planos são processos em que todas as atividades do processo são planejadas com antecedência e o progresso é medido em relação a esse plano
- Nos processos ágeis o planejamento é incremental e é mais fácil modificar o processo para refletir alterações nos requisitos do cliente
- Na realidade, os processos mais práticos incluem elementos dos processos ágeis e dirigidos a planos
- Não existe processo de software certo ou errado

# Modelos de processo de software

## Modelo Cascata

Modelo dirigido a planos, Fases de especificação e desenvolvimento separadas e distintas.

### Fases do modelo cascata

- Existem fases identificadas e separadas no modelo cascata:
  - Análise e definição de requisitos
  - Projeto de sistema e software
  - Implementação e teste de unidade
  - Integração e teste de sistema
  - Operação e manutenção
- O principal inconveniente do modelo cascata é a dificuldade de acomodação de mudanças depois que o processo já foi iniciado. Em princípio, uma fase precisa ser completada antes de se mover para a próxima fase.

### Problemas do modelo cascata

- Divisão inflexível do projeto em estágios distintos, torna difícil responder às mudanças nos requisitos do cliente
  - Por isso, esse modelo só é apropriado quando os requisitos são bem entendidos e as mudanças durante o processo de projeto serão limitadas
  - Poucos sistemas de negócio possuem requisitos estáveis
- O modelo cascata é mais usado em projetos de engenharia de grandes sistemas onde o sistema é desenvolvido em vários locais.
  - Nessas circunstâncias, a natureza do modelo cascata dirigida a plano ajuda a coordenar o trabalho

## Desenvolvimento Incremental.

Especificação, desenvolvimento e validação são intercaladas. Pode ser dirigido a planos ou ágil.

### Benefícios do desenvolvimento incremental

1. O custo para acomodar mudanças nos requisitos do cliente é reduzido
   - A quantidade de análise e documentação que precisa ser feita é bem menor do que a necessária no modelo cascata
2. É mais fácil obter feedback do cliente sobre o trabalho de desenvolvimento que tem sido feito
   - Os clientes podem comentar demonstrações do software e ver quanto foi implementado
3. Possibilidade de mais rapidez na entrega e implantação de software útil para o cliente
   - Os clientes podem usar e obter ganhos do software mais cedo do que é possível no processo cascata

### Problemas do desenvolvimento incremental

- O processo não é visível
  - Gerentes precisam de entregar regulares para medir o progresso. Se os sistemas são desenvolvidos de forma rápida, não é viável do ponto de vista do custo produzir documentação para refletir todas as versões do sistema
- A estrutura do sistema tende a degradar conforme novos incrementos são adicionados
  - A menos que tempo e dinheiro sejam gastos na reconstrução para melhorar o software, as mudanças regulares tendem a corromper a estrutura do sistema. A incorporação posterior de mudanças no software se torna progressivamente mais difícil e cara

## Engenharia de software orientada a reúso

O sistema é montado a partir de componentes já existentes. Pode ser dirigido a planos ou ágil.

> OBS
> A maioria dos grandes sistemas são desenvolvidos usando um processo que incorpora elementos de todos esses modelos.

- Baseada no reúso sistemático em que os sistemas são integrados com componentes existentes ou sistemas COTS(Commercial-off-the-shell)
- Estágios do processos:
  - Análise de componentes
  - Modificação de requisitos
  - Projeto de sistema com reúso
  - Desenvolvimento e integração
- Atualmente, o reúso é a abordagem padrão para a construção de vários tipos de sistemas de negócio

# Tipos de componente de software

- Web services que são desenvolvidos de acordo com padrões de serviço e ficam disponíveis para chamada remota
- Coleções de objetos que são desenvolvidas como um pacote para ser integrado com um framework, como .NET ou J2EE
- Sistemas de software stand-alone (COTS) que são configurados para uso em ambientes específicos

# Atividades do processo

- Processos de software reais são sequências intercaladas de atividades técnicas, colaborativas e gerenciais com o objetivo geral de especificar, projetar, implementar e testar um sistema de software
- As quaro atividades de processo básicas (especificação, desenvolvimento, validação e evolução) são organizadas de forma diferente em processos de desenvolvimento distintos
- No modelo cascata, elas são organizadas em sequências, enquanto no desenvolvimento incremental são intercaladas

## Especificações de software

- O processo de estabelecer quais serviços são necessários e as restrições na operação e desenvolvimento do sistema
- O processos de engenharia de requisitos
  - Estudo da viabilidade: É técnica e financeiramente viável construir o sistema?
  - Elicitação e análise de requisitos: O que os stakeholders do sistema precisam ou esperam do sistema?
  - Especificação de requisitos: Definição dos requisitos em detalhes
  - Validação dos requisitos: Verificação da completude dos requisitos

## Projeto e implementação de software

- Processo de converter a especificação de sistema em um sistema executável
- Projeto de software
  - Design de uma estrutura de software que materialize a especificação
- Implementação
  - Transformar essa estrutura em um programa executável
- As atividades de projeto e implementação são intimamente ligadas e podem ser intercaladas

## Atividades de projeto

- Projeto de arquitetura, em que você identifica a estrutura geral do sistema, os componentes principais (as vezes chamados sub-sistemas ou módulos), seus relacionamentos e como são distribuídos
- Projeto de interface, em que você define as interfaces entre os componentes do sistema
- Projeto de componente, em que você projeta como cada componente do sistema irá operar separadamente
- Projeto de banco de dados, em que você projeta as estruturas de dados do sistema e como essas serão representadas no banco de dados

## Validação de software

- Verificação e validação (V & V) serve para mostrar que o sistema está em conformidade com sua especificação e está de acordo com os requisitos do cliente
- Envolve processos de inspeção e revisão, e testes do sistema
- Testes do sistema envolvem executar o sistema com casos de teste. São provenientes de especificações dos dados reais que deverão ser processados pelo sistema
- O teste é a atividade de V & V mais usada

## Estágios de teste

### Teste de desenvolvimento ou de componente

- Componentes individuais são testados independentemente
- Componentes podem ser funções ou objetos, ou agrupamentos coerentes dessas entidades

### Teste de sistema

- Teste do sistema como um todo. Teste de propriedades emergentes são particularmente importantes

### Teste de aceitação

- Teste com dados do cliente para checar se o sistema está de acordo com as necessidades do cliente

# Evolução de software

- Os softwares são inerentemente flexíveis e podem mudar
- Conforme os requisitos mudam, conforme mudam as circunstâncias do negócio, o software que dá suporte ao negócio também deve evoluir e mudar
- Apesar de ter acontecido uma demarcação entre desenvolvimento e evolução (manutenção) essa precisa se tornar cada vez mais irrelevante já que tem diminuído a quantidade de sistemas completamente novos

# Pontos importantes

- Os processos de software são as atividades envolvidas na produção de um sistema de software. Os modelos de processo de software são representações abstratas desses processos
- Modelos de processo gerais descrevem a organização dos processos de software. Exemplos desses processos geris incluem o modelo 'cascata', desenvolvimento incremental e desenvolvimento orientado a reúso
- A engenharia de requisitos é o processo de desenvolver uma especificação de software
- Processos de projeto e implementação se preocupam em transformar uma especificação de requisitos em um sistema de software executável
- A validação de software é o processo de checar se o sistema está em conformidade com sua especificação e se esse está de acordo com as necessidades reais do usuário do sistema
- A evolução de software ocorre quando você altera sistemas de software existentes para adequá-los a novas necessidades. O software precisa evoluir para continuar útil.
