# PySpark Jupyter Lab Notebook - Python v3.10

Jupyter Lab Notebook with root access.
EaseWithApacheSpark notebooks provided to start with.

### To build image from the Dockerfile:

    docker build -t data-engineer/pyspark-jupyter-lab .

### To create container from image

    docker run -it --rm -p 8888:8888 --name pyspark-jupyter-lab data-engineer/pyspark-jupyter-lab
