# Criando e Configurando um Modelo de Previsão no Azure

Este guia fornecerá instruções detalhadas sobre como criar e configurar um modelo de previsão utilizando o Azure Machine Learning Services. O Azure oferece uma variedade de ferramentas e serviços para desenvolver, treinar e implantar modelos de machine learning de maneira eficiente.

## Pré-requisitos

- Uma conta no Microsoft Azure. Se você não tem uma, pode criar uma em [azure.microsoft.com](https://azure.microsoft.com/).
- Conhecimento básico de machine learning e Azure.

## Passo 1: Criando um Workspace no Azure Machine Learning

1. Acesse o Portal do Azure e faça login na sua conta.
2. No painel esquerdo, selecione "Machine Learning".
3. Clique em "Create a resource" e procure por "Machine Learning".
4. Selecione "Machine Learning" e clique em "Create".
5. Preencha os detalhes necessários, como nome, assinatura, grupo de recursos, etc., e clique em "Review + create".
6. Revise as configurações e clique em "Create" para criar o workspace.

## Passo 2: Desenvolvendo e Treinando o Modelo

1. Desenvolva seu modelo de previsão utilizando uma biblioteca de machine learning.
2. Divida seus dados em conjuntos de treinamento e teste.
3. Utilize o SDK do Azure Machine Learning para definir e executar experimentos, registrando métricas e artefatos do modelo.

## Passo 3: Configurando os Pontos de Extremidade (Endpoints)

1. Após treinar e registrar seu modelo no Azure Machine Learning, você pode implantá-lo como um serviço web.
2. No Azure Machine Learning Studio, navegue até o modelo que deseja implantar.
3. Selecione "Deploy" e escolha o método de implantação adequado (ACI - Azure Container Instances ou AKS - Azure Kubernetes Service).
4. Siga as instruções para configurar as opções de implantação, como nome, tipo de serviço, número de instâncias, etc.
5. Depois que o serviço web estiver implantado com sucesso, você receberá os pontos de extremidade (endpoints) para acessar o seu modelo.

## Passo 4: Testando o Modelo

1. Utilize ferramentas como o Postman ou escreva código para enviar requisições HTTP para o ponto de extremidade do serviço web.
2. Envie dados de teste para o ponto de extremidade e receba as previsões do modelo.

## Considerações Finais

Seguindo este guia, você poderá criar, treinar, implantar e testar um modelo de previsão utilizando o Azure Machine Learning Services. Lembre-se de revisar regularmente e atualizar sua documentação conforme necessário para garantir que ela permaneça útil e precisa.


## Endpoints
Test:


## Metrics
https://portal.azure.com/#@smouragandraoutlook.onmicrosoft.com/blade/Microsoft_Azure_MonitoringMetrics/Metrics.ReactView/Referer/MetricsExplorer/ResourceId/%2Fsubscriptions%2F51ddfe21-58f6-426e-8276-4b032de55772%2FresourceGroups%2Flabai-900%2Fproviders%2FMicrosoft.MachineLearningServices%2Fworkspaces%2FLaboratorioAI900%2FonlineEndpoints%2Flaboratorioai900-zkzbb/TimeContext/%7B%22relative%22%3A%7B%22duration%22%3A86400000%7D%2C%22showUTCTime%22%3Afalse%2C%22grain%22%3A1%7D/ChartDefinition/%7B%22v2charts%22%3A%5B%7B%22metrics%22%3A%5B%5D%2C%22title%22%3A%22%22%2C%22titleKind%22%3A1%2C%22visualization%22%3A%7B%22chartType%22%3A2%2C%22legendVisualization%22%3A%7B%22isVisible%22%3Atrue%2C%22position%22%3A2%2C%22hideHoverCard%22%3Afalse%2C%22hideLabelNames%22%3Afalse%7D%2C%22axisVisualization%22%3A%7B%22x%22%3A%7B%22isVisible%22%3Atrue%2C%22axisType%22%3A2%7D%2C%22y%22%3A%7B%22isVisible%22%3Atrue%2C%22axisType%22%3A1%7D%7D%7D%7D%5D%7D


