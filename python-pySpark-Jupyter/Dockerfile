FROM jupyter/base-notebook:latest

# Install Java (required by Spark)
USER root
RUN apt-get update && apt-get install -y openjdk-11-jdk && rm -rf /var/lib/apt/lists/*

# Set Java environment variables
ENV JAVA_HOME=/usr/lib/jvm/java-11-openjdk-amd64
ENV PATH=$JAVA_HOME/bin:$PATH

# Install PySpark
USER $NB_UID
RUN pip install pyspark findspark
