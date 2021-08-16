# Fundamentos de Arquiteura de Software

### O que é Arquitetura?
"Organização de um sistema, contemplando seus componentes, os relacionamentos entre estes, com o ambiente e os que governam seu projeto e evolução."

### Pilares
- Organização de um sistema
- Componentização
- Relacionamento entre sistemas
- Governança: Infraestrutura, Time e Arquitetura
- Ambiente
- Projeto: Tem inicio, meio e fim
- Projeção: Possibilidades futuras
- Cultura: Conflito entre a personalidade dos envolvidos

### Frameworks
São ferramentas e métodos que nos ajudam a focar essencialmente no objetivo final. Frameworks nos ajudam a definir um padrão de trabalho

- The TOGAF Standard
    - Framework conceitual
    - Definição dos processos de arquitetura
    - +900 Páginas
    - Conceitos e nomenclaturas
    - Visão geral de tipos de arquiteturas:
        - Negócio
        - Sistemas de informação
        - Tecnologia
        - Planos de migração
- ISO 42010:2011
    - Lançado em 2011 pelo ISO
    - Mais simplificado em relação as 900 páginas do TOGAF
    - Formaliza os fundamentos da área de arquitetura de software.


### Momentos da Arquitetura de Software na História
- Tradicional
- Atual
- Emergente
- Futuro

-------------------------
- Metodologias
- Tipos de aplicação
- Infraestrutura

##### Momento: Tradicional
Metodologia de desenvolvimento: Waterfall

Ciclo de vida do desenvolvimento de software:
1. Requirements Analysis
1. Design
1. Development
1. Testing
1. Maintenance 

Tipos de aplicações: Monolíticas

Infraestrutura: on-premise

##### Momento: Atual
Metodologia de desenvolvimento: Agile

Tipo de aplicações: Multi-tier architecture (Softwares Distribuidos)

Infraestrutura: Virtualização

##### Momento: Emergente
Metodologia de desenvolvimento: DevOps/FullCycle (Cultura)

Tipos de aplicações: Microserviços

Infraestrutura: Containers

##### Momento: Futuro
NoOps

Tipo de aplicações: Serverless Applications

Infraestrutura Public Cloud

### Sistemas Monolíticos
- Tudo em um unico lugar; Tudo em um só sistema.
- Alto acoplamento
- Processo de deploy "completo" a cada mudança
- Normalmente usa uma tecnologia
- Um problrma afeta todo o sistema
- Maior complexidade para times
- Não é crime usar sistema monolítico
- Na maioria dos casos vai atender
- Menos complexidade na maioria dos casos
- Sistema monolítico é Vida!

### Escalando software
- Escala Vertical: Aumento de Recursos Computacionais
- Escala Horizontal: Adição pequenas maquinas acessadas através de um LoadBalancer

### Detalhes sobre a arquitetura da aplicação
- Disco efêmero
- Servidor de aplicação vs Servidor de assets
- Cache centralizado
- Sessões centralizadas
- Upload / Gravação de Arquivos

Tudo pode ter que ser destruído e criado facilmente.

### Distribuição de responsabilidades
