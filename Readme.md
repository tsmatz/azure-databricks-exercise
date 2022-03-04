# Azure Databricks Hands-on (Tutorials)

Follow each instructions on notebook below.

1. [Storage Settings](https://tsmatz.github.io/azure-databricks-exercise/exercise01-blob.html)
2. [Basics of PySpark, Spark Dataframe, and Spark Machine Learning](https://tsmatz.github.io/azure-databricks-exercise/exercise02-pyspark-dataframe.html)
3. [Spark Machine Learning Pipeline](https://tsmatz.github.io/azure-databricks-exercise/exercise03-sparkml-pipeline.html)
4. [Hyper-parameter Tuning](https://tsmatz.github.io/azure-databricks-exercise/exercise04-hyperparams-tuning.html)
5. [MLeap](https://tsmatz.github.io/azure-databricks-exercise/exercise05-mleap.html) (requires ML runtime)
6. [Horovod Runner on Databricks Runtime for ML](https://tsmatz.github.io/azure-databricks-exercise/exercise06-horovod.html) (requires ML runtime)
7. [Structured Streaming (Basic)](https://tsmatz.github.io/azure-databricks-exercise/exercise07-structured-streaming.html)
8. [Structured Streaming with Azure EventHub or Kafka](https://tsmatz.github.io/azure-databricks-exercise/exercise08-streaming-eventhub.html)
9. [Delta Lake](https://tsmatz.github.io/azure-databricks-exercise/exercise09-databricks-delta.html)
10. [MLFlow](https://tsmatz.github.io/azure-databricks-exercise/exercise10-mlflow.html) (requires ML runtime)
11. [Orchestration with Azure Data Services](https://tsmatz.github.io/azure-databricks-exercise/exercise11-orchestration.html)

## Before you start

- Create Azure Databricks resource in [Microsoft Azure](https://portal.azure.com/).<br>
  After the resource is created, launch Databricks workspace UI by clicking "Launch Workspace".
- Create a compute (computing cluster) in workspace UI. (Select "Compute" menu and proceed.)<br>
Databricks **Runtime Version 10.2 ML or above** is recommended for this tutorial.
- Download [HandsOn.dbc](https://github.com/tsmatz/azure-databricks-exercise/raw/master/HandsOn.dbc) in this repository and import into your workspace as follows.
    - Select "Workspace" in Workspace UI.
    - Go to user folder.<br>
      Click your e-mail (the arrow icon in the right side of e-mail) and select "import" command.
    - Pick up the downloaded ```HandsOn.dbc``` to import into your workspace.
- Open the imported notebooks and attach your cluster (your compute) in every notebook. (Select a cluster on top of each notebook.)

> Note : You cannot use Azure Trial (Free) subscription, because of the limited quota. Please promote to Pay-As-You-Go when you're in trial subscription. (The credit will be reserved even when you transit to Pay-As-You-Go.)

*Tsuyoshi Matsuzaki @ Microsoft*
