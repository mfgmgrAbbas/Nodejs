# NVM (Node Version Manager) Documentation

This is a documentation for Node Version Manager - Complete Guide

[VIDEO TUTORIAL](https://youtu.be/246pRYZDAHA)


## Introduction
NVM (Node Version Manager) is a tool that allows you to manage multiple installations of Node.js and npm. 
It provides an easy way to switch between different Node.js versions based on your project requirements.

## Installation
To install NVM, run the following command in your terminal:

```shell
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
```
or using wget:

```shell
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
```
## Troubleshooting
In case of error NVM not found, copy the code below and run it:
```shell
source ~/.nvm/nvm.sh
```
## Usage
After installation, you can start using NVM to manage Node.js versions:
1. nvm install [version]: Install a specific Node.js version.
2. nvm use [version]: Use a specific Node.js version in the current shell.
3. nvm ls: List installed Node.js versions.
4. nvm alias default [version]: Set a default Node.js version to be used.

## Updating
To update NVM to the latest version, run the following command:
```shell
nvm install node --reinstall-packages-from=node
```
## Uninstallation
If you wish to uninstall NVM, run the following command:
```shell
rm -rf ~/.nvm
```
## Resources
- [NVM GitHub Repository](https://github.com/nvm-sh/nvm)
- [NVM Installation Instructions](https://github.com/nvm-sh/nvm#installation-and-update)
- [NVM Usage Guide](https://github.com/nvm-sh/nvm#usage)
