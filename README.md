# ohmyposh

## .zshrc on a mac

```sh
if [ "$TERM_PROGRAM" != "Apple_Terminal" ];then
  eval "$(oh-my-posh init zsh --config ~/.config/ohmyposh/zen.toml)"
fi
```

