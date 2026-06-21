# Connecta Solutions – Salesforce Functional Challenge

![Salesforce](https://img.shields.io/badge/Salesforce-CRM-blue)
![Sales Cloud](https://img.shields.io/badge/Sales-Cloud-blue)
![Service Cloud](https://img.shields.io/badge/Service-Cloud-green)
![Marketing Cloud](https://img.shields.io/badge/Marketing-Cloud-orange)
![License](https://img.shields.io/badge/License-CC_BY--NC_4.0-lightgrey)

## Índice

- [Sobre o Desafio](#-sobre-o-desafio)
- [Papel Exercido](#-papel-exercido)
- [Cenário de Negócio](#-cenário-de-negócio)
- [Solução Proposta](#-solução-proposta)
- [Arquitetura da Solução](#-arquitetura-da-solução)
- [Fluxo Comercial](#-fluxo-comercial)
- [Fluxo de Atendimento](#-fluxo-de-atendimento)
- [Funcionalidades Salesforce Utilizadas](#-funcionalidades-salesforce-utilizadas)
- [Benefícios Esperados](#-benefícios-esperados)
- [Evidências da Implementação](#-evidências-da-implementação)
- [Documentação Complementar](#-documentação-complementar)
- [Metodologias Aplicadas](#-metodologias-aplicadas)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Autor](#-autor)
- [Licença](#-licença)

# Descrição do Projeto

Este projeto foi desenvolvido como parte de um desafio funcional promovido pela empresa Dream Experience, o desafio foi voltado para a prática de Análise de Negócios, CRM e desenho de soluções Salesforce.

O objetivo foi atuar como Analista Funcional Salesforce, compreendendo os desafios apresentados por uma empresa fictícia e propondo uma solução capaz de otimizar processos de vendas, atendimento ao cliente e comunicação.

A proposta foi construída utilizando recursos do ecossistema Salesforce e aplicando conceitos de Business Analysis, CRM Design, Process Mapping e boas práticas de implementação.

---

# Sobre o Desafio

A Connecta Solutions é uma empresa fictícia que iniciou sua jornada com Salesforce buscando organizar melhor:

- O processo comercial;
- O atendimento ao cliente;
- A comunicação com leads e clientes.

Como Analista Funcional, o desafio consistiu em:

- Identificar os problemas de negócio;
- Levantar requisitos;
- Mapear processos;
- Desenhar fluxos de atendimento e vendas;
- Selecionar funcionalidades Salesforce aderentes às necessidades da empresa;
- Apresentar uma proposta de solução para a banca avaliadora.

---

# Competências Demonstradas

## Salesforce

- Salesforce CRM
- Salesforce Sales Cloud
- Salesforce Service Cloud
- Salesforce Marketing Cloud
- Lead Management
- Opportunity Management
- Case Management
- Customer Journey

## Análise Funcional

- Levantamento de Requisitos
- Business Analysis
- Functional Analysis
- CRM Design
- Process Mapping
- Solution Design

## Metodologias

- Agile Mindset
- Discovery Workshop
- AS-IS / TO-BE Analysis
- Customer Journey Mapping
- Salesforce Best Practices

---
# Papel Exercido

Neste projeto atuei como Analista Funcional Salesforce, sendo responsável por:

- Análise do cenário de negócio;
- Levantamento de requisitos;
- Identificação de dores e oportunidades;
- Mapeamento de processos;
- Desenho da arquitetura da solução;
- Definição de funcionalidades Salesforce;
- Estruturação de automações;
- Elaboração da documentação funcional.

---

# Cenário de Negócio

A Connecta Solutions enfrentava desafios relacionados às áreas comercial, atendimento e comunicação.

## Captação e Vendas

### Situação Atual

- Leads chegam através de formulários do site.
- Informações frequentemente incompletas.
- Falta de padronização das etapas comerciais.
- Dificuldade para acompanhar negociações.

### Impactos

- Retrabalho da equipe comercial.
- Baixa visibilidade do pipeline.
- Perda de oportunidades de negócio.

---

## Atendimento ao Cliente

### Situação Atual

- Chamados recebidos apenas por e-mail.
- Ausência de padronização.
- Falta de priorização.

### Impactos

- Tempo elevado de resposta.
- Baixo controle operacional.
- Experiência inconsistente para o cliente.

---

## Comunicação e Dados

### Situação Atual

- Comunicação genérica.
- Baixo aproveitamento dos dados do CRM.

### Impactos

- Menor engajamento dos clientes.
- Campanhas pouco eficientes.
- Oportunidades perdidas de relacionamento.

---

# Solução Proposta

A solução foi estruturada utilizando três produtos da plataforma Salesforce.

## Sales Cloud

Responsável pela gestão comercial.

### Funcionalidades Implementadas

- Web-to-Lead
- Lead Qualification
- Opportunity Stages
- Sales Path
- Kanban
- Dashboards

### Objetivo

Padronizar o processo comercial e melhorar a qualidade dos leads.

---

## Service Cloud

Responsável pelo atendimento ao cliente.

### Funcionalidades Implementadas

- Email-to-Case
- Web-to-Case
- Filas de Atendimento
- Omni-Channel
- Entitlements e SLA
- Macros

### Objetivo

Centralizar e padronizar o atendimento.

---

## Marketing Cloud

Responsável pela comunicação e relacionamento.

### Funcionalidades Implementadas

- Segmentação de Clientes
- Campanhas Automatizadas
- Jornadas de Relacionamento
- Einstein Engagement Scoring

### Objetivo

Personalizar a comunicação utilizando dados do CRM.

---

# Justificativa da Solução

A escolha das funcionalidades Salesforce foi realizada com base nas necessidades identificadas durante a análise do cenário atual.

| Desafio | Funcionalidade Salesforce | Benefício |
|----------|----------|----------|
| Leads incompletos | Web-to-Lead | Melhoria da qualidade dos dados |
| Falta de processo comercial | Opportunity Stages | Padronização do funil |
| Baixa visibilidade das negociações | Kanban | Gestão visual do pipeline |
| Chamados por e-mail sem controle | Email-to-Case | Centralização do atendimento |
| Falta de priorização | SLA e Omni-Channel | Atendimento mais eficiente |
| Comunicação genérica | Marketing Cloud | Personalização do relacionamento |

---

# Arquitetura da Solução

```text
Website
   │
   ▼
Web-to-Lead
   │
   ▼
Sales Cloud
   │
   ├── Leads
   ├── Contas
   ├── Contatos
   └── Oportunidades
              │
              ▼
        Marketing Cloud
              │
              ▼
     Campanhas Personalizadas

────────────────────────────

Cliente
   │
   ▼
Email-to-Case / Web-to-Case
   │
   ▼
Service Cloud
   │
   ├── Cases
   ├── Filas
   ├── SLA
   └── Omni-Channel
````

---

# Fluxo Comercial

```text
Lead entra via site
        ↓
Validação de dados
        ↓
Qualificação
        ↓
Conversão
        ↓
Conta + Contato + Oportunidade
        ↓
Pipeline Comercial
        ↓
Fechamento
```

---

# Fluxo de Atendimento

```text
Cliente envia solicitação
           ↓
Email-to-Case
           ↓
Criação do Case
           ↓
Classificação
           ↓
Priorização
           ↓
Fila de Atendimento
           ↓
Atendimento
           ↓
Resolução
           ↓
Encerramento
```

---

# Funcionalidades Salesforce Utilizadas

| Cloud           | Funcionalidade              | Objetivo                       |
| --------------- | --------------------------- | ------------------------------ |
| Sales Cloud     | Web-to-Lead                 | Captura automática de leads    |
| Sales Cloud     | Opportunity Stages          | Padronização do funil          |
| Sales Cloud     | Sales Path                  | Orientação comercial           |
| Sales Cloud     | Kanban                      | Visualização do pipeline       |
| Service Cloud   | Email-to-Case               | Criação automática de chamados |
| Service Cloud   | Omni-Channel                | Distribuição automática        |
| Service Cloud   | SLA                         | Controle de atendimento        |
| Service Cloud   | Macros                      | Automação operacional          |
| Marketing Cloud | Journey Builder             | Automação de campanhas         |
| Marketing Cloud | Einstein Engagement Scoring | Análise de engajamento         |

---

# Benefícios Esperados

* Melhoria da qualidade dos leads.
* Padronização dos processos comerciais.
* Redução do tempo de atendimento.
* Melhor controle dos SLAs.
* Comunicação personalizada.
* Melhor aproveitamento dos dados do CRM.
* Aumento da produtividade das equipes.

---

# Evidências da Implementação

## Sales Cloud

* Web-to-Lead
* Opportunity Path
* Kanban
* Dashboard Comercial

> Procurar screenshots da implementação realizada no Salesforce na pasta docs/screenshots.

## Service Cloud

* Email-to-Case
* Registro de Cases
* Omni-Channel
* Macros

## Marketing Cloud

* Segmentação de Clientes
* Journey Builder
* Campanhas Automatizadas

---

# Documentação Complementar

A documentação completa do projeto está disponível na pasta `docs`.

- [Documentação Funcional](docs/01-Documentacao-Funcional.md)
- [Decisões Funcionais](docs/02-Decisoes-Funcionais.md)
- [Metodologia](docs/03-Metodologia.md)
- [Requisitos](docs/04-Requisitos.md)
- [Guia de Implementação](docs/05-Guia-de-Implementacao.md)

---

# Metodologias Aplicadas

* Agile Mindset
* Discovery Workshop
* Levantamento de Requisitos
* Business Analysis
* Process Mapping (AS-IS / TO-BE)
* CRM Design
* Salesforce Best Practices

---

# Tecnologias Utilizadas

* Salesforce Sales Cloud
* Salesforce Service Cloud
* Salesforce Marketing Cloud
* CRM Design
* Business Analysis
* Process Mapping

---

# Autor

**Mariana Camila, Mariana Monteiro, Paulo Félix, Thiago Félix e Ycaro Agrielle**

Projeto desenvolvido para fins educacionais e demonstração de competências em Salesforce CRM, Análise Funcional, Business Analysis e Solution Design.

---

## 📄 Licença

© 2026 Mariana Monteiro

Este projeto está licenciado sob a licença Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0).

Você pode compartilhar e adaptar este material para fins não comerciais, desde que atribua o devido crédito à autora.

Para mais informações, consulte o arquivo LICENSE.

```
