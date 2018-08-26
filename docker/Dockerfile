FROM jupyter/datascience-notebook

RUN apt-get update
RUN apt-get install python3-pip


MAINTAINER Matheus Mota 
RUN pip install npm
RUN pip install jupyterlab
RUN jupyter serverextension enable --py jupyterlab
