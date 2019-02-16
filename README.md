# Chapter 7 - Recurrent Neural Networks
This case study explores recurrent neural networks on Neural Machine Translation. Upon starting the docker container, a jupyter server will start up. The Chapter 7 notebook will walk through the experiments performed. 

## Requirements
Without GPU (CPU only):
* [Docker](https://docs.docker.com/install/) 

If using a GPU: 
* [Nvidia docker2](https://github.com/nvidia/nvidia-docker/wiki/Installation-(version-2.0)#installing-version-20)

## Running the Docker Image
The docker images for this case study are located on dockerhub. Running the commands below will automatically download and start a jupyter notebook.

Run the Docker image for CPU only computation:
```
docker run -p 8888:8888 jimmywhitaker/chapter_7:latest
```

Run the Docker image with GPU access: 
```
docker run --runtime=nvidia -p 8888:8888 jimmywhitaker/chapter_7:latest
```

## Building the Docker image
```
docker build -t springer_nlp/chapter_7:latest .
```
