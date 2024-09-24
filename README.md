# Formação Alura CI/CD

## Principais Tópicos a Dominar

- **Configuração de Pipelines**: Entenda o fluxo de CI/CD.
- **GitHub Actions**: Automatize tarefas como testes, builds e deploys.
- **Containers Docker**: Crie containers para rodar testes automaticamente.
- **Entrega Contínua**: Implemente utilizando serviços de cloud.

Ao final, terá um pipeline funcional de CI/CD, otimizando seus processos de desenvolvimento e entregando software com mais agilidade e confiabilidade.

## O que é Integração Contínua (Continuous Integration/CI)?

A Integração Contínua é uma prática de desenvolvimento de software onde os desenvolvedores frequentemente mesclam suas mudanças de código em um repositório central, seguido de builds e testes automatizados.

## O que é Entrega Contínua (Continuous Delivery/CD)?

A Entrega Contínua é uma extensão da Integração Contínua que garante que o código pode ser implantado em produção a qualquer momento, através de um pipeline automatizado.

## Como Integração Contínua e Entrega Contínua estão Ligadas?

A Integração Contínua e a Entrega Contínua trabalham juntas para automatizar e melhorar a qualidade do software. A CI se concentra na integração e teste contínuos, enquanto a CD se concentra na entrega contínua do software.

## Melhores Práticas para Implementar Pipelines de CI/CD

- **Automatize Tudo**: Automatize os processos de build, teste e deployment para garantir consistência e reduzir erros manuais.
- **Use Controle de Versão**: Armazene todo o código, incluindo infraestrutura e configuração, em um sistema de controle de versão como o Git.
- **Execute Testes Cedo e Frequentemente**: Integre testes unitários, de integração e outros testes automatizados no pipeline para detectar problemas o mais cedo possível.
- **Mantenha os Pipelines Rápidos**: Otimize o pipeline para rodar rapidamente. Use jobs paralelos e caching para acelerar o processo.
- **Falhe Rápido**: Configure o pipeline para falhar assim que um erro for detectado. Isso ajuda a identificar e corrigir problemas rapidamente.
- **Isole Ambientes**: Use diferentes ambientes (desenvolvimento, staging, produção) para testar mudanças isoladamente antes de implantar em produção.
- **Monitore e Registre**: Implemente monitoramento e logging para rastrear o desempenho e a saúde do pipeline e das aplicações implantadas.
- **Verificação de Segurança**: Integre verificações de segurança e escaneamento de vulnerabilidades no pipeline para garantir que o código e as dependências sejam seguros.
- **Mecanismo de Rollback**: Tenha um mecanismo de rollback para reverter para um estado estável anterior em caso de falhas de deployment.
- **Documentação**: Mantenha uma documentação clara para a configuração e os processos do pipeline para ajudar os membros da equipe a entender e gerenciar o pipeline de forma eficaz.

