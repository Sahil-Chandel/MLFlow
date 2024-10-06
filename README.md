## ML FLow experiments


import dagshub
dagshub.init(repo_owner='Sahil-Chandel', repo_name='MLFlow', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)