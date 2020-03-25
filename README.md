[Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh/) plugin for [xxh-shell-zsh](github.com/xxh/xxh-shell-zsh).

## Install
Install from xxh repo:
```
xxh +I xxh-plugin-zsh-ohmyzsh
```
Install from any repo:
```
XXH +I xxh-plugin-zsh-ohmyzsh+git+https://github.com/xxh/xxh-plugin-zsh-ohmyzsh
```
Connect:
``` 
xxh yourhost +s zsh +if
```

## Seamless mode
To use seamless mode with saving your theme and plugins use `source` command: 
```
source xxh.zsh myhost
```

## Environment variables

Xxh support environment variables: `xxh myhost +e NAME=VAL` or `~/.xxh/.xxhc` config.

* `+e ZSH_THEME=clean` - set theme
* `+e plugins="(git ubuntu)"` - set plugins list
