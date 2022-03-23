# Machine Learning

## Presentation
Follow [along](https://byui451.github.io/guide_machine_learning/#1)

## What is machine learning?
In simple terms, machine learning is a diverse set of tools that are used to understand data and it allows us to go further beyond summary statistics and basic analystics. To sum it up, machine learning learns from the data without being programmed. 

# Why Spark machine learning?
- Scale
  - Process more data than can fit in any one machine
  - More data == performant models
- Works with pre-existing pipelines and tools
  - Spark (streaming, ETL, ad hoc analysis, reporting)
  - Frameworks (sklearn, Tensorflow and Horovod, R)
  - Languages (Python, R, Scala, SQL, Java)
- Model training and production model serving   

## MLib
Databrick users are able to access the MLlib, or Spark's machine learning library, which makes machine learning scalabe and easy to implement . Tools avaiable for the library include

-ML Algorithms: common learning algorithms such as classification, regression, clustering, and collaborative filtering

-Featurization: feature extraction, transformation, dimensionality reduction, and selection

-Pipelines: tools for constructing, evaluating, and tuning ML Pipelines

-Persistence: saving and load algorithms, models, and Pipelines

-Utilities: linear algebra, statistics, data handling, etc.

## Two Type of MLib: (Both don't work as well for smaller datasets)

### MLib (RDD-based)
(https://databricks.com/glossary/what-is-rdd)

-RDD, Resilient Distributed Dataset, is a  collection of elements of data, partitioned across nodes that allows processes to be run in parallel.

-The dataframe structure in Spark ML allows for seamless translation to RDD's.

### MLib (Dataframe-based)

-Provide a more user-friendly API than RDDs

-Provides a uniform API across ML algorithms and across multiple languages.

## Additional Learning
[Machine Learning on Spark](https://adb-5187062830023627.7.azuredatabricks.net/?o=5187062830023627#notebook/2204255629165651/command/1092605121220237)
