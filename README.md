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
docker run -p 8888:8888 --rm springernlp/chapter_7:latest
```

Run the Docker image with GPU access: 
```
docker run --runtime=nvidia -p 8888:8888 --rm springernlp/chapter_7:latest
```

## Building the Docker image
```
docker build -t chapter_7:latest .
```

## Book Reference
More information can be found at: [Deep Learning for NLP and Speech Recognition](https://www.amazon.com/Deep-Learning-NLP-Speech-Recognition/dp/3030145956) by [Springer](https://www.springer.com/us/book/9783030145958) 
