# Decisões Funcionais da Solução

## 1. Objetivo do Documento

Este documento apresenta as principais decisões funcionais tomadas durante o desenho da solução Salesforce para a Connecta Solutions.

O objetivo é demonstrar o racional utilizado para selecionar funcionalidades da plataforma Salesforce com base nos desafios identificados no negócio.

---

# 2. Contexto

Durante a análise do cenário atual da Connecta Solutions foram identificados problemas relacionados aos processos de vendas, atendimento ao cliente e comunicação.

Com base nessas necessidades, foi realizada a seleção de funcionalidades do Salesforce capazes de atender aos requisitos levantados.

---

# 3. Decisões Funcionais – Sales Cloud

## Decisão 01 – Implementação do Web-to-Lead

### Problema Identificado

Os leads chegavam através do website com informações incompletas, dificultando o trabalho da equipe comercial.

### Decisão

Implementar o recurso Web-to-Lead.

### Justificativa

O Web-to-Lead permite capturar informações diretamente do site e definir campos obrigatórios, garantindo maior qualidade dos dados recebidos.

### Benefícios Esperados

* Redução de informações incompletas.
* Melhor qualidade dos leads.
* Menor retrabalho da equipe comercial.

---

## Decisão 02 – Definição de Opportunity Stages

### Problema Identificado

Não existia um processo comercial padronizado para acompanhamento das negociações.

### Decisão

Estruturar o funil comercial através de Opportunity Stages.

### Justificativa

A utilização de etapas padronizadas permite que todas as oportunidades sigam o mesmo fluxo comercial.

### Benefícios Esperados

* Maior previsibilidade de vendas.
* Melhor acompanhamento das negociações.
* Padronização do processo comercial.

---

## Decisão 03 – Utilização do Sales Path

### Problema Identificado

Os vendedores não possuíam direcionamento claro sobre quais atividades executar em cada etapa da venda.

### Decisão

Implementar o Sales Path.

### Justificativa

O Sales Path orienta os usuários sobre informações importantes e próximos passos durante o processo comercial.

### Benefícios Esperados

* Aumento da aderência ao processo.
* Redução de erros operacionais.
* Maior produtividade da equipe.

---

## Decisão 04 – Visualização Kanban

### Problema Identificado

Dificuldade em visualizar rapidamente as oportunidades em negociação.

### Decisão

Utilizar a visualização Kanban.

### Justificativa

O Kanban permite uma gestão visual simples e intuitiva do pipeline de vendas.

### Benefícios Esperados

* Melhor visibilidade do pipeline.
* Identificação rápida de gargalos.
* Acompanhamento facilitado.

---

## Decisão 05 – Dashboards Gerenciais

### Problema Identificado

Ausência de indicadores para acompanhamento da operação comercial.

### Decisão

Criar dashboards e relatórios gerenciais.

### Justificativa

Os dashboards permitem transformar dados operacionais em informações estratégicas para tomada de decisão.

### Benefícios Esperados

* Monitoramento de resultados.
* Maior controle da operação.
* Apoio à tomada de decisão.

---

# 4. Decisões Funcionais – Service Cloud

## Decisão 06 – Implementação do Email-to-Case

### Problema Identificado

Os chamados eram recebidos por e-mail sem qualquer controle centralizado.

### Decisão

Implementar o Email-to-Case.

### Justificativa

Permite transformar automaticamente e-mails em registros de atendimento dentro do Salesforce.

### Benefícios Esperados

* Centralização dos chamados.
* Melhor rastreabilidade.
* Redução de processos manuais.

---

## Decisão 07 – Utilização de Filas de Atendimento

### Problema Identificado

Não existia organização na distribuição dos chamados.

### Decisão

Criar filas de atendimento.

### Justificativa

As filas permitem direcionar os chamados para equipes responsáveis por cada tipo de demanda.

### Benefícios Esperados

* Melhor distribuição de trabalho.
* Maior organização operacional.
* Redução de atrasos.

---

