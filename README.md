A simple ansible role that installs a given version of docker-compose

This package closely follows the guide at: https://docs.docker.com/compose/install/

# Supported variables

~~~
compose_version
~~~
Which version of docker-compose should you install?
Check out: https://github.com/docker/compose/releases
Defaults to: `/usr/bin`.

~~~
docker_compose_symlink
~~~
Should a symlink be created?
Defaults to: `yes`.

~~~
docker_compose_symlink_path
~~~
If `docker_compose_symlink` is set to true, then create a symlink to this path
Defaults to: `/usr/bin`.