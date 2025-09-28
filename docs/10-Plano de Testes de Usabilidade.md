# 📋 Plano de Testes de Software e Usabilidade  
**Sistema de Gerenciamento de Hábitos**

---

## 1. Objetivo  
Garantir que o sistema seja **intuitivo, funcional** e atenda às necessidades do usuário final, validando aspectos técnicos (funcionalidades) e de experiência (usabilidade).  

---

## 2. Escopo  
O plano abrange:  
- **Testes funcionais** → Verificar se as funcionalidades implementadas funcionam conforme os requisitos.  
- **Testes de usabilidade** → Avaliar a facilidade de uso, clareza das interfaces e eficiência na execução das tarefas.  

---

## 3. Funcionalidades a Testar  
- Cadastro e login de usuários.  
- Criação, edição e exclusão de hábitos.  
- Definição de periodicidade e metas personalizadas.  
- Registro de check-ins diários.  
- Sistema de recompensas e streaks.  
- Lembretes e notificações.  
- Compartilhamento de conquistas em redes sociais.  
- Visualização de métricas e relatórios de progresso.  

---

## 4. Estratégia de Testes  

### 4.1 Testes Funcionais  
- **Método**: Testes manuais e automatizados.  
- **Abordagem**: Caixa-preta (validação de entradas e saídas).  

**Exemplo de Caso de Teste:**  
- **ID**: CT-01  
- **Funcionalidade**: Cadastro de usuário  
- **Ação**: Preencher formulário com dados válidos  
- **Resultado esperado**: Conta criada e usuário redirecionado para tela inicial.  

### 4.2 Testes de Usabilidade  
- **Método**: Testes de campo com usuários reais (5 a 10 por perfil).  
- **Perfis testados**: Estudantes, profissionais e adultos buscando saúde.  
- **Critérios observados**:  
  - **Eficiência** – Tempo para realizar tarefas.  
  - **Eficácia** – Percentual de tarefas concluídas.  
  - **Satisfação** – Nível de satisfação do usuário (questionário SUS).  
  - **Aprendizado** – Facilidade de compreender funcionalidades sem tutoriais extensos.  

---

## 5. Métricas de Usabilidade  
- Tempo médio de execução de tarefas.  
- Taxa de erro (ações incorretas ou abandonadas).  
- Taxa de sucesso em tarefas.  
- **SUS Score** (0–100).  
- Feedback qualitativo.  

---

## 6. Ferramentas de Apoio  
- **Funcionais**: Postman (API), Selenium/Appium (automatização), JUnit/PyTest.  
- **Usabilidade**: Gravação de tela, questionários SUS, protótipos interativos (Figma, MarvelApp).  

---

## 7. Cronograma (Exemplo)  

| Etapa                     | Duração    | Responsável   |  
|----------------------------|------------|---------------|  
| Planejamento dos testes    | 1 semana   | Equipe QA     |  
| Testes funcionais iniciais | 2 semanas  | Dev + QA      |  
| Testes de usabilidade      | 2 semanas  | UX Researcher |  
| Análise de resultados      | 1 semana   | Equipe UX     |  
| Ajustes finais             | 2 semanas  | Dev Team      |  

---

## 8. Critérios de Aceitação  
- Funcionalidades críticas (cadastro, login, criação de hábito, check-ins) devem ter **100% de sucesso**.  
- **SUS ≥ 80** (considerado “excelente”).  
- Taxa de sucesso em tarefas ≥ **90%**.  
- Tempo médio para criar um hábito ≤ **1 minuto**.  

---

## 9. Casos de Teste Funcionais  

| ID   | Funcionalidade       | Pré-condição             | Ação                                  | Resultado Esperado                                       |  
|------|----------------------|--------------------------|---------------------------------------|---------------------------------------------------------|  
| CT-01 | Cadastro de usuário  | Nenhuma                  | Preencher formulário com dados válidos | Conta criada e redirecionamento para tela inicial        |  
| CT-02 | Cadastro de usuário  | Nenhuma                  | Preencher formulário com e-mail inválido | Mensagem de erro exibida, sem criar conta              |  
| CT-03 | Login                | Usuário já cadastrado    | Inserir credenciais válidas            | Usuário acessa a tela principal                         |  
| CT-04 | Login                | Usuário já cadastrado    | Inserir senha incorreta                | Exibir mensagem de erro                                 |  
| CT-05 | Criação de hábito    | Usuário logado           | Inserir nome e meta                    | Hábito aparece na lista do usuário                      |  
| CT-06 | Check-in diário      | Hábito criado            | Marcar como concluído                  | Hábito exibido como concluído, streak atualizado        |  
| CT-07 | Sistema de recompensas | Usuário com streak ≥ 7  | Atingir meta mínima                    | Recompensa visual/medalha liberada                      |  
| CT-08 | Notificações         | Usuário com hábito ativo | Configurar lembrete                    | Sistema envia notificação no horário programado         |  
| CT-09 | Relatórios           | Hábitos registrados      | Acessar painel de métricas             | Exibir relatórios gráficos de progresso                 |  
| CT-10 | Compartilhamento     | Usuário com conquista    | Clicar em “compartilhar”               | Postagem gerada em rede social integrada                |  

---

## 10. Questionário de Usabilidade  

### Parte A – SUS (System Usability Scale)  
1. Eu usaria este sistema com frequência.  
2. Achei o sistema desnecessariamente complexo. *(inverso)*  
3. Achei o sistema fácil de usar.  
4. Acho que precisaria de ajuda técnica para usar o sistema. *(inverso)*  
5. As funcionalidades estão bem integradas.  
6. Achei o sistema inconsistente em alguns momentos. *(inverso)*  
7. A maioria das pessoas aprenderia a usar este sistema rapidamente.  
8. Achei o sistema complicado de aprender. *(inverso)*  
9. Eu me senti confiante usando o sistema.  
10. Precisei aprender muitas coisas antes de conseguir usar. *(inverso)*  

> **Resultado**: respostas convertidas em **SUS Score (0–100)**.  

---

### Parte B – Perguntas Qualitativas  
- Qual foi a sua primeira impressão ao usar o sistema?  
- O que você achou mais fácil de fazer?  
- O que você achou mais difícil/confuso de entender?  
- Você se sentiu motivado a registrar seus hábitos diariamente?  
- Que melhorias você sugeriria para deixar o sistema mais útil ou agradável?  
- Você recomendaria este sistema para amigos/colegas? Por quê?  

