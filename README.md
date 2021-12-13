# \[Practice] GitHub Actions
Practice project. Following a GitHub actions tutorial.

Video: https://www.youtube.com/watch?v=R8_veQiYBjI 

Docker Repo: https://hub.docker.com/repository/docker/milanesachan/prac-github-actions

## What does it do?

This repo contains a docker image with a Java + Gradle project. There is a GitHub action in here that triggers with any pull request or commit to the main branch. 

The action is based on the "Java with Gradle" template. A step was added that pushes the gradle build to a public Docker Hub repository. All of this served as practice for better understanding CI/CD workflows.
