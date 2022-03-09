#strabomap_db

This is a docker-compose yaml file which constructs a container with :

- PostGreSQL with PostGIS extension (kartoza/postgis image - visit the docker hub at: https://hub.docker.com/r/kartoza/postgis/ )

- PGAdmin running at port 5050, for which I followed this tutprial https://towardsdatascience.com/how-to-run-postgresql-and-pgadmin-using-docker-3a6a8ae918b5 

This docker can simply be connected to QGIS to manage the contents of the repository. As used now, it can connect to the strabomap_backend - https://github.com/RinseWillet/strabomap_backend

