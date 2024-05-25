<div align="center">
<img height="auto" src="/assets/1.png">
</div>
 
## Install instructions

##### 1. Install all the required apps

- i3
- alacritty
- i3lock-color
- polybar
- rofi
- flameshot
- dunst
- feh

##### 2. Move everything from `.config` to `~/.config/`

##### 3. Install the rofi theme

```bash
git clone https://github.com/dracula/rofi
cp rofi/theme/config1.rasi ~/.config/rofi/config.rasi
```

##### 4. Move the `rofi-power-menu` from the `scripts` directory to `~/.local/bin/` and make it executable

##### 5. Then move everything from `.fonts` to `~/.fonts/`

##### 6. Install ohmyposh from [here](https://ohmyposh.dev/docs/)

##### 7. Adjust the Oh My Posh init line in `~/.bashrc` (could be `~/.profile` or `~/.bash_profile` depending on your environment) by adding the `--config` flag with the location of your configuration.

```bash
eval "$(oh-my-posh init bash --config ~/.config/prompt.omp.json"
```

##### 8. Once altered, reload your profile for the changes to take effect.

```bash
exec bash
```

## Acknowledgements
