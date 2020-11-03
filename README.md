# Basic PySpark Setup

## Environment
- WSL:Ubuntu-18.04

## Install Spark on Ubuntu
- sudo apt update
- sudo apt install openjdk-8-jdk
- download Spark from Spark website
- tar vxf <spark.tgz file>
- create .env file (see .env file)
- source .env
- start-master.sh 
- start-slave.sh -c 1 spark://<name from Spark Web UI>:7077
- test running pyspark

## Reference
- https://phoenixnap.com/kb/install-spark-on-ubuntu