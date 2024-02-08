ARG REGISTRY=quay.io
ARG OWNER=jupyter
ARG BASE_CONTAINER=$REGISTRY/$OWNER/r-notebook:2023-11-19
FROM $BASE_CONTAINER

RUN conda install -y \
    shiny \
    r-base \