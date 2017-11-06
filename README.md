## Docker

    docker build -t mqtt-scripts-host .

    docker run --env km200config=/data/config.yml  -v /Volumes/data/smarthome:/data -it mqtt-scripts-host 