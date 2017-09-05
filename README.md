# KuduPyspark
Sample Code to get started with KuduPyspark

Instructions:
- The latest JAR file for Kudu-Spark can be downloaded from the link Maven Website
- The Jar file used for this program is downloaded from 
For pyspark:
https://repository.cloudera.com/content/repositories/releases/org/apache/kudu/kudu-spark_2.10/1.2.0-cdh5.10.0/kudu-spark_2.10-1.2.0-cdh5.10.0.jar
For pyspark2:
https://repository.cloudera.com/content/repositories/releases/org/apache/kudu/kudu-spark2_2.11/1.2.0-cdh5.10.2/kudu-spark2_2.11-1.2.0-cdh5.10.2.jar
- Running instructions
  - pyspark shell:
    $ pyspark2 --jars PATH_TO_JAR
  - Spark submit
    spark-submit --jars PATH_TO_JAR pyspark-kudu_application_path.py
    spark2-submit --jars PATH_TO_JAR pyspark-kudu_application_path.py
