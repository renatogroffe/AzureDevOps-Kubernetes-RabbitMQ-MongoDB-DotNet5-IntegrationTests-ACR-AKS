# AzureDevOps-Kubernetes-RabbitMQ-MongoDB-DotNet5-IntegrationTests-ACR-AKS
Pipeline do Azure DevOps para execução automatizada de testes de integração (baseados em .NET 5 e no uso de RabbitMQ + MongoDB), build e deployment de uma aplicação que faz uso de containers com publicação de imagens no Azure Container Registry e deployment no AKS - Azure Kubernetes Service (inclui ainda o uso de Variables, além de um Secret no Kubernetes).

Projeto que serviu de base para elaboração deste Pipeline:

https://github.com/renatogroffe/DotNet5-WorkerService-RabbitMQ-MongoDB-IntegrationTests_Acoes

Projeto para envio de mensagens à aplicação de processamento:

https://github.com/renatogroffe/ASPNETCore5-MongoDB-RabbitMQ_APIAcoes