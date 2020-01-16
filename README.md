# Hadoop Docker Image

teamsprint/hadoop:2.7.3

# Based on (in a row)

teamsprint/centos:7<br/>
teamsprint/jdk:8<br/>

# Build the image

run build.sh

# Start a container

run run.sh

The container name is "hadoop". If you don't want, just edit the scripts.

# Attach a container

run attach.sh

# Destroy containers

run destroy.sh

# IMPORTANT: After attach you might to want to to:
./start-hadoop.sh (HDFS & Yarn)<br/>
./test-hadoop.sh (Optional)<br/>

