# OpenStreetMap Tile and Nominatim Docker with persistent data

Download a .pbf file from www.geofabrik.de or some other sources and rename it in data.osm.pbf

- To start the Docker-Service docker-compose up -d
- To check what the Docker is doing docker-compose logs -f (The first start needs a long time because he need to create the database)
- To delete docker-compose down
- To stop or start -> docker-compose stop or start

Runs on normal Hardware but need a lot of RAM and for example Austria needs around 30GiB of Drivespace
