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
10. [MLflow](https://tsmatz.github.io/azure-databricks-exercise/exercise10-mlflow.html) (requires ML runtime)
11. [Orchestration with Azure Data Services](https://tsmatz.github.io/azure-databricks-exercise/exercise11-orchestration.html)
12. [Delta Live Tables](https://tsmatz.github.io/azure-databricks-exercise/exercise12-dlt.html)

## How to start

- Create Azure Databricks resource in [Microsoft Azure](https://portal.azure.com/).<br>
  After the resource is created, launch Databricks workspace UI by clicking "Launch Workspace".
- Create a compute (cluster) in Databricks UI. (Select "Compute" menu and proceed.)<br>
Databricks **Runtime Version 10.2 ML or above** is recommended for this tutorial.
- Download [HandsOn.dbc](https://github.com/tsmatz/azure-databricks-exercise/raw/master/HandsOn.dbc) and import into your workspace as follows.
    - Select "Workspace" in Workspace UI.
    - Go to user folder, click your e-mail (the arrow icon), and then select "import" command.
    - Pick up ```HandsOn.dbc``` to import.
- Open notebook and attach above compute (your cluster) in every notebook. (Select compute on the top of each notebook.)
- Please run "Exercise 01 : Storage Settings (Prepare)" notebook first, before running other notebooks.

> Note : You cannot use Azure trial (free) subscription, because of the limited quota. Please promote to pay-as-you-go when you're in Azure free subscription. (The credit will be reserved, even when you transit to pay-as-you-go.)

*Tsuyoshi Matsuzaki @ Microsoft*
