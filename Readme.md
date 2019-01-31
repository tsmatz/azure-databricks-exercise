# Spark Machine Learning Exercise for Beginners on Azure Databricks

Please download [HandsOn.dbc](https://github.com/tsmatz/azure-databricks-exercise/raw/master/HandsOn.dbc) and import into your workspace on Azure Databricks.　　　　
This sample requires Databricks Runtime **Version 5.1** (includes Spark 2.4.0, Scala 2.11) or above. Both Exercise 05 and Exercise 06 require Runtime **Version 5.1 ML Beta** or above.

- Azure Data Lake Storage Gen2 requires Databricks Runtime 4.2 or above
- Azure Data Lake Storage Gen2 mount points require Databricks Runtime 5.1 or above

Moreover you needs **Premium** tier for runtime to run Exercise 09 (Databricks Delta). (Otherwise you can use Standard tier.)

Follow each instructions on notebook below.

1. [Exercise 01 : Storage Settings](https://databricks-hol.azurewebsites.net/basics/exercise01-blob.html)
2. [Basics of Pyspark and Spark Machine Learning](https://databricks-hol.azurewebsites.net/basics/exercise02-pyspark-dataframe.html)
3. [Spark Machine Learning Pipeline](https://databricks-hol.azurewebsites.net/basics/exercise03-sparkml-pipeline.html)
4. [Hyper-parameter Tuning](https://databricks-hol.azurewebsites.net/basics/exercise04-hyperparams-tuning.html)
5. [MLeap (needs ML runtime)](https://databricks-hol.azurewebsites.net/basics/exercise05-mleap.html)
6. [Horovod Estimator on Databricks Runtime for ML (needs ML runtime)](https://databricks-hol.azurewebsites.net/basics/exercise06-horovod-estimator.html)
7. [Structured Streaming](https://databricks-hol.azurewebsites.net/basics/exercise07-structured-streaming.html)
8. [Structured Streaming with Azure EventHub or Kafka](https://databricks-hol.azurewebsites.net/basics/exercise08-streaming-eventhub.html)
9. [Databricks Delta](https://databricks-hol.azurewebsites.net/basics/exercise09-databricks-delta.html)
10. [Work with MLFlow](https://databricks-hol.azurewebsites.net/basics/exercise10-mlflow.html)

This sample worked on Databricks Runtime Version 5.1 and 5.1 ML Beta.

*Tsuyoshi Matsuzaki @ Microsoft*
