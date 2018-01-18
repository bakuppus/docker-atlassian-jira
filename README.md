# Atlassian JIRA Core in a Docker container

This is a containerized installation of Atlassian JIRA Core with Docker.
The aim of this image is to keep the image small and adjustable. 
It is based on an alpine oraclejdk image.


If you want to help out, please create pull requests and/or issues on github.

## I'm in the fast lane! Get me started

To quickly get started running a JIRA Core instance, use the following command:
```bash
docker run --detach --publish 8080:8080 blacs30/atlassian-jira:latest
```

Then simply navigate your preferred browser to `http://[dockerhost]:8080` and finish the installation.
