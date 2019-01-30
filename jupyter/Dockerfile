FROM jupyter/datascience-notebook

USER root

RUN apt-get update && \
    apt-get install graphviz -y

RUN pip install tqdm
RUN pip install graphviz

USER jovyan