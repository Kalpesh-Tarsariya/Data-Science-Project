import dagshub
dagshub.init(repo_owner='Kalpesh-Tarsariya', repo_name='Data-Science-Project', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)
