## End to End Machine Learning Project



## Run from terminal:
## Build docker image
docker build -t myregistry.azurecr.io/mlproject:latest .

docker login myregistry.azurecr.io
## provide username and password to login into azure container registry

docker push myregistry.azurecr.io/mlproject:latest
## Docker image gets loaded into ACR
