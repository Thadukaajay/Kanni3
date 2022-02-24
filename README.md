# Function App Deployment (.NET 6)

This is a sample repository to demonstrate how a .NET 6 Function App can be deployed to Azure using GitHub Actions.

The [`infrastructure.yml`](.github/workflows/infrastructure.yml) workflow creates/updates the Azure resources.

The [`application.yml`](.github/workflows/application.yml) workflow packages and deploys the Function App project.

This repo and its files are used in the [**Azure Functions University** *Deployment lesson (.NET 6)*](https://github.com/marcduiker/azure-functions-university/blob/main/lessons/dotnet6/deployment/).

## Status

![infrastructure](https://github.com/marcduiker/functionapp-deployment-dotnet6/workflows/infrastructure/badge.svg)

![application](https://github.com/marcduiker/functionapp-deployment-dotnet6/workflows/application/badge.svg)