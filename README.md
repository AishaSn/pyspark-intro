# pyspark-intro
PySpark is the Python API for Apache Spark, allowing Python developers to harness the power of Spark for big data processing and analytics. Because Python has been one of the most popular programming languages; especially in the data science and machine learning communities. PySpark allows Python developers to work with Spark using familiar syntax and libraries.
# Guidance to go through PySpark
Ensuring Python is installed and is verifiable throught PATH - python--version. If this fails, Download and install from https://www.python.org/downloads/.

Sparks runs on the JVM - java--version. If this fails, Download and install JDV from https://www.oracle.org/java/technologies/downloads

Spark download and install from https://www.spark.apache.org/downloads.html. Set SPARK HOME in the env variables.

 Hadoop - 
 
 • Create a hadoop folder and create a bin folder inside it.
 
 • Download winutils file from: https://github.com/steveloughran/winutils and put in bin folder.
 
 • Set HADOOP_HOME path into the env variables.
 
 pip check the avaliability of pip - pip--version.
 pip list- show installed packages.
 pip install <package>- install a package.
 pip uninstall <package>- remove a package.
 pip install--upgrade <package>- update a package.
 pip install pyspark.
 
 Jupyter Notebook - pip install jupyterlab notebook. pip install findspark
 
 Launch using the command pyspark in terminal. Save Spark code in ‘.py‘ files and run using: spark-submit myscript.py
