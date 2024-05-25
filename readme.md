<div align="center">
<img height="auto" src="/assets/1.png">
</div>
 
## Install instructions

**1. Install all the required apps**

- i3
- alacritty
- i3lock-color
- polybar
- rofi
- flameshot
- dunst
- feh

**2. Move everything from `.config` to `~/.config/`**

**3. Install the rofi theme**

```bash
git clone https://github.com/dracula/rofi
cp rofi/theme/config1.rasi ~/.config/rofi/config.rasi
```

**4. Move the `rofi-power-menu` from the `scripts` directory to `~/.local/bin/` and make it executable**

**5. Then move everything from `.fonts` to `~/.fonts/`**

**6. Install ohmyposh from [here](https://ohmyposh.dev/docs/)**

**7. Adjust the Oh My Posh init line in `~/.bashrc` (could be `~/.profile` or `~/.bash_profile` depending on your environment) by adding the `--config` flag with the location of your configuration.**

```bash
eval "$(oh-my-posh init bash --config ~/.config/prompt.omp.json"
```

**8. Once altered, reload your profile for the changes to take effect.**

```bash
exec bash
```

**9. Reboot your system.**
## Acknowledgements

- Power menu script by [@jluttine](https://github.com/jluttine/rofi-power-menu)
- Dunst configuration by [@ericmurphyxyz](https://github.com/ericmurphyxyz/dotfiles/tree/master/.config/dunst)
- i3lock-color [dracula theme](https://draculatheme.com/i3lock-color)
- Catppuccin [polybar](https://github.com/catppuccin/polybar)
, [i3](https://github.com/catppuccin/i3) and [rofi](https://github.com/catppuccin/rofi/tree/main/basic) theme
- Oh-my-posh [material theme](https://github.com/JanDeDobbeleer/oh-my-posh/blob/main/themes/material.omp.json)
## Screenshots
<div align="center">
<img height="auto" src="/assets/1.png">
<img height="auto" src="/assets/3.png">
<img height="auto" src="/assets/4.png">
<img height="auto" src="/assets/5.png">

</div>
