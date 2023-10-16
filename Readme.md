# Azure Databricks Hands-on (Tutorials)

To run these exercises, follow each instructions below in this readme.

1. [Storage Settings](https://tsmatz.github.io/azure-databricks-exercise/exercise01-blob.html)
2. [Basics of PySpark, Spark Dataframe, and Spark Machine Learning](https://tsmatz.github.io/azure-databricks-exercise/exercise02-pyspark-dataframe.html)
3. [Spark Machine Learning Pipeline](https://tsmatz.github.io/azure-databricks-exercise/exercise03-sparkml-pipeline.html)
4. [Hyper-parameter Tuning](https://tsmatz.github.io/azure-databricks-exercise/exercise04-hyperparams-tuning.html)
5. [MLeap](https://tsmatz.github.io/azure-databricks-exercise/exercise05-mleap.html) (requires ML runtime)
6. [Spark PyTorch Distributor](https://tsmatz.github.io/azure-databricks-exercise/exercise06-dnn-distributor.html) (requires ML runtime)
7. [Structured Streaming (Basic)](https://tsmatz.github.io/azure-databricks-exercise/exercise07-structured-streaming.html)
8. [Structured Streaming with Azure Event Hubs or Kafka](https://tsmatz.github.io/azure-databricks-exercise/exercise08-streaming-eventhub.html)
9. [Delta Lake](https://tsmatz.github.io/azure-databricks-exercise/exercise09-databricks-delta.html)
10. [MLflow](https://tsmatz.github.io/azure-databricks-exercise/exercise10-mlflow.html) (requires ML runtime)
11. [Orchestration with Azure Data Services](https://tsmatz.github.io/azure-databricks-exercise/exercise11-orchestration.html)
12. [Delta Live Tables](https://tsmatz.github.io/azure-databricks-exercise/exercise12-dlt.html)
13. [Databricks SQL](https://tsmatz.github.io/azure-databricks-exercise/exercise13-sql.html)

## Getting Started

- Create Azure Databricks resource in [Microsoft Azure](https://portal.azure.com/).<br>
When you create a resource, please select Premium plan.
- After the resource is created, launch Databricks workspace UI by clicking "Launch Workspace".
- Create a compute (cluster) in Databricks UI. (Select "Compute" menu and proceed to create.)<br>
Please select runtime in ML (not a standard runtime).
- Clone this repository by running the following command. (Or download [HandsOn.dbc](https://github.com/tsmatz/azure-databricks-exercise/raw/master/HandsOn.dbc).)<br>
```git clone https://github.com/tsmatz/azure-databricks-exercise```
- Import ```HandsOn.dbc``` into your Databricks workspace as follows.
    - Select "Workspace" in Workspace UI.
    - Go to user folder, click your e-mail (the arrow icon), and then select "import".
    - Pick up ```HandsOn.dbc```.
- Open the imported notebooks and attach above compute (cluster) in every notebooks. (Select compute (cluster) on the top of notebook.)
- Please make sure to run "Exercise 01 : Storage Settings (Prepare)", before running other notebooks.

> Note : You cannot use Azure trial (free) subscription, because of the limited quota. When you're in Azure free subscription, please promote to pay-as-you-go. (The credit in free subscription will be reserved, even when you transit to pay-as-you-go.)

*Tsuyoshi Matsuzaki @ Microsoft*
