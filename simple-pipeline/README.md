# Inside my simple-pipeline
This folder contains a Jenkins pipeline (`Jenkinsfile`) that runs a Node.js Docker container and prints the Node.js version.

## Steps:
1. Uses the `node:latest` Docker image.
2. Runs `node --version` to display the version.

## How to Use:
- Link this `Jenkinsfile` in a Jenkins pipeline job.
- Trigger a build to see the Node.js version.