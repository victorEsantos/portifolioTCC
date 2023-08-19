# portifolioTCC

## Diagrama visão geral:

![visaoGeral drawio](https://github.com/victorEsantos/portifolioTCC/assets/61585518/894e6e19-5287-4d1e-84e5-77d5122c6d3e)


## Diagrama de contêiners:

![Conteiner drawio](https://github.com/victorEsantos/portifolioTCC/assets/61585518/633ce826-a909-4d08-984a-cd589fc10287)



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
