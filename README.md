# Zsh Plugin For Tailscale
tailscale auto-completion plugin for zsh

## How to use?

1. First, clone this lib into `oh-my-zsh` custom plugin directory
```shell
git clone https://github.com/hsrzq/PluginForTailscale.git ~/.oh-my-zsh/custom/plugins/tailscale
```
2. Second, edit `oh-my-zsh` config file `~/.zshrc`, add `tailscale` into plugins, it maybe like below:
```shell
plugins=(
  ...
  tailscale
  ...
)
```
3. And finally, just refresh your zsh
```shell
omz reload
```
