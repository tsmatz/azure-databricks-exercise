# Azure Databricks Hands-on (Tutorials)

To run these exercises, follow each instructions below in this readme.

1. [Storage Settings](https://tsmatz.github.io/azure-databricks-exercise/exercise01-blob.html)
2. [Basics of PySpark, Spark Dataframe, and Spark Machine Learning](https://tsmatz.github.io/azure-databricks-exercise/exercise02-pyspark-dataframe.html)
3. [Data Transformation and Spark ML Pipeline](https://tsmatz.github.io/azure-databricks-exercise/exercise03-sparkml-pipeline.html)
4. [Hyper-parameter Tuning](https://tsmatz.github.io/azure-databricks-exercise/exercise04-hyperparams-tuning.html)
5. [MLeap](https://tsmatz.github.io/azure-databricks-exercise/exercise05-mleap.html) (requires ML runtime)
6. [Spark PyTorch Distributor](https://tsmatz.github.io/azure-databricks-exercise/exercise06-dnn-distributor.html) (requires ML runtime)
7. [Structured Streaming (Basic)](https://tsmatz.github.io/azure-databricks-exercise/exercise07-structured-streaming.html)
8. [Structured Streaming with Azure Event Hubs or Kafka](https://tsmatz.github.io/azure-databricks-exercise/exercise08-streaming-eventhub.html)
9. [Delta Lake](https://tsmatz.github.io/azure-databricks-exercise/exercise09-databricks-delta.html)
10. [MLflow](https://tsmatz.github.io/azure-databricks-exercise/exercise10-mlflow.html) (requires ML runtime)
11. [Orchestration with Azure Data Services](https://tsmatz.github.io/azure-databricks-exercise/exercise11-orchestration.html)
12. [Lakeflow Spark Declarative Pipelines](https://tsmatz.github.io/azure-databricks-exercise/exercise12-dlt.html)
13. [Databricks SQL](https://tsmatz.github.io/azure-databricks-exercise/exercise13-sql.html)

These exercises focus only on essential working with data and primitive ML features - not including generative AI features, such as, building AI agents, AI functions, fine-tuning foundation models, etc. (First commit: Oct 2018)

## Getting Started

- Create Azure Databricks resource in [Microsoft Azure](https://portal.azure.com/).<br>
(Select premium plan, not standard. Select hybrid type, not serverless.)
- After the resource is created, launch Databricks workspace UI by clicking "Launch Workspace".
- Create a compute (cluster) in Databricks UI. (Select "Compute" menu and proceed to create.)<br>
Enable "machine learning" to create ML runtime.
- Clone this repository. (Or download [HandsOn.dbc](https://github.com/tsmatz/azure-databricks-exercise/raw/master/HandsOn.dbc).)<br>
```git clone https://github.com/tsmatz/azure-databricks-exercise```
- Import ```HandsOn.dbc``` into your Databricks workspace as follows.
    - Select "Workspace" in Workspace UI.
    - Go to your user folder, and then select "Import".
    - Pick up ```HandsOn.dbc``` and submit import.
- Open the imported notebooks and attach above compute (cluster) in every notebooks. (Select compute (cluster) on the top of notebook.)
- Please make sure to run "Exercise 01 : Storage Settings (Prepare)", before running other notebooks.

> Note : This requires classic compute culster, and you cannot use Azure trial (free) subscription, because of the limited quota. When you're in Azure free subscription, please promote to pay-as-you-go. (The credit in free subscription will be reserved, even when you transit to pay-as-you-go.)<br>
> Throughout exercises in this repository, we mostly use All-purpose compute as cluster for experimentation purpose, but please create a Job and use Job compute for production. (All-purpose compute is more expensive than Job compute.)

*Tsuyoshi Matsuzaki @ Microsoft Asia*
