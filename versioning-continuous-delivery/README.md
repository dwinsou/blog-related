- `mvn package` to build the jar, wrap it in a docker image and install the image to the local registry.
- `docker-compose up` to start the built image locally.
- `mvn deploy` to push the image to the docker registry.