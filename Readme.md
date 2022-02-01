# Azure Databricks Hands-on (Tutorials)

Follow each instructions on notebook below.

1. [Storage Settings](https://tsmatz.github.io/azure-databricks-exercise/exercise01-blob.html)
2. [Basics of Pyspark and Spark Machine Learning](https://tsmatz.github.io/azure-databricks-exercise/exercise02-pyspark-dataframe.html)
3. [Spark Machine Learning Pipeline](https://tsmatz.github.io/azure-databricks-exercise/exercise03-sparkml-pipeline.html)
4. [Hyper-parameter Tuning](https://tsmatz.github.io/azure-databricks-exercise/exercise04-hyperparams-tuning.html)
5. [MLeap](https://tsmatz.github.io/azure-databricks-exercise/exercise05-mleap.html) (requires ML runtime)
6. [Horovod Runner on Databricks Runtime for ML](https://tsmatz.github.io/azure-databricks-exercise/exercise06-horovod.html) (requires ML runtime)
7. [Structured Streaming (Basic)](https://tsmatz.github.io/azure-databricks-exercise/exercise07-structured-streaming.html)
8. [Structured Streaming with Azure EventHub or Kafka](https://tsmatz.github.io/azure-databricks-exercise/exercise08-streaming-eventhub.html)
9. [Delta Lake](https://tsmatz.github.io/azure-databricks-exercise/exercise09-databricks-delta.html)
10. [Work with MLFlow](https://tsmatz.github.io/azure-databricks-exercise/exercise10-mlflow.html) (requires ML runtime)
11. [Orchestration with Azure Data Services](https://tsmatz.github.io/azure-databricks-exercise/exercise11-orchestration.html)

## Before you start

- Create Azure Databricks resource in [Microsoft Azure](https://portal.azure.com/), and launch workspace.
- Create a computing cluster on Databricks workspace. (Select "Compute" in Workspace UI.)<br>
Databricks **Runtime Version 10.2 ML or above** is recommended for running this tutorial.
- Download [HandsOn.dbc](https://github.com/tsmatz/azure-databricks-exercise/raw/master/HandsOn.dbc) and import into your workspace.
    - Select "Workspace" in Workspace UI.
    - Go to user folder.
    - Click your e-mail (the arrow in the right side) and select "import" command to import HandsOn.dbc.
- Open the imported notebook and attach your cluster in the notebook. (Select cluster on top of notebook.)

> Note : You cannot use Azure Trial (Free) subscription, because of limited vCPU quota. Please promote to Pay-As-You-Go when you use trial subscription. (The credit will be reserved even when you transit to Pay-As-You-Go.)

*Tsuyoshi Matsuzaki @ Microsoft*
