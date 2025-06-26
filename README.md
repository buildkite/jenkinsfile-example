# Run Jenkinsfile on Buildkite

[![Build status](https://badge.buildkite.com/6546028c7208cf924e0775a11daf02122fa5206f7e69910ffd.svg?branch=main)](https://buildkite.com/buildkite/jenkinsfile-example/builds/latest?branch=main)
[![Add to Buildkite](https://img.shields.io/badge/Add%20to%20Buildkite-14CC80)](https://buildkite.com/new)

Use [Jenkinsfile Runner][jenkinsfile-runner] to run a Jenkinsfile on a [Buildkite Agent][buildkite-agent].

This repository is checked out by the Buildkite Agent. It then runs the Jenkinsfile using Jenkinsfile Runner via [a Docker image][jenkinsfile-runner-image], using the [Docker Buildkite Plugin][docker-buildkite-plugin], with the checkout mounted inside.

This example is basic, but illustrates the idea - anything the Jenkinsfile might need could be added to an image atop the Jenkinsfile Runner. [Jenkinsfile Runner Image Packs][jenkinsfile-runner-image-packs] provide some existing examples.

  [jenkinsfile-runner]: https://github.com/jenkinsci/jenkinsfile-runner
  [buildkite-agent]: https://buildkite.com/docs/agent
  [jenkinsfile-runner-image]: https://hub.docker.com/r/jenkins/jenkinsfile-runner
  [docker-buildkite-plugin]: https://github.com/buildkite-plugins/docker-buildkite-plugin
  [jenkinsfile-runner-image-packs]: https://github.com/jenkinsci/jenkinsfile-runner-image-packs

Try it yourself:

[![Add to Buildkite](https://buildkite.com/button.svg)](https://buildkite.com/new)

<a href="https://buildkite.com/buildkite/jenkinsfile-example/builds/latest?branch=main"><img width="1504" alt="Screenshot of Jenksfile example pipeline" src=".buildkite/screenshot.png" /></a>

