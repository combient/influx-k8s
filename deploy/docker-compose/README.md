# Quick start with docker-compose

Make sure you have installed [Docker Compose](https://docs.docker.com/compose/).  Once compose is installed go ahead and fire the awesome:

    $ docker-compose up

InfluxDB web UI is on http://localhost:8086 and Grafana is available on http://localhost:3000. *Note*: if you are using [docker-machine](https://docs.docker.com/machine/) you need to replace localhost by the one provided by docker-machine, example:
    
    $ eval "$(docker-machine env default)"
    $ echo $DOCKER_HOST                                                                 
    tcp://192.168.99.100:2376

in this case you will need to visit http://192.168.99.100:8086 (InfluxDB) and http://192.168.99.100:3000 (Grafana)

