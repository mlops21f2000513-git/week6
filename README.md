# Setup files
- Copy model.joblib from gcp bucket to vm
- Add requirements and iris_fastapi.py file to the project


model.joblib    - trained model from previous weeks
iris_fastapi.py - FastAPI code to serve model via API
Dockerfile      - dockerfile to build container image
deployment.yml  - app config for the cluster
service.yaml    - external config for the app
deploy.yml      - github CI action
