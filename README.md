# udagram-kubernetes

This repo contains the final project of the kubernetes course for the cloud developer nanodegree. Please note that this repo does not contain the code, but references (submodules) to the repos that actually have the code. Each of the submodules in this repo is a stand alone repo representing a microservice in the kubernetes cluster.

Run the following command to recursivelly clone the repos:

`git clone git@github.com:samuelchvez/udagram-kubernetes.git --recurse-submodules`

I decided to completely remove the shell scripts that populated the environment variables and replaced it with a couple of .env files, inside the api microservices to ease the integration with Travis CI. This .env is generated during CI using Travis Environment Variables (check the .travis.yaml file in both repos).
