# spark_practice
1. OS: Ubuntu 19.04, requirement software: spark 2.4.3, python3.7.3, jupyter notebook

2. required python packages: requirements.txt

   $ pip install -r requirements.txt

3. edit $~/.bashrc file as below

   export PATH=$SPARK_HOME/bin:$PATH

   export PYSPARK_PYTHON=python3

   export PYSPARK_DRIVER_PYTHON=jupyter

   export PYSPARK_DRIVER_PYTHON_OPTS='notebook'

4. execute pyspark

   $ pyspark


## About Data directory
We use 'data' directory in spark distribution source file.

It needs to adjust actual 'data' directory path in example codes.

