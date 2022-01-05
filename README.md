# swarm-runner
Exploring setting up CircleCI's self-hosted Runner with Docker Swarm

## Introduction

We make use of Dynamic Configuration (_more specifically, with path-filtering_) to separate the following operations:

- Publishing the custom Launch-Agent image for Runner
- Updating the (existing) Docker Swarm

## Publishing the custom Launch-Agent image

The final published image is available at https://hub.docker.com/r/kelvintaywl/circleci-launch-agent .

You can see the Dockerfile in this project, under _runner/Dockerfile_.
