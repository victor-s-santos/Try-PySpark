# Spark with PySpark

# How to
* ## 1 Install Spark
    * 1.1 Download Spark
        - wget https://dlcdn.apache.org/spark/spark-3.3.2/spark-3.3.2-bin-hadoop3.tgz
    
    * 1.2 Unpact downloaded file 
        - tar xvf spark-3.3.2-bin-hadoop3.tgz
    
    * 1.3 Move to /opt/
        - sudo mv spark-3.3.2-bin-hadoop3/ /opt/spark/spark-3.3.2-bin-hadoop3

* ## 2 Set env config
    * 2.1 Add the spark_env.sh file content in end of ~/.bashrc
    * 2.2 Reload ~/.bashrc:
        - source ~/.bashrc
    - Obs: You are going to need the seconde step just once.

* ## 3 Create the jupyter notebook
    * 3.1 Create the virtualenv
        - python -m venv .venv
        - source .venv/bin/activate
    
    * 3.2 Install dependencies

* ## 4 Up jupyter notebook
    * 4.1 Up the jupyter notebook
        - jupyter notebook
    
    * 4.2 Access the browser
        -  http://localhost:8888/tree