FROM mcr.microsoft.com/azureml/minimal-ubuntu18.04-py37-cuda11.0.3-gpu-inference:latest

USER root:root

RUN apt-get update && \
    apt-get install -y --no-install-recommends \
    libnvinfer8 \
    python3-libnvinfer-dev

RUN pip install nvidia-pyindex

RUN pip install nvidia-tensorrt
