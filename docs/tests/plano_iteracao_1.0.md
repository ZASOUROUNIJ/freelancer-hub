# Plano de Iteração

## Estrutura de Iterações

O plano de iteração seguirá uma abordagem ágil, dividindo o projeto em sprints de 1 a 2 semanas. Cada iteração terá um conjunto de metas específicas, priorizando funcionalidades críticas e avançando para melhorias e integrações adicionais.

- **Iteração 0: Configuração Básica**

  - Tarefas:
    - Criação das milestones no Github.
    - Configuração do ambiente (Node.js, Express, MongoDB/PostgreSQL, etc.).
    - Autenticação de usuários (login/registro com JWT ou sessão).
    - Estruturação do banco de dados para clientes, freelancers e projetos.
  - Meta: Configurar o backend básico e garantir que o login e registro funcionem corretamente.

- **Iteração 1: Gerenciamento de Projetos**

  - Tarefas:
    - Implementar rotas para criação, edição e exclusão de projetos pelos clientes.
    - Implementar candidaturas e gerenciamento de propostas pelos freelancers.
    - Implementar a lógica de aceitação de freelancers pelos clientes.
  - Meta: Finalizar o fluxo de criação e gestão de projetos e candidaturas.

- **Iteração 2: Sistema de Pagamentos**

  - Tarefas:
    - Integração com um gateway de pagamento (PayPal, Stripe).
    - Implementar o pagamento por marcos, permitindo que os clientes paguem conforme etapas do projeto são concluídas.
    - Testar a segurança e consistência dos pagamentos.
  - Meta: Concluir o sistema de pagamento e validar o fluxo completo de projetos e candidaturas.

- **Iteração 3: Feedback e Avaliações**

  - Tarefas:
    - Implementar o sistema de feedback pós-projeto, permitindo que freelancers e clientes se avaliem.
    - Adicionar funcionalidades de busca e filtros para freelancers e projetos.
  - Meta: Finalizar o ciclo de feedback e refinar a interface e usabilidade.

- **Iteração 4: Refinamentos e Testes**
  - Tarefas:
    - Testes de performance e segurança.
    - Refinar a interface de usuário (se aplicável) e corrigir bugs.
    - Documentação e preparação para o lançamento.
  - Meta: Garantir que o sistema esteja pronto para uso, com testes completos.
