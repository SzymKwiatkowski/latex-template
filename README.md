# Latex template

Latex template to integrate vscode and latex packages into docker composed environment.

## Requirements
To use template install:
- docker
- visual studio code

Template uses `devcontainers` extension to create docker container with latex dependencies. Container by default mounts current workspace to it. Extensions used in a container by default are as follows:
- latex workshop (wrapped latex command to commands and autocompletion for latex)
- code spell checker polish