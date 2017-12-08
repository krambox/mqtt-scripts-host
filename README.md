## Docker

    docker build -t mqttscripts .

    sudo docker run --env-file /volume1/data/smarthome/scripthost.env   -v /Volumes/data/smarthome/scripts:/data -it mqtt-scripts-host 