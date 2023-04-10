# Koinos SDK AS Dev Container

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://github.com/codespaces/new?hide_repo_select=true&ref=master&repo=591180027)

[![Open in Dev Containers](https://img.shields.io/static/v1?label=Dev%20Containers&message=Open&color=blue&logo=visualstudiocode)](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/roaminro/koinos-sdk-as-dev-container)

If you already have VS Code and Docker installed, you can click the badge above or [here](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/roaminro/koinos-sdk-as-dev-container) to get started. Clicking these links will cause VS Code to automatically install the Dev Containers extension if needed, clone the source code into a container volume, and spin up a dev container for use.

This dev container contains all the necessary tools to get you started with AssemblyScript Koinos Smart Contracts development:

- `koinos-sdk-as-cli` installed (create a new contract by typing the following command directly in the dev container's terminal:

```sh
koinos-sdk-as-cli create myawesomecontract
```

- `local-koinos` installed to allow you to quickly start a development node. Start a local dev node by typing the following command directly in the dev container's terminal:
```sh
local-koinos start -r http://host.docker.internal:8080 -a amqp://host.docker.internal:5672
```
