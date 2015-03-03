# Docker Neovim

[![Docker Hub](https://img.shields.io/badge/docker-erroneousboat%2Fneovim-blue.svg)](https://registry.hub.docker.com/u/erroneousboat/neovim/)

This image will run [Neovim](http://neovim.org/) inside a 
[Docker](https://www.docker.com/) container, and is influenced by the
[blog post](https://blog.jessfraz.com/posts/docker-containers-on-the-desktop.html)
of Jessie Frazelle.

```bash
$ docker run -it \
    --name neovim \
    erroneousboat/neovim
```