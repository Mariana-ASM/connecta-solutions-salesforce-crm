# Requisitos

## Connecta Solutions – Salesforce CRM Solution

---

# 1. Objetivo

Este documento apresenta os requisitos identificados durante a análise do cenário da Connecta Solutions.

Os requisitos serviram como base para o desenho da solução Salesforce e para a seleção das funcionalidades necessárias para atender às necessidades do negócio.

---

# 2. Escopo

A solução contempla processos relacionados a:

* Gestão Comercial
* Atendimento ao Cliente
* Comunicação e Relacionamento

Os requisitos foram classificados em:

* Requisitos Funcionais (RF)
* Requisitos Não Funcionais (RNF)

---

# 3. Requisitos Funcionais

## Área Comercial

### RF01 – Captura de Leads

O sistema deve permitir a captura automática de leads através do website da empresa.

### RF02 – Validação de Dados

O sistema deve garantir o preenchimento de informações obrigatórias durante o cadastro de leads.

### RF03 – Qualificação de Leads

O sistema deve permitir a classificação e qualificação dos leads antes da conversão.

### RF04 – Conversão de Leads

O sistema deve permitir a conversão de Leads em Conta, Contato e Oportunidade.

### RF05 – Gestão de Oportunidades

O sistema deve permitir o gerenciamento das oportunidades comerciais ao longo do funil de vendas.

### RF06 – Pipeline Comercial

O sistema deve disponibilizar uma visualização das oportunidades por estágio de negociação.

### RF07 – Indicadores Comerciais

O sistema deve disponibilizar dashboards e relatórios para acompanhamento da performance comercial.

---

## Área de Atendimento

### RF08 – Criação Automática de Chamados

O sistema deve permitir a criação automática de chamados a partir de e-mails recebidos.

### RF09 – Gestão de Cases

O sistema deve permitir o registro, acompanhamento e encerramento de chamados.

### RF10 – Distribuição de Chamados

O sistema deve distribuir chamados para equipes ou atendentes responsáveis.

### RF11 – Controle de SLA

O sistema deve monitorar os prazos de atendimento definidos pela empresa.

### RF12 – Automação Operacional

O sistema deve permitir a execução automática de tarefas repetitivas durante o atendimento.

---

## Área de Comunicação

### RF13 – Segmentação de Clientes

O sistema deve permitir a segmentação de clientes com base em critérios definidos pela empresa.

### RF14 – Automação de Campanhas

O sistema deve permitir o envio automatizado de campanhas de comunicação.

### RF15 – Jornadas de Relacionamento

O sistema deve permitir a criação de jornadas automatizadas de relacionamento com clientes.

### RF16 – Monitoramento de Engajamento

O sistema deve permitir acompanhar o engajamento dos clientes com as campanhas realizadas.

---

# 4. Requisitos Não Funcionais

### RNF01 – Disponibilidade

A solução deve estar disponível em ambiente cloud com alta disponibilidade.

### RNF02 – Segurança

O acesso às informações deve ser controlado através de perfis e permissões.

### RNF03 – Escalabilidade

A solução deve suportar o crescimento do volume de usuários e registros.

### RNF04 – Usabilidade

A interface deve ser intuitiva e de fácil utilização pelos usuários.

### RNF05 – Rastreabilidade

Todas as interações devem ser registradas para fins de auditoria e acompanhamento.

### RNF06 – Integridade dos Dados

As informações armazenadas devem manter consistência e confiabilidade.

---

# 5. Priorização dos Requisitos

| ID   | Requisito                      | Prioridade |
| ---- | ------------------------------ | ---------- |
| RF01 | Captura de Leads               | Alta       |
| RF02 | Validação de Dados             | Alta       |
| RF03 | Qualificação de Leads          | Alta       |
| RF04 | Conversão de Leads             | Alta       |
| RF05 | Gestão de Oportunidades        | Alta       |
| RF06 | Pipeline Comercial             | Média      |
| RF07 | Indicadores Comerciais         | Média      |
| RF08 | Criação Automática de Chamados | Alta       |
| RF09 | Gestão de Cases                | Alta       |
| RF10 | Distribuição de Chamados       | Alta       |
| RF11 | Controle de SLA                | Alta       |
| RF12 | Automação Operacional          | Média      |
| RF13 | Segmentação de Clientes        | Média      |
| RF14 | Automação de Campanhas         | Média      |
| RF15 | Jornadas de Relacionamento     | Média      |
| RF16 | Monitoramento de Engajamento   | Baixa      |

---

# 6. Matriz de Rastreabilidade

| Problema Identificado          | Requisito        | Solução Salesforce  |
| ------------------------------ | ---------------- | ------------------- |
| Leads incompletos              | RF01, RF02       | Web-to-Lead         |
| Falta de processo comercial    | RF03, RF04, RF05 | Sales Cloud         |
| Baixa visibilidade do pipeline | RF06, RF07       | Kanban e Dashboards |
| Chamados sem controle          | RF08, RF09       | Email-to-Case       |
| Falta de priorização           | RF10, RF11       | Omni-Channel e SLA  |
| Comunicação genérica           | RF13, RF14, RF15 | Marketing Cloud     |

---

# 7. Critérios de Sucesso

A solução será considerada aderente aos requisitos quando:

* Os leads forem capturados automaticamente.
* O pipeline comercial estiver estruturado e monitorado.
* Os chamados forem registrados e distribuídos automaticamente.
* Os SLAs forem controlados pela plataforma.
* As campanhas puderem ser segmentadas e automatizadas.
* Os usuários tiverem acesso a indicadores de desempenho.

---

# 8. Conclusão

Os requisitos apresentados neste documento serviram como base para o desenho da solução Salesforce da Connecta Solutions.

A partir deles foi possível definir as funcionalidades necessárias para atender às necessidades do negócio, garantindo alinhamento entre os objetivos da empresa e os recursos disponibilizados pela plataforma Salesforce.
