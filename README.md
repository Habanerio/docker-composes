# docker-compose

If after following all of the steps, including setting permissions (https://docs.docker.com/engine/install/linux-postinstall/) you get the following error:
   docker: permission denied while trying to connect to the Docker daemon socket at unix:///var/run/docker.sock: Post "http://%2Fvar%2Frun%2Fdocker.sock/v1.24/containers/create": dial unix /var/run/docker.sock: connect: permission denied.
See 'docker run --help'.

Then run: sudo chmod 666 /var/run/docker.sock
