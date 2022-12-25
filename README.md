# C/C++ Devcontainer Template

This repo provides a simple starter template for working in a devcontainer
provided by VSCode's extension.

The container provides the following:

- Alpine Linux (Note: `musl` and not `libc`).
- VSCode extension: `ms-vscode.cpptools`.
- zsh and oh-my-zsh as the default shell.
- curl, git, nvim.
- C/C++ base build tools.
- Debugging enabled.

A script is also provided to build/launch the container without VSCode using
Podman or Docker. By default it will use podman, but you can change this via
command line argument.

```sh
./start
    -e|--engine        docker|podman (defaults to podman)
    -b|--build         build the image before starting the container
```

## License

This template repository is released under the Unlicense (public domain). See
LICENSE for details, and use at your own risk.