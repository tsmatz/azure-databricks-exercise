# Azure Databricks Hands-on Exercise

Please download [HandsOn.dbc](https://github.com/tsmatz/azure-databricks-exercise/raw/master/HandsOn.dbc) and import into your workspace on Azure Databricks.

Both Exercise 05 and Exercise 06 require Runtime **Version 5.1 ML** or above.    
Exercise 09 (Databricks Delta) requires **Premium** tier. (Otherwise you can use Standard tier.)    
Exercise 10 (MLFlow) requires Runtime **Version 5.4** or above.    
Others require Databricks Runtime **Version 5.1** (includes Spark 2.4.0, Scala 2.11) or above.

Follow each instructions on notebook below.

1. [Storage Settings](https://tsmatz.github.io/azure-databricks-exercise/exercise01-blob.html)
2. [Basics of Pyspark and Spark Machine Learning](https://tsmatz.github.io/azure-databricks-exercise/exercise02-pyspark-dataframe.html)
3. [Spark Machine Learning Pipeline](https://tsmatz.github.io/azure-databricks-exercise/exercise03-sparkml-pipeline.html)
4. [Hyper-parameter Tuning](https://tsmatz.github.io/azure-databricks-exercise/exercise04-hyperparams-tuning.html)
5. [MLeap](https://tsmatz.github.io/azure-databricks-exercise/exercise05-mleap.html) (needs ML runtime)
6. [Horovod Estimator on Databricks Runtime for ML](https://tsmatz.github.io/azure-databricks-exercise/exercise06-horovod-estimator.html) (needs ML runtime)
7. [Structured Streaming](https://tsmatz.github.io/azure-databricks-exercise/exercise07-structured-streaming.html)
8. [Structured Streaming with Azure EventHub or Kafka](https://tsmatz.github.io/azure-databricks-exercise/exercise08-streaming-eventhub.html)
9. [Databricks Delta](https://tsmatz.github.io/azure-databricks-exercise/exercise09-databricks-delta.html)
10. [Work with MLFlow](https://tsmatz.github.io/azure-databricks-exercise/exercise10-mlflow.html)
11. [Orchestration with Azure Data Services](https://tsmatz.github.io/azure-databricks-exercise/exercise11-orchestration.html)

This sample worked on Databricks Runtime Version 5.4 ML.

Note : When you're using Azure Trial (Free) subscription, you cannot run your cluster (because of limited vCPU quota). Please promote to Pay-As-You-Go. (The credit is reserved even when using Pay-As-You-Go.)

*Tsuyoshi Matsuzaki @ Microsoft*
