# Sistema de Gestão de Freelancers

## Visão do Projeto

### Objetivo do Projeto

O sistema de gestão de freelancers tem como principal objetivo proporcionar uma plataforma para conectar freelancers e clientes, permitindo o gerenciamento eficiente de projetos, candidaturas e pagamentos. Além disso, este projeto será uma oportunidade prática para aprender e consolidar o conhecimento na linguagem Node.js e no framework Express, aplicando conceitos fundamentais de desenvolvimento backend.

Este projeto também faz parte da disciplina de Testes Automatizados, tendo como objetivo aplicar metodologias de testes unitários, de integração e de performance. A implementação de um conjunto robusto de testes automatizados garantirá a qualidade e a estabilidade do sistema, além de demonstrar boas práticas de desenvolvimento orientadas à qualidade do software.

Portanto, além de cumprir sua finalidade prática de conectar freelancers e clientes, o projeto será uma oportunidade para explorar:

- O aprendizado de Node.js e desenvolvimento backend com Express.
- A implementação de testes automatizados para garantir a funcionalidade, segurança e performance do sistema.
- O uso de ferramentas de teste como Jest, Postman, e Selenium, com foco em garantir a confiabilidade do sistema.

### Público-Alvo

**Freelancers:** Profissionais independentes que oferecem serviços em diversas áreas, como desenvolvimento de software, design gráfico, redação, marketing, entre outros.

**Clientes (Contratantes):** Empresas ou indivíduos que precisam de serviços especializados de freelancers e querem um local seguro e confiável para encontrar profissionais.

### Problemas que Resolve

- Dificuldade em encontrar freelancers qualificados para projetos específicos.
- Gestão ineficiente de contratos e pagamentos de freelancers.
- Falta de um meio seguro para avaliação, feedback e suporte no ciclo de trabalho.

## Visão Geral do Sistema

O sistema permitirá que freelancers criem perfis, se candidatem a projetos e gerenciem seus contratos de forma segura.
Clientes poderão postar projetos, escolher freelancers e acompanhar o progresso do trabalho.
A plataforma também integrará sistemas de pagamento seguros, permitindo que clientes paguem freelancers conforme a conclusão de marcos do projeto.

## Requisitos Funcionais

Autenticação de usuários (clientes e freelancers) com permissões baseadas em perfis.
Cadastro de projetos pelos clientes, incluindo descrição, prazo e orçamento.
Sistema de candidaturas: freelancers podem se candidatar a projetos com propostas.
Sistema de avaliação e feedback após a conclusão dos projetos.
Pagamentos escalonados por marcos do projeto, integrados a serviços de pagamento como Stripe ou PayPal.

## Requisitos Funcionais Detalhados

### Autenticação e Perfis:

Login e registro de usuários (freelancers e clientes) com permissões específicas.
Edição de perfil, permitindo freelancers adicionarem habilidades e clientes adicionarem detalhes da empresa.
Gerenciamento de Projetos:

Clientes podem criar, editar e excluir projetos.
Freelancers podem se candidatar a projetos com propostas (orçamento e cronograma).
Clientes podem aceitar ou rejeitar candidaturas.

### Sistema de Pagamento:

Pagamento por marco: o cliente pode pagar os freelancers conforme a entrega de partes específicas do projeto.
Integração com gateways como Stripe ou PayPal.

### Avaliações:

Clientes e freelancers podem se avaliar mutuamente após a conclusão de um projeto, criando um sistema de reputação.

### Notificações:

Notificações por e-mail para candidaturas, aceitação de projetos e conclusão de marcos.

## Requisitos Não Funcionais

### Segurança:

Uso de HTTPS, criptografia de senhas (bcrypt), proteção contra ataques comuns como CSRF e XSS.

### Escalabilidade:

Suporte para muitos usuários simultâneos sem degradação da performance.

### Performance:

Respostas rápidas às requisições, mesmo sob alta carga.
