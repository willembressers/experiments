FROM python:3.10.5-slim

# define work directory
WORKDIR /mlflow

# build actions
RUN pip install \
    mlflow[extras] \
    mlflow[all] \
    sqlalchemy \
    boto3 \
    google-cloud-storage \
    psycopg2-binary