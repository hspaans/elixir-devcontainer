# Devcontainer for Elixir

## Using within you project

Add `.devcontainer/devcontainer.json` to your repository.

```json
{
  "image": "ghcr.io/hspaans/elixer-devcontainer:latest",
  "name": "Elixer",
  "settings": {
    "terminal.integrated.shell.linux": "/bin/bash"
  },
  "appPort": [],
  "postCreateCommand": "",
  "remoteUser": "vscode",
  "extensions": [
    "editorconfig.editorconfig",
    "github.vscode-pull-request-github",
    "mjmcloug.vscode-elixir",
    "redhat.vscode-yaml"
  ]
}
```
