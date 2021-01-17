# Docker compose
The list of docker-compose to develop

## Docker Image list
1. [terragrunt](https://hub.docker.com/r/alpine/terragrunt) - The docker image terragrunt which wrapper for terraform, include terraform.
    - example: `docker run -it --rm --env AWS_DEFAULT_REGION=MY_REGION -v $HOME/.aws:/root/.aws -v ${HOME}/.ssh:/root/.ssh -v `pwd`:/apps alpine/terragrunt:0.14.3 bash`
