# devbox

[![](https://imagelayers.io/badge/pemcconnell/devbox:latest.svg)](https://imagelayers.io/?images=pemcconnell/devbox:latest 'Get your own badge on imagelayers.io')

A dev environment as a docker container, because why the hell not.

# run

At a minimum you can just run:

`docker run -ti pemcconnell/devbox`

Which will throw you into bash on a debian container (with some dev tools installed).

If you wish to run this with the docker sock mounted, run:

`docker run -v /var/run/docker.sock:/var/run/docker.sock -ti pemcconnell/devbox`
