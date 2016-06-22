# docker-tiles

Docker Tile Cache server

#### Build: 
    docker build -t twms https://github.com/princeamd/docker-tiles.git

### Usage: 
    docker run --name princeamd-twms -p 8080:8080 -d twms:latest

This container exposes port 8080 which you can access to view tiles.

Example: "http://princeamd-twms:8080/?layers=ocm&request=GetTile&z={$zoom}&x={$xCoord}&y={$yCoord}"
