# Udacity-Project4-ML-predictor

<h1>Project Overview</h1>

Deploy a containerized Python flask application to serve out predictions (inference) about housing prices through API calls. It uses a a pre-trained, sklearn model that has been trained to predict housing prices in Boston according to several features.

<h1>Project Procedure</h1>

Test project code using linting
Complete a Dockerfile to containerize this application
Deploy containerized application using Docker and make a prediction
Configure Kubernetes and create a Kubernetes cluster
Deploy a container using Kubernetes and make a prediction
Upload a complete Github repo with CircleCI to indicate the code has been tested

<h1>Getting Started</h1>

Setup the Environment
Create a virtualenv and activate it
python3 -m venv <your_venv>
source <your_venv>/bin/activate
Run make install to install the necessary dependencies

<h1>Running app.py Project</h1>

Deploy in Docker: ./run_docker.sh
Making predictions For Docker: ./make_prediction-docker.sh
Upload the Docker Image: ./upload_docker.sh
Deploy in Kubernetes: ./run_kubernetes.sh
Making predictions For Kubernetes: ./make_prediction-k8s.sh

<h1>Kubernetes Steps</h1>

Setup and Configure Docker locally
Setup and Configure Kubernetes locally
Create Flask app in Container
Run via kubectl
