# End-to-end-Cell-Segmentation-Using-Yolo-v8

## Workflows

1. constants
2. entity
3. components
4. pipelines
5. app.py




# AZURE-CICD-Deployment-with-Github-Actions

## Save pass:

S6tXzK7IxUHz9O/9jkhciLsseddeQ++E+OcD7nQYy8+ACRDtEgUW


## Run from terminal:

docker build -t cellseg.azurecr.io/cell:latest .

docker login cellseg.azurecr.io

docker push cellseg.azurecr.io/cell:latest


## Deployment Steps:

1. Build the Docker image of the Source Code
2. Push the Docker image to Container Registry
3. Launch the Web App Server in Azure 
4. Pull the Docker image from the container registry to Web App server and run 
