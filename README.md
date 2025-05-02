# AzureDevOps-Popeye-Kubernetes-kind
Pipeline do Azure DevOps demonstrando o uso da ferramenta Popeye no scan de vulnerabilidades em cluster Kubernetes gerado via utilitário kind. Inclui geração de relatório em HTML e no padrão JUnit (.xml).

Links importantes:
* Projeto Popeye: https://github.com/derailed/popeye
* kind (emulador Kubernetes): https://kind.sigs.k8s.io/

Aproveito este espaço para agradecer a meu amigo Daniel Dias Assumpção - @dassump - pela indicação desta excelente ferramenta (Popeye).

## Resultados

Utilitário Popeye executado gerando o resultado da análise em stdout:

![Popeye stdout 01](img/popeye-01.png)

![Popeye stdout 02](img/popeye-01.png)

Relatório HTML gerado como resultado de uma análise com o Popeye:

![Popeye Azure Pipelines 01](img/popeye-03.png)

![Popeye Azure Pipelines 02](img/popeye-04.png)