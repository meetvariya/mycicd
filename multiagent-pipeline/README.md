## Jenkins Pipeline to Check Versions of Maven and Node.js
This pipeline runs two stages: one for checking the version of Maven and another for checking the version of Node.js. Each stage uses a Docker container with the respective tool's image.

## Stages:
- Back-end: Runs the maven:3.8.1-adoptopenjdk-11 Docker image and prints the Maven version.
- Front-end: Runs the node:16-alpine Docker image and prints the Node.js version.

## How to Use:
- Link this Jenkinsfile in a Jenkins pipeline job.
- Trigger a build to see the Maven and Node.js versions printed in the console output.