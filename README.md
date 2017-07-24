# tilestache
run tilestache server with docker compose (for testing purposes)

Uses the build in ``tilestache-server.py``. As a default config it uses ``config/tilestache_test.cfg``

to start the server run::

    docker-compose up
    
You should see output like this::

    tiles-server_1  |  * Running on http://0.0.0.0:8080/ (Press CTRL+C to quit)


Go to http://localhost:4455, respose should be::

    TileStache bellows hello.
    

To get a OSM tile http://0.0.0.0:4455/osm/10/163/394.png


