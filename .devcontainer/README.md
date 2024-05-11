# Dev container
This project includes a [dev container](https://containers.dev/), which lets you use a container as a full-featured dev environment.

You can use the dev container configuration in this folder to build and run the app without needing to install any of its tools locally! You can use it in [GitHub Codespaces](https://github.com/features/codespaces) or the [VS Code Dev Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers).

## Tips and tricks
If you are working with the same repository folder in a container and Windows, you'll want consistent line endings (otherwise you may see hundreds of changes in the SCM view). The .gitattributes file in the root of this repo will disable line ending conversion and should prevent this. See tips and tricks for more info.
If you'd like to review the contents of the image used in this dev container, you can check it out in the devcontainers/images repo.