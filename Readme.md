# Azure Databricks Hands-on Exercise

Please download [HandsOn.dbc](https://github.com/tsmatz/azure-databricks-exercise/raw/master/HandsOn.dbc) and import into your workspace on Azure Databricks.<br>
Create a cluster on Azure Databricks.

Currently, Databricks **Runtime Version 6.6 ML** is recommended for running this tutorial.<br>
Because,
- You cannot run Exercise 03, Exercise 04, Exercise 05 and Exercise 10 on Runtime Version 7.0 (including Spark 3.0) or above.
- Both Exercise 05 and Exercise 06 require Runtime Version 5.1 ML or above.
- Exercise 10 (MLFlow) requires Runtime Version 5.4 or above.
- Others require Databricks Runtime Version 5.1 (including Spark 2.4.0, Scala 2.11) or above.

Follow each instructions on notebook below.

1. [Storage Settings](https://tsmatz.github.io/azure-databricks-exercise/exercise01-blob.html)
2. [Basics of Pyspark and Spark Machine Learning](https://tsmatz.github.io/azure-databricks-exercise/exercise02-pyspark-dataframe.html)
3. [Spark Machine Learning Pipeline](https://tsmatz.github.io/azure-databricks-exercise/exercise03-sparkml-pipeline.html)
4. [Hyper-parameter Tuning](https://tsmatz.github.io/azure-databricks-exercise/exercise04-hyperparams-tuning.html)
5. [MLeap](https://tsmatz.github.io/azure-databricks-exercise/exercise05-mleap.html) (needs ML runtime)
6. [Horovod Estimator on Databricks Runtime for ML](https://tsmatz.github.io/azure-databricks-exercise/exercise06-horovod-estimator.html) (needs ML runtime)
7. [Structured Streaming](https://tsmatz.github.io/azure-databricks-exercise/exercise07-structured-streaming.html)
8. [Structured Streaming with Azure EventHub or Kafka](https://tsmatz.github.io/azure-databricks-exercise/exercise08-streaming-eventhub.html)
9. [Delta Lake](https://tsmatz.github.io/azure-databricks-exercise/exercise09-databricks-delta.html)
10. [Work with MLFlow](https://tsmatz.github.io/azure-databricks-exercise/exercise10-mlflow.html)
11. [Orchestration with Azure Data Services](https://tsmatz.github.io/azure-databricks-exercise/exercise11-orchestration.html)

> Note : You cannot use Azure Trial (Free) subscription, because of limited vCPU quota. Please promote to Pay-As-You-Go. (The credit is reserved even when you transition to Pay-As-You-Go.)

*Tsuyoshi Matsuzaki @ Microsoft*
