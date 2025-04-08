# staship_prompt
My favorite config for starship prompt

![image](https://github.com/user-attachments/assets/49f51d60-28e7-48f2-9b65-277b6ec296fc)

https://starship.rs/ 

### Install
```shell
curl -sS https://starship.rs/install.sh | sh
```

Add on `.bashrc`:
```shell
eval "$(starship init bash)"
```

### Font
Nerd font is required for a good icons compatibility:

Choose one from [NerdFonts](https://www.nerdfonts.com/font-downloads) then:

```shell
# get font
cd ~/.local/share/fonts
curl https://github.com/ryanoasis/nerd-fonts/releases/download/v3.3.0/FiraCode.zip

# Update font cache
fc-cache -fv
```

### Preset
I choose [Gruvbox Rainbow Preset](https://starship.rs/presets/gruvbox-rainbow).

```
starship preset gruvbox-rainbow -o ~/.config/starship.toml
```

### Config
Config was changed compare to the one in preset page, because it didn't deal with virtualenvs.

use [starship.toml](./starship.toml) instead and put it in `~/.config/starship.toml`
