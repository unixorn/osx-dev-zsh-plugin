# OSX-Dev Oh-My-ZSH Plugin

This plugin adds some commands for maintaining various server programs
on my OSX install. It was cobbled together from my previous
[mamp-control](https://github.com/marshallmick007/mamp-control) project, and various other sources, and "Works On My Machine™"

## Instalation

Fork this repo and add a git submodule to your Oh-My-ZSH
`custom/plugins` directory

... Or, use this repo as is

```shell
cd ~/.oh-my-zsh/custom/plugins
git submodule add git@github.com:marshallmick007/osx-dev-zsh-plugin.git osx-dev
```

Then, add `osx-dev` to your loaded plugins in your `.zshrc` file

## Commands

```shell
devstatus
```

Prints the current status of all of the servers below

### NGINX

```shell
start-nginx
stop-nginx
restart-nginx
status-nginx
```

### Apache

```shell
start-apache
stop-apache
restart-apache
status-apache
```

### MySQL

```shell
start-mysql
stop-mysql
restart-mysql
status-mysql
```

### MongoDB

```shell
start-mongodb
stop-mongodb
restart-mongodb
status-mongodb
```

## Constibuting

Any additions or bug-fixes are welcome, just create an issue and a Pull
request

## TODO

