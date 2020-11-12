# Repository for Splunk examples

## Spin up a docker container to experiment with splunk stuff

<https://hub.docker.com/r/splunk/splunk>

`docker run -d -p 8000:8000 -e "SPLUNK_START_ARGS=--accept-license" -e "SPLUNK_PASSWORD=password" --name splunk splunk/splunk:latest`

View search example [here](./Search)