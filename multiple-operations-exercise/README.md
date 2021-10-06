# Parameterized pipeline arithmetic operation exercise

This exercise has two parts.

1. Creating and executing the pipeline that adds two numbers using **pipeline variables**
2. Executing the pipeline template using **template parameters**

## Pipeline execution

In order to run the pipelines, please click the pipelines icon in the azure devops project space.

<img src='https://azurecomcdn.azureedge.net/cvt-29bb5b361a30509ed9e5daf51ad1318c032a10805d9ab60ea21edf9042d6f872/images/shared/services/devops/pipelines-icon-80.png' width='50px' height='50px' />

Next, click the **New Pipeline** button and enter the following details when prompted.

- Where is your code: Azure Repos Git
- Select the repository: <THE-NAME-OF-YOUR-REPOSITORY>
- Configure your pipeline: Existing azure pipelines YAML file
- Select the appropriate pipeline from the list
  - _Add two numbers pipeline_: `/multiple-operations-exercise/multiple-operations.yaml`
  - _Add two numbers using pipeline template_: `/multiple-operations-exercise/multiple-operations-templated.yaml`
- Click on **Continue**
- Click on **Run**
