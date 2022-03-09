#strabomap_db

This is a docker-compose yaml file which constructs a container with :

- PostGreSQL with PostGIS extension (kartoza/postgis image - visit the docker hub at: https://hub.docker.com/r/kartoza/postgis/ )

- PGAdmin running at port 5050, for which I followed this tutprial https://towardsdatascience.com/how-to-run-postgresql-and-pgadmin-using-docker-3a6a8ae918b5 

This docker can simply be connected to QGIS to manage the contents of the repository. As used now, it can connect to the strabomap_backend - https://github.com/RinseWillet/strabomap_backend

Simplified instructions:

- make sure docker and docker-compose are installed
- copy the yml file to your directory of choice
- make your own password, username, etc. by loading the yml file in a text editor (I used Visual Studio Code)
- navigate to this directory in the terminal/commandprompt
- run: docker-compose up
- the container is now running, now it is time to set up PG Admin -> in a browser go to localhost:5050 (if you haven't changed the port in the yml file)
- follow the tutorial for connecting to your postgresql/postgis container here: https://towardsdatascience.com/how-to-run-postgresql-and-pgadmin-using-docker-3a6a8ae918b5
 
