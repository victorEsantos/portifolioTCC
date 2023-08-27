# portifolioTCC

## Objetivo da aplicação
### A proposta da aplicação 
Consiste em desenvolver um Sistema de Gestão de Tarefas altamente funcional, projetado para auxiliar os usuários a gerenciar suas responsabilidades cotidianas, sejam elas individuais ou em grupo. O objetivo principal é fornecer uma solução eficaz para o desafio de lembrar tarefas importantes dentro de prazos específicos.

### Como funciona?
Ao criar uma tarefa, o usuário pode definir um intervalo de lembrete, escolhendo entre opções diárias, semanais ou mensais. Além disso, se a tarefa for compartilhada entre várias pessoas, o sistema permite a criação de uma lista de responsáveis. O aspecto único é a capacidade de alternar automaticamente a pessoa responsável pela tarefa com base na ordem alfabética, garantindo equidade na distribuição das responsabilidades ao longo do tempo. Essa abordagem inteligente, combinada com os lembretes personalizados, assegura que as tarefas sejam lembradas e concluídas de maneira oportuna e organizada.

## Diagrama visão geral:

![visaoGeral drawio](https://github.com/victorEsantos/portifolioTCC/assets/61585518/894e6e19-5287-4d1e-84e5-77d5122c6d3e)


## Diagrama de contêiners:

![Conteiner drawio](https://github.com/victorEsantos/portifolioTCC/assets/61585518/633ce826-a909-4d08-984a-cd589fc10287)

## Diagrama de classes

![Diagrama sem nome drawio](https://github.com/victorEsantos/portifolioTCC/assets/61585518/1a014556-35db-4ba1-abbc-854e6499c3e2)




# ADRs

## ADR1

Título: Inclusão do Módulo de envio de email, job e regras de négicio em um mesmo sistema.
Status: Decidido.

Alternativas:

1 - Desenvolvimento de Módulo Separado para Envio de Email e jobs.

2 - Modulos juntos em um mesmo sistema.

Decisão: Optar pela Alternativa 2 - Integração do Módulo de Notificação e Responsabilidade no Sistema Principal para gerenciar a responsabilidade semanal de observabilidade e as notificações correspondentes.

Justificativa: Dado o escopo limitado do sistema e a simplicidade das notificações necessárias, a integração do módulo de notificação e responsabilidade diretamente no sistema principal é a abordagem mais eficiente. Isso elimina a necessidade de um módulo separado para envio de email e simplifica a arquitetura do sistema.

Consequências:
* Simplicidade de Arquitetura
* Facilidade de Desenvolvimento
* Manutenção Simplificada
* Baixo Custo
* Limitações de Flexibilidade
