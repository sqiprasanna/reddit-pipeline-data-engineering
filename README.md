pip install apache-airflow pandas numpy praw

mkdir config dags data etls logs pipelines tests utils

touch airflow.env docker-compose.yaml Dockerfile

pip freeze > requirements.txt

Fill Dockerfile, docker-compose.yml, airflow.env contents

docker compose up -d --build


### DAGs
* create a DAG using airflow and reddit pipeline initiation

### Piplines
* create a reddit_pipline function where we connect to reddit instance and perform ETL 

### Config
* database, filepaths, api_keys, aws access keys, etl settings written in config.conf file


### utils
* retrieve all the keys, secrets into constants.py

### ETLS
* connect to reddit using praw

add all the code-> Create DAG-> reddit pipeline (ETL)->connect to reddit using praw-> ETL posts from reddit-> constants for storing usernames& Passwords


docker compose up -d --build

open - http://localhost:8080/

airflow users create --username admin --firstname admin --lastname admin --role Admin --email airflow@airflow.com --password admin



Reddit, Airflow, Celery, Postgres, S3, AWS Glue, Athena, and Redshift to create a seamless ETL process. 