## Decisão 08 – Implementação do Omni-Channel

### Problema Identificado

Distribuição desigual dos chamados entre os atendentes.

### Decisão

Implementar Omni-Channel.

### Justificativa

O Omni-Channel distribui automaticamente os casos para os agentes disponíveis.

### Benefícios Esperados

* Redução do tempo de resposta.
* Balanceamento da carga de trabalho.
* Melhor experiência do cliente.

---

## Decisão 09 – Definição de SLA

### Problema Identificado

Não havia controle dos prazos de atendimento.

### Decisão

Implementar Entitlements e SLA.

### Justificativa

Garantir que os chamados sejam tratados dentro dos níveis de serviço definidos.

### Benefícios Esperados

* Controle dos prazos.
* Melhor qualidade de atendimento.
* Maior satisfação dos clientes.

---

## Decisão 10 – Utilização de Macros

### Problema Identificado

Atividades repetitivas consumiam grande parte do tempo dos atendentes.

### Decisão

Implementar Macros.

### Justificativa

Automatizar ações recorrentes durante o atendimento.

### Benefícios Esperados

* Aumento da produtividade.
* Padronização das respostas.
* Redução de tempo operacional.

---

# 5. Decisões Funcionais – Marketing Cloud

## Decisão 11 – Segmentação de Clientes

### Problema Identificado

A comunicação era enviada de forma genérica para toda a base.

### Decisão

Criar segmentos de clientes.

### Justificativa

Permitir comunicações mais relevantes e direcionadas.

### Benefícios Esperados

* Maior engajamento.
* Melhor experiência do cliente.
* Campanhas mais eficientes.

---

## Decisão 12 – Implementação do Journey Builder

### Problema Identificado

Não existia uma estratégia automatizada de relacionamento.

### Decisão

Criar jornadas automatizadas.

### Justificativa

Permitir o envio de comunicações personalizadas ao longo do ciclo de vida do cliente.

### Benefícios Esperados

* Relacionamento contínuo.
* Maior taxa de conversão.
* Fidelização de clientes.

---

## Decisão 13 – Utilização do Einstein Engagement Scoring

### Problema Identificado

Dificuldade em identificar clientes mais propensos ao engajamento.

### Decisão

Utilizar Einstein Engagement Scoring.

### Justificativa

A funcionalidade utiliza inteligência artificial para prever o comportamento dos clientes.

### Benefícios Esperados

* Melhor segmentação.
* Priorização de oportunidades.
* Comunicação mais assertiva.

---

# 6. Resumo Executivo das Decisões

| Problema                      | Funcionalidade Salesforce   | Benefício              |
| ----------------------------- | --------------------------- | ---------------------- |
| Leads incompletos             | Web-to-Lead                 | Qualidade dos dados    |
| Falta de processo comercial   | Opportunity Stages          | Padronização           |
| Falta de orientação comercial | Sales Path                  | Aderência ao processo  |
| Baixa visibilidade            | Kanban                      | Gestão visual          |
| Falta de indicadores          | Dashboards                  | Tomada de decisão      |
| Chamados sem controle         | Email-to-Case               | Centralização          |
| Distribuição inadequada       | Filas                       | Organização            |
| Sobrecarga de atendentes      | Omni-Channel                | Balanceamento          |
| Falta de SLA                  | Entitlements e SLA          | Controle de prazo      |
| Processos repetitivos         | Macros                      | Produtividade          |
| Comunicação genérica          | Segmentação                 | Personalização         |
| Relacionamento manual         | Journey Builder             | Automação              |
| Baixo uso dos dados           | Einstein Engagement Scoring | Inteligência analítica |

---

# 7. Conclusão

As decisões funcionais apresentadas neste documento foram tomadas com base nos requisitos identificados durante a análise do cenário da Connecta Solutions.

A solução proposta busca alinhar as necessidades do negócio às capacidades da plataforma Salesforce, promovendo maior eficiência operacional, melhor experiência do cliente e suporte à tomada de decisão baseada em dados.
