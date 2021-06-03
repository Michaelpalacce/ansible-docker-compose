A simple ansible role that installs the latest version of Docker.

This package closely follows the guide at: https://docs.docker.com/engine/install/ubuntu/

# Supported variables

~~~
arch
~~~
Define your current ubuntu architecture.
Possible values: `amd64`, `armhf`, `arm64`.
Defaults to: `amd64`.