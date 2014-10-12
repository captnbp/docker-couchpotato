docker couchpotato
================

This is a Dockerfile to set up "Couchpotato" - (https://couchpota.to/)

Build from docker file

```
git clone https://github.com/captainebp/docker-couchpotato.git
cd docker-couchpotato
docker build -rm -t couchpotato .
```

docker run -d -v /*couchpotato_data_location*:/data  -v /*your_videos_location*:/media -p 5050:5050 couchpotato
