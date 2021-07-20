# pipeline_flow



## MLFlow - questo mi piace in più con serveml si possonon servire i modelli con FastAPi,
ma non fa ETL solo hyperparameter tuning etc

- https://www.youtube.com/watch?v=OWJHHAtnAwY
- https://www.youtube.com/watch?v=M_CTgJcDkwg
- https://pypi.org/project/serveml/

## Airflow fa tutto, in più nella versione 2.0 ha lo swaggerUI di FastAPI integrato

mkdir airflow2
cd airflow2
wget https://github.com/visiont3lab/hello-world/blob/master/airflow2/docker-compose.yaml
code .
mkdir ./dags ./logs ./plugins
echo -e "AIRFLOW_UID=$(id -u)\nAIRFLOW_GID=0" > .env

docker-compse up
localhost:8080
user:airflow
passw:airflow
