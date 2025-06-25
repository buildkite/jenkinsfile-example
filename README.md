# Run Jenkinsfile on Buildkite

[![Build status](https://badge.buildkite.com/6546028c7208cf924e0775a11daf02122fa5206f7e69910ffd.svg?branch=main)](https://buildkite.com/buildkite/jenkinsfile-example/builds/latest?branch=main)
[![Add to Buildkite](https://buildkite.com/button.svg)](https://buildkite.com/new)

This uses [the Jenkinsfile Runner][jenkinsfile-runner] to run an example
Jenkinsfile in this repo on [a Buildkite Agent][buildkite-agent].

  [jenkinsfile-runner]: https://github.com/jenkinsci/jenkinsfile-runner
  [buildkite-agent]: https://buildkite.com/docs/agent

This example is quite basic, but illustrates the idea. Anything can be added
into the container image and run any pipeline.

