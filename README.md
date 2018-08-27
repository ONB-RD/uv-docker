# uv-docker
A simple dockerization of the Universal Viewer

This is a simple Dockerfile that builds a docker container that serves the latest release of the Universal Viewer.

The image is on Dockerhub under the name [onbrd/universalviewer](https://hub.docker.com/r/onbrd/universalviewer/) and can be pulled freely or you can clone this repository and build it yourself.

Run it using the -p parameter to specify the port. The default port for Universal Viewer is 80.

**Running example:** 'docker run --name uv -p 8889:80 -dit onbrd/uv'
This example binds the port to 8889 and names the container 'uv'. Universal Viewer can be accessed at [localhost:8889] with an example book from the Austrian National Library.

To change the displayed manifest, change the data-uri attribute in the div with the id "universalViewerDiv" to your preferred Manifest URL.