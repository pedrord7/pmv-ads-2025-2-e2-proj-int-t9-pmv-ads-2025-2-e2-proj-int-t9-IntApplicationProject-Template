# Plano de Testes de Usabilidade


## Definição do(s) objetivo(s)

Garantir que o sistema seja intuitivo, funcional e atenda às necessidades do usuário final, validando aspectos técnicos (funcionalidades) e de experiência (usabilidade).


 #Escopo
O plano abrange:
Testes funcionais → Verificar se as funcionalidades implementadas funcionam conforme os requisitos.
Testes de usabilidade → Avaliar a facilidade de uso, clareza das interfaces e eficiência na execução das tarefas.
Ex: "Este plano não abrange testes de desempenho, testes de segurança ou compatibilidade em navegadores desatualizados."
📋 3. Funcionalidades a Testar

Considere agrupar as funcionalidades por categorias para facilitar leitura:

Autenticação: Cadastro e login de usuários.

Gerenciamento de Hábitos: Criação, edição, exclusão, definição de metas.

Engajamento: Recompensas, streaks, notificações.

Social e Relatórios: Compartilhamento, métricas.

🔍 4. Estratégia de Testes
4.1 Testes Funcionais

Para casos mais complexos, adicione testes negativos e alternativos (ex: conexão instável, repetição de hábito, etc).

Reforce a necessidade de regressão para evitar quebra de funcionalidades anteriores.

4.2 Testes de Usabilidade

Pode ser interessante definir tarefas específicas para os testes:

Criar um hábito com meta semanal.

Configurar um lembrete.

Acompanhar o progresso de um hábito no painel de métricas.

📊 5. Métricas de Usabilidade

Além das que já listou, considere:

Net Promoter Score (NPS): "Você recomendaria este app a um amigo?"

Número de cliques por tarefa: útil para identificar caminhos longos.

🛠️ 6. Ferramentas de Apoio

Você pode adicionar ferramentas de:

Gestão de testes: TestRail, Zephyr, Xray.

Captura de feedback com protótipos: Maze, UsabilityHub.

🗓️ 7. Cronograma

Muito bom. Para clareza, considere formatar como tabela:
| Etapa                   | Duração   | Responsável   |
| ----------------------- | --------- | ------------- |
| Planejamento dos testes | 1 semana  | Equipe QA     |
| Testes funcionais       | 2 semanas | Dev + QA      |
| Testes de usabilidade   | 2 semanas | UX Researcher |
| Análise de resultados   | 1 semana  | Equipe UX     |
| Ajustes finais          | 2 semanas | Dev Team      |

✅ 8. Critérios de Aceitação

Excelente, mas pode reforçar:

Todos bugs críticos e altos devem ser corrigidos antes da entrega final.

Nenhuma funcionalidade essencial deve apresentar falhas bloqueantes.

📌 Casos de Teste Funcionais

Perfeitos. Sugestão: adicionar colunas de Prioridade e Status para controle durante execução:

| ID    | Funcionalidade      | Pré-condição | Ação                                   | Resultado Esperado                   | Prioridade | Status    |
| ----- | ------------------- | ------------ | -------------------------------------- | ------------------------------------ | ---------- | --------- |
| CT-01 | Cadastro de usuário | Nenhuma      | Preencher formulário com dados válidos | Conta criada e usuário redirecionado | Alta       | A definir |

🧠 2. Questionário de Usabilidade
Parte A – SUS

Muito bem estruturado. Lembre-se de aplicar a pontuação reversa nos itens ímpares/pares para cálculo correto.

Parte B – Qualitativas

Perfeitas. Considere incluir:

"Você encontrou algo que não funcionou como esperava?"

"O que te motivaria a continuar usando este sistema diariamente?"

🧩 Conclusão

O documento já está muito completo e funcional. Com pequenos ajustes, pode se tornar um plano de referência para testes ágeis e centrados no usuário.

Se quiser, posso gerar:

✅ Um template editável (em Word, Google Docs ou PDF).

✅ Uma planilha com os casos de teste organizados.

✅ Um roteiro para aplicar o teste de usabilidade com participantes.


