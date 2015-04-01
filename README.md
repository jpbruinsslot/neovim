# Docker Neovim

[![Docker Hub](https://img.shields.io/badge/docker-erroneousboat%2Fneovim-blue.svg)](https://registry.hub.docker.com/u/erroneousboat/neovim/)

This image will run [Neovim](http://neovim.org/) inside a 
[Docker](https://www.docker.com/) container, and is influenced by the
[blog post](https://blog.jessfraz.com/posts/docker-containers-on-the-desktop.html)
of Jessie Frazelle.

Fire it up:
```bash
$ docker run -it \
    --name neovim \
    erroneousboat/neovim
```

Use with configuration files and mounting a folder:
```bash
$ docker run -it \
    -v $HOME/.nvim:/root/.nvim \
    -v $HOME/.nvimrc:/root/.nvimrc \
    -v $HOME/myfolder:/data \
    --name neovim \
    erroneousboat/neovim
```

The branch
[development](https://github.com/erroneousboat/neovim/tree/development) makes
use of the truecolor capabilities of Neovim. Check out that branch to see how
you might set that up.
