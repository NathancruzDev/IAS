# Laboratórios Microsoft Learning — IA Generativa e Azure OpenAI

Este repositório contém um resumo aprofundado e orientações sobre três laboratórios essenciais da Microsoft Learning relacionados ao uso de IA generativa e à governança responsável no Microsoft Copilot e Azure OpenAI.

---

## 📌 Conteúdo

1. [Explore Generative AI with Microsoft Copilot](#-explore-generative-ai-with-microsoft-copilot)
2. [Explore Azure OpenAI](#-explore-azure-openai)
3. [Explore Content Filters in Azure OpenAI](#-explore-content-filters-in-azure-openai)

---

##  Explore Generative AI with Microsoft Copilot

###  Descrição  
Este laboratório introduz o **Microsoft Copilot**, a integração de modelos de linguagem natural diretamente nas ferramentas de produtividade do **Microsoft 365** (Word, Excel, PowerPoint, Outlook, Teams). O Copilot potencializa atividades cotidianas, automatizando tarefas, sugerindo conteúdos e sintetizando informações.

O Copilot é alimentado por modelos de IA generativa, como o GPT, adaptados ao ambiente seguro e empresarial da Microsoft, garantindo privacidade, segurança e conformidade.

###  O que você vai aprender?

- **Arquitetura do Microsoft Copilot**:
  - Como os modelos de linguagem são integrados ao Microsoft Graph.
  - Papel do **Semantic Index for Copilot** no fornecimento de contexto.
  - Como o Copilot acessa dados organizacionais com segurança.

- **Casos de uso práticos**:
  - Geração de e-mails automáticos no Outlook.
  - Criação de apresentações no PowerPoint com base em textos descritivos.
  - Elaboração e revisão de documentos no Word.
  - Análises preditivas e geração de gráficos complexos no Excel.

- **IA responsável**:
  - Como o Copilot implementa os **princípios de IA responsável da Microsoft**: justiça, confiabilidade, privacidade, segurança, inclusividade e transparência.
  - Mecanismos de mitigação de riscos, como feedback humano e limitações de uso.

- **Configuração e segurança**:
  - Requisitos de licença e habilitação do Copilot no ambiente organizacional.
  - Como controlar permissões e gerenciar dados sensíveis.

###  Objetivo

- Demonstrar como a IA generativa melhora a produtividade empresarial.
- Capacitar profissionais de TI e negócios a implementar e usar o Copilot de forma responsável.
- Fortalecer o entendimento sobre segurança, privacidade e compliance no uso da IA.

---

## ☁️ Explore Azure OpenAI

###  Descrição  
Este laboratório explora o **Azure OpenAI Service**, a oferta da Microsoft que disponibiliza acesso a modelos de IA de última geração da OpenAI (como **GPT-4, Codex, DALL·E**) com a infraestrutura, segurança e compliance do Microsoft Azure.

O Azure OpenAI permite que empresas criem e escalem aplicações de IA generativa com responsabilidade, contando com recursos como **Content Filtering, logging, quotas, e RBAC (Role-Based Access Control)**.

###  O que você vai aprender?

- **Provisionamento do serviço**:
  - Como criar um recurso do Azure OpenAI no portal Azure.
  - Escolher e configurar as regiões e tipos de modelo disponíveis.

- **Uso dos modelos**:
  - Diferenças e aplicações dos principais modelos:
    - **GPT**: geração de texto, chatbots, resumo, tradução.
    - **Codex**: geração de código, assistentes de programação.
    - **DALL·E**: criação de imagens a partir de descrições textuais.

- **Playground**:
  - Como experimentar prompts e ajustar parâmetros como temperatura, top-p, frequência e penalidade de presença.
  - Avaliação de outputs para diferentes casos de uso.

- **Integração com aplicações**:
  - Uso de **REST APIs** para consumir modelos em backends.
  - Exemplos de integração com **Azure Functions, Logic Apps, Power Automate**.
  - Boas práticas de segurança: gerenciamento de chaves e autenticação via **Managed Identity**.

- **Governança e segurança**:
  - Monitoramento via **Azure Monitor** e **Application Insights**.
  - Controle de acesso granular via **Azure RBAC**.
  - Gerenciamento de **quotas e limites de consumo**.

###  Objetivo

- Capacitar profissionais a integrar modelos de IA generativa em soluções de negócio com segurança e escalabilidade.
- Promover boas práticas no desenvolvimento de soluções baseadas em IA.
- Destacar a importância do compliance e da governança em ambientes corporativos.

---

##  Explore Content Filters in Azure OpenAI

###  Descrição  
Este laboratório se aprofunda no uso dos **Content Filters** do Azure OpenAI Service, um conjunto de ferramentas essenciais para garantir que as interações com modelos generativos sigam padrões éticos e regulatórios, mitigando riscos de uso indevido.

Os filtros analisam entradas e saídas para identificar conteúdo potencialmente prejudicial ou impróprio, classificando e bloqueando conforme políticas definidas.

###  O que você vai aprender?

- **Funcionamento dos Content Filters**:
  - Como o serviço aplica filtros automáticos para bloquear conteúdo com base em categorias como:
    - Ódio e violência.
    - Exploração sexual.
    - Informações confidenciais.
    - Assuntos regulados.
  - Entendimento das métricas de severidade associadas aos filtros.

- **Configuração e personalização**:
  - Ajustar a sensibilidade dos filtros conforme o caso de uso.
  - Configurar políticas de segurança em conjunto com outras ferramentas do Azure, como **Microsoft Purview** e **Defender for Cloud**.

- **Monitoramento e auditoria**:
  - Como gerar logs e relatórios de eventos relacionados a bloqueios e alertas.
  - Estratégias para revisão contínua e melhoria das políticas de filtragem.

- **Estratégias de mitigação de riscos**:
  - Desenvolvimento de prompts seguros e **prompt engineering**.
  - Implementação de mecanismos de fallback e revisão humana.
  - Treinamento de usuários sobre limites e responsabilidades no uso da IA.

###  Objetivo

- Garantir que soluções baseadas em IA sejam implementadas com responsabilidade.
- Capacitar administradores a configurar e monitorar políticas de conteúdo.
- Minimizar riscos legais, éticos e reputacionais associados ao uso de IA generativa.

---

##  Resumo Comparativo

| Laboratório | Foco Principal |
| --- | --- |
| **Explore Generative AI with Microsoft Copilot** | Aplicação prática de IA generativa nas ferramentas do Microsoft 365, com foco em produtividade e responsabilidade. |
| **Explore Azure OpenAI** | Configuração, consumo e integração de modelos de IA generativa com segurança, escalabilidade e compliance via Azure. |
| **Explore Content Filters in Azure OpenAI** | Governança, mitigação de riscos e segurança no uso de IA generativa por meio de filtros de conteúdo robustos. |

---

##  Como utilizar este repositório

1. Leia atentamente cada seção para aprofundar os principais conceitos.
2. Realize os laboratórios correspondentes no **Microsoft Learn**.
3. Aplique os aprendizados em seus projetos e ambientes corporativos.
4. Consulte os recursos adicionais para se manter atualizado.

---
