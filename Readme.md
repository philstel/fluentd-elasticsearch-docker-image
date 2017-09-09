# Instructions

`docker run -d -p 24224:24224 -p 24224:24224/udp -v /data:/fluentd/log phillu/fluentd-elasticsearch`

Follow instructions on [https://hub.docker.com/r/fluent/fluentd/](https://hub.docker.com/r/fluent/fluentd/) to run this image

I just took the elasticsearch plugin install instructions from the page above and made a docker image out of it.

Public docker image ist here: [https://hub.docker.com/r/phillu/fluentd-elasticsearch/](https://hub.docker.com/r/phillu/fluentd-elasticsearch/)