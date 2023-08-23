## End to End Machine Learning Project



## Run from terminal:
## Build docker image
docker build -t myregistry.azurecr.io/mlproject:latest .

## provide username and password to login into azure container registry
docker login myregistry.azurecr.io

## Docker image gets loaded into ACR
docker push myregistry.azurecr.io/mlproject:latest

