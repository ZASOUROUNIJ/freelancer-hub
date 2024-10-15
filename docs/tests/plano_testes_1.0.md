# Plano de Testes

## **Objetivo**

Garantir que todas as funcionalidades do sistema de gestão de freelancers funcionem corretamente e atendam às expectativas dos usuários finais. O plano de testes cobrirá aspectos de funcionalidade, segurança, desempenho e integração com serviços externos.

### Tipos de Testes

**Testes Unitários**: Verificar a funcionalidade de cada componente individual, como as rotas de criação de projeto, candidaturas, avaliação e pagamentos.

- **Ferramenta**: Jest.
- **Exemplo**: Testar o endpoint que permite a criação de projetos por clientes.

**Testes de Integração**: Validar que os diferentes módulos do sistema funcionam corretamente quando integrados.

- **Ferramenta**: Postman para testar APIs.
- **Exemplo**: Testar se um freelancer consegue se candidatar a um projeto e o cliente consegue aceitar essa candidatura.

**Testes de Interface de Usuário**: Validar se os componentes do frontend interagem corretamente com o backend.

- **Ferramenta**: Selenium.

**Testes de Segurança**: Simular ataques como injeção SQL, Cross-Site Scripting (XSS) e Cross-Site Request Forgery (CSRF) para garantir que o sistema seja seguro.

- **Ferramenta**: OWASP ZAP ou bibliotecas Node.js específicas.

**Testes de Performance**: Avaliar a capacidade do sistema de responder a múltiplas requisições simultâneas.

- **Ferramenta**: Artillery ou JMeter.
- **Exemplo**: Simular 1000 usuários criando projetos e freelancers se candidatando ao mesmo tempo.

## Casos de Testes

### Autenticação e Permissões:

- Testar login e registro de clientes e freelancers.

- Testar restrições de acesso (um freelancer não pode acessar funções de cliente e vice-versa).
  Fluxo de Criação e Gerenciamento de Projetos:

- Testar a criação de projetos pelos clientes.
- Testar a submissão de candidaturas pelos freelancers.
- Verificar a aceitação de candidaturas por parte do cliente.

### Sistema de Pagamentos:

- Verificar se o cliente pode fazer pagamentos conforme os marcos do projeto são concluídos.
- Testar integração com gateways de pagamento (simulações de Stripe ou PayPal).
