## Docker

    docker build -t mqtt-scripts-host .

    sudo docker run --env-file /volume1/data/smarthome/scripthost.env   -v /Volumes/data/smarthome/scripts:/data --name scripts2mqtt -d -t krambix/mqtt-scripts-host 