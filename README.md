# hadoop-spark-airflow

1. run `bash run.sh` on terminal to build docker images & container
2. copy Sales.csv from `hadoop-data/input/Sales.csv` into `input/`
    - run `docker exec -it namenode /bin/bash` to acces docker namenode
    - copy file `hdfs dfs -put /hadoop-data/input/Sales.csv input/`
![access-namenode](https://github.com/abdurrahmanshidiq/hadoop-spark-airflow/blob/master/img/access-namenode.png "access-namenode")<br>
3. open `http://localhost:8080` to access airflow Web UI then play / trigger the dag
4. your pipeline is run
![airflow-ui](https://github.com/abdurrahmanshidiq/hadoop-spark-airflow/blob/master/img/airflow-ui.png "airflow-ui")<br>
