# Jupyter Notebook With Python 3 and Node 10 LTS

This is a docker image for a Jupyter Notebook for both Python 3 and Node 10 LTS.

## Building The Docker Image

`docker build -t jupyter-notebook-python3-node:dev .`

## Making The Docker Container

`docker run --name jupyter-notebook-python3-node -p 8888:8888 -v "$(pwd)/notebooks:/opt/notebooks" -d jupyter-notebook-python3-node`

## Published At Docker Hub

`docker pull chrisgruber/jupyter-notebook-python3-node`
