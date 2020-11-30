# Airflow Sandbox

To run, 
```
export AIRFLOW_HOME=~/Sandbox/airflow-sandbox
airflow initdb
airflow webserver -p 8080
airflow scheduler

Visit localhost:8080 to see Airflow UI
```