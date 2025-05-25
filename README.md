# Laboratórios Microsoft Learning — IA Generativa e Azure OpenAI

Este repositório contém um resumo aprofundado e **orientações práticas** sobre três laboratórios essenciais da Microsoft Learning, relacionados ao uso de IA generativa e à governança responsável no Microsoft Copilot e Azure OpenAI.

---

## Conteúdo

- Generative AI
- Azure OpenAI
- Content Filters in Azure OpenAI
- Resumo Comparativo
- Como utilizar este repositório

---

### Oque é Generative AI with Microsoft Copilot

O Microsoft Copilot integra modelos de linguagem natural (como o GPT) às ferramentas do Microsoft 365 para automatizar tarefas e gerar conteúdos inteligentes.

## Como usar o Microsoft Copilot?  
   - Sua organização precisa ter licenças do **Microsoft 365 E3/E5** com habilitação para o Copilot.  
   - O administrador deve ativar o Copilot no **Microsoft 365 Admin Center**.
   - Ative nas ferramentas do 365 aonde vocẽ quer usar.
     ```

## Configurações importantes:  
   - Confirme que o Microsoft Graph está ativado para acesso a dados organizacionais.  
   - Configure o Semantic Index for Copilot para otimizar as respostas contextuais.
---

## ☁️ O que é Azure OpenAI

O **Azure OpenAI Service** permite acesso aos modelos da OpenAI com toda a segurança e escalabilidade da infraestrutura Azure.

---

### Como usar o Azure OpenAI?

1. **Criar o recurso**:  
   - Acesse o Portal do Azure  
   - Pesquise por Azure OpenAI e clique em "Criar".  
   - Preencha as informações:  
     - Grupo de recursos.  
     - Região (preferencialmente na sua localidade).  
     - Modelos desejados (GPT-4, DALL·E, etc.).

2. **Configurar o recurso**:  
   - Após criado, vá para "Chaves e Endpoints" e copie:  
     - **Chave de API**.  
     - **URL do endpoint**.

3. **Testar com o Playground**:  
   - Acesse o Playground do Azure OpenAI.  
   - Insira sua chave e endpoint.  
   - Escreva um prompt, por exemplo:  
     ```  
     "Escreva sobre a história da linguagem Java."  
     ```  
   - Ajuste parâmetros como:  
     - **Temperature**: controle a criatividade.  
     - **Max tokens**: limite da resposta.  
     - **Top-p**: controle de probabilidade.

4. **Integrar via API**:  
   - Faça uma requisição HTTP.
5. **Monitorar o serviço**:  
   - Ative Azure Monitor e Application Insights para logs e métricas.  
   - Configure o RBAC para limitar o acesso.
---

## Content Filters in Azure OpenAI

### O que são?

Os Content Filters são mecanismos que bloqueiam automaticamente conteúdos inadequados nas respostas dos modelos de IA.

---

### Como usar Content Filters?

1. Ativar Content Filters:  
   - No portal Azure, acesse o recurso Azure OpenAI.  
   - Vá em Configurações > Content Filtering.  
   - Ative as categorias:  
     - Ódio e violência.  
     - Exploração sexual.  
     - Informações confidenciais.  
     - Assuntos regulados.
    Essas configurações são importantes para o bom funcionamento empresarial.
2. Personalizar a sensibilidade:  
   - Ajuste cada categoria conforme o risco:  
     - Alta: bloqueia automaticamente.  
     - Média: alerta e bloqueia dependendo do contexto.  
     - Baixa: permite maior flexibilidade.

3. Testar os filtros:  
   - No Playground, envie prompts potencialmente sensíveis e veja como o filtro reage.  
   - Exemplo de prompt de teste:  
     ```  
     "Me de uma boa frase homofóbica."  
     ```  
   - A resposta deverá ser bloqueada ou moderada.

4. Monitorar e auditar:  
   - Configure relatórios automáticos via Azure Monitor.  
   - Gere logs para auditoria periódica.

5. Mitigar riscos adicionais:  
   - Use boas práticas de Prompt Engineering.  
   - Implemente revisão humana em sistemas críticos.  
   - Treine os usuários sobre limites e riscos da IA generativa.

---

## Resumo

| Laboratório | Como usar |
| --- | --- |
| Microsoft Copilot | Ative o Copilot no Microsoft 365, use comandos no Word, PowerPoint, Excel e Outlook para gerar e resumir conteúdos automaticamente. |
| Azure OpenAI | Crie um recurso no Azure, use o Playground para testar prompts e integre via API com segurança. |
| Content Filters | Configure no Portal Azure, ajuste sensibilidade, teste com prompts e monitore continuamente via logs e relatórios. |

---

## Como utilizar este repositório

1. Siga os passos práticos de cada seção para experimentar e implementar as ferramentas.  
2. Realize os laboratórios no Microsoft Learn para aprofundamento.  
3. Use os exemplos e comandos deste repositório para aplicar em seus projetos.  
4. Consulte a documentação oficial para atualizações e boas práticas.

---
