Tools JS
======

A Docker image with a NodeJS and a set of Javascript tools, task runners and package managers for web development purposes.

## What's in the image?
- NodeJS 9.2.X
- NPM 5.5.X
- yarn

### Node packages (latest compatible version):
- bower
- grunt-cli
- gulp
- plop

### Yeoman generators:
- webapp
- generator
- fountain-webapp

## Usage
To open a shell with all the tools, mounting the current folder:

```docker run --rm -it -v "$(pwd):/home/node" saoula/tools_js sh```

## Alias
### Bash
- Append ```alias js='docker run --rm -it -v "$(pwd):/home/node" saoula/tools_js'``` to _~/.bashrc_
- Enter `source ~/.bashrc` or open a new terminal window
### Zsh
- Append ```alias js='docker run --rm -it -v "$(pwd):/home/node" saoula/tools_js'``` to _~/.zshrc_
- Enter `source ~/.zshrc` or open a new terminal window