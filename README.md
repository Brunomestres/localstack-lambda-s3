## Aprendizados e Insights

Durante este laboratório, aprendi como integrar o Amazon S3 com o AWS Lambda para criar fluxos automatizados baseados em eventos. Com essa abordagem, ações podem ser executadas automaticamente sempre que um arquivo é enviado, removido ou modificado em um bucket.

Também entendi melhor o conceito de computação serverless, onde não é necessário gerenciar servidores para executar tarefas específicas. O AWS Lambda permite focar apenas na lógica da aplicação, enquanto a AWS cuida da infraestrutura necessária para a execução.

Outro aprendizado importante foi a utilização do LocalStack para simular serviços da AWS localmente. Essa ferramenta possibilita desenvolver, testar e validar aplicações sem a necessidade de utilizar recursos reais da nuvem durante as fases iniciais do desenvolvimento, tornando o processo mais rápido e econômico.

A integração entre Lambda, S3 e LocalStack demonstrou como é possível construir e testar soluções escaláveis baseadas em eventos antes mesmo de realizar o deploy na AWS.

### Insights Obtidos

* Nem toda automação exige servidores dedicados; funções serverless podem executar tarefas sob demanda de forma eficiente.
* O Amazon S3 não é apenas um serviço de armazenamento, mas também pode atuar como gatilho para diversos processos automatizados.
* A arquitetura orientada a eventos permite criar aplicações mais desacopladas e flexíveis.
* O uso do Lambda ajuda a reduzir custos, já que a cobrança ocorre apenas durante a execução das funções.
* Pequenas automações podem eliminar tarefas manuais repetitivas e tornar processos mais confiáveis.
* A combinação de S3 e Lambda é uma solução simples e poderosa para processamento automático de arquivos.
* O LocalStack facilita o aprendizado e os testes de serviços AWS sem gerar custos durante o desenvolvimento.
* Simular a infraestrutura localmente permite identificar problemas mais cedo e acelerar o ciclo de desenvolvimento.
* O modelo serverless facilita a escalabilidade da aplicação sem a necessidade de configurar ou administrar servidores.
