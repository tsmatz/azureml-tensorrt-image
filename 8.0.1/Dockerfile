FROM mcr.microsoft.com/azureml/openmpi4.1.0-cuda11.1-cudnn8-ubuntu18.04

USER root:root

RUN apt-get update && \
    apt-get install -y --no-install-recommends \
    libnvinfer8=8.0.1-1+cuda11.3 \
    python3-libnvinfer-dev=8.0.1-1+cuda11.3
