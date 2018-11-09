# Java-Maven-Template
Simple Java Template with some maven and docker functionality.

### Available Functionality
* Packaging with the maven-shade-plugin. `mvn clean package` generates
the executable jar file.
* Generation of docker image with the docker-maven-plugin.
`mvn clean install -P docker` generates the image.
* `docker-compose.yml` which runs the previously generated image.