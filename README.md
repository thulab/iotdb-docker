# iotdb-docker
Dockerfiles of Apache IoTDB. The Repo will be maintained until Apache can release the docker image officially

# How to run

`docker run -d -p 6667:6667 -p 31999:31999 --name some-iotdb hxdiotdb/iotdb:{version}`

Supported versions:

 * 0.8.1
 * 0.9.0

From 0.9.0, there is another port that can be exposed: 8181

# How to use IoTDB-cli

`docker exec -it some-iotdb /bin/bash`

Then, run start-client.sh
