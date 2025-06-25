# Run Jenkinsfile on Buildkite

[![Build status](https://badge.buildkite.com/6546028c7208cf924e0775a11daf02122fa5206f7e69910ffd.svg?branch=main)](https://buildkite.com/buildkite/jenkinsfile-example/builds/latest?branch=main)
[![Add to Buildkite](https://buildkite.com/button.svg)](https://buildkite.com/new)

This uses [the Jenkinsfile Runner][jenkinsfile-runner] to run an example
Jenkinsfile in this repo on [a Buildkite Agent][buildkite-agent].

This example is quite basic, but illustrates the idea. This repository is
checked out by the Buildkite Agent. It then runs the Jenkinsfile Runner via
[its Docker image][jenkinsfile-runner-image], using the [Docker Buildkite
Plugin][docker-buildkite-plugin], with the checkout mounted inside. Anything
can be added into the container image and run any pipeline.

  [jenkinsfile-runner]: https://github.com/jenkinsci/jenkinsfile-runner
  [buildkite-agent]: https://buildkite.com/docs/agent
  [jenkinsfile-runner-image]: https://hub.docker.com/r/jenkins/jenkinsfile-runner
  [docker-buildkite-plugin]: https://github.com/buildkite-plugins/docker-buildkite-plugin

[Add to Buildkite](https://buildkite.com/new) to try it yourself!

<a href="https://buildkite.com/buildkite/jenkinsfile-example/builds/latest?branch=main"><img width="1504" alt="Screenshot of Jenksfile example pipeline" src=".buildkite/screenshot.png" /></a>

