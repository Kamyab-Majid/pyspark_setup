conda create -n pyspark_env python  
conda install cyclus::java-jdk
conda install conda-forge::pyspark 
conda env config vars set PYSPARK_PYTHON=python SPARK_HOME=C:/Users/Adriy/anaconda3/envs/pyspark_env/Lib/site-packages/pyspark JAVA_HOME="C:\Users\Adriy\anaconda3\envs\pyspark_env\Library\jre\" HADOOP_HOME="C:\Users\Adriy\OneDrive\Desktop\repos\winutils\hadoop-3.0.0" SPARK_LOCAL_HOSTNAME=localhost