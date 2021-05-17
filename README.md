# bumblebee-themes 

## installation

```console
$ git clone <this repository> ~/.config/bumblebee-status/themes

# if you manage dotfiles
$ git submodule add <this repository> <path to dotfiles>
```

## usage

write in `i3/config`
```
bar {
    ...
    status_command bumblebee-status ... -t night-owl
}
```
