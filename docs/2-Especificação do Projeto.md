# Especificações do Projeto

A especificação do projeto detalha o problema e a solução proposta a partir da perspectiva do usuário. Este capítulo abrange a definição de personas, histórias de usuários, requisitos (funcionais e não funcionais) e restrições, com o uso de técnicas como brainstorming e design centrado no usuário. A abordagem foca em garantir clareza e objetividade para o desenvolvimento do sistema.

## Personas  

1. **Lucas Almeida (Gestor de Segurança do Trabalho)**  
   - **Idade:** 35 anos  
   - **Descrição:** Engenheiro de segurança em uma indústria automotiva, responsável por garantir o uso de EPIs e a conformidade com regulamentações. Tem conhecimento intermediário em tecnologia, mas utiliza frequentemente relatórios para tomada de decisão.  
   - **Objetivos:** Monitorar os EPIs dos trabalhadores e gerar relatórios precisos para auditorias.  
   - **Desafios:** Falta de ferramentas automatizadas para fiscalização em tempo real.  

2. **Ana Souza (Operadora de Produção)**  
   - **Idade:** 28 anos  
   - **Descrição:** Trabalhadora em uma linha de montagem, que utiliza EPIs diariamente. Tem conhecimento básico em tecnologia e foco nas atividades operacionais.  
   - **Objetivos:** Garantir que seus EPIs estejam em conformidade para evitar multas ou advertências.  
   - **Desafios:** Não compreende todas as exigências de segurança detalhadamente.  

3. **Carlos Medeiros (Técnico de TI)**  
   - **Idade:** 40 anos  
   - **Descrição:** Responsável pela manutenção e suporte técnico da infraestrutura de TI. Possui alto conhecimento técnico e lida diretamente com integrações e sistemas.  
   - **Objetivos:** Instalar e configurar a aplicação no ambiente industrial, garantindo sua estabilidade.  
   - **Desafios:** Tempo limitado para suporte e necessidade de uma solução simples de manter.  

---

## Histórias de Usuários

| EU COMO...              | QUERO/PRECISO...                                 | PARA...                                      |  
|--------------------------|-------------------------------------------------|---------------------------------------------|  
| Lucas (Gestor)           | Monitorar os trabalhadores em tempo real        | Garantir o cumprimento das normas de segurança |  
| Lucas (Gestor)           | Gerar relatórios periódicos                     | Apresentar em auditorias regulatórias       |  
| Ana (Operadora)          | Receber notificações caso não esteja com EPI    | Corrigir imediatamente e evitar advertências |  
| Carlos (Técnico de TI)   | Instalar e configurar a solução facilmente      | Reduzir o tempo de implementação            |  
| Lucas (Gestor)           | Configurar alertas automáticos                  | Receber informações de incidentes críticos  |  

---
## Requisitos  

### **Requisitos Funcionais (RF)**  

| ID     | Descrição do Requisito                               | Prioridade |  
|--------|-----------------------------------------------------|------------|  
| RF-001 | Detectar e identificar EPIs em tempo real           | ALTA       |  
| RF-002 | Notificar gestores quando um trabalhador estiver sem EPI | ALTA       |  
| RF-003 | Gerar relatórios mensais sobre o uso de EPIs         | MÉDIA      |  
| RF-004 | Permitir a configuração de alertas automáticos       | MÉDIA      |  

### **Requisitos Não Funcionais (RNF)**  

| ID      | Descrição do Requisito                              | Prioridade |  
|---------|----------------------------------------------------|------------|  
| RNF-001 | O sistema deve ser acessível via dispositivos móveis e desktops | ALTA       |  
| RNF-002 | As notificações devem ser enviadas em menos de 5 segundos após detecção | MÉDIA      |  
| RNF-003 | A aplicação deve suportar até 200 trabalhadores monitorados simultaneamente | MÉDIA      |  
| RNF-004 | O sistema deve operar offline, salvando eventos localmente para sincronização posterior | BAIXA      |  

---

## Restrições  

| ID  | Restrição                                                |  
|-----|----------------------------------------------------------|  
| 01  | O projeto deve ser concluído até o final do semestre acadêmico |  
| 02  | A solução deve utilizar exclusivamente tecnologias já disponíveis no ambiente industrial |  
| 03  | O orçamento do projeto não deve exceder R$10.000         |  

--- 
