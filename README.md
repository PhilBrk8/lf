<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://github.com/catppuccin/template">App</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
	<a href="https://github.com/catppuccin/template/stargazers"><img src="https://img.shields.io/github/stars/catppuccin/template?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/template/issues"><img src="https://img.shields.io/github/issues/catppuccin/template?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/template/contributors"><img src="https://img.shields.io/github/contributors/catppuccin/template?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

<p align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/previews/preview.webp"/>
</p>

## Previews

<summary>🌿 Mocha</summary>

Please be aware that I also use the [Alacritty Terminal Mocha Theme](https://github.com/catppuccin/alacritty).  
If you don't then your lf file manager might look different.

<img src="assets/mocha.png"/>
</details>

## Usage

0. I assume I do not have to explain anything about lf-installation or lf-configuration.  
   If you are here, you know what you are doing.

1. Execute the commands for the creation of the directory structure as intende by the [lf OG](https://github.com/gokcehan/lf/wiki/Colors-and-Icons):

   `mkdir -p ~/.config/lf`  
   `curl https://raw.githubusercontent.com/gokcehan/lf/master/etc/colors.example -o ~/.config/lf/colors`  
   `curl https://raw.githubusercontent.com/gokcehan/lf/master/etc/icons.example -o ~/.config/lf/icons`

2. Clone this repo and cd into it.  
   `git clone https://github.com/catppuccin/lf && cd lf`

3. Replace the `colors`-file with the wanted flavor file from this repo by executing either one of the following commands:  
   (Please use mocha everywhere - your eyes will thank you in 15 years if you use dark mode.)  
   `mv -f ./config/colors.latte ~/.config/lf/colors`  
   `mv -f ./config/colors.frappe ~/.config/lf/colors`  
   `mv -f ./config/colors.macciato ~/.config/lf/colors`  
   `mv -f ./config/colors.mocha ~/.config/lf/colors`

4. Backup your own config and adopt my lf-config if you like:  
   `mv ~/.config/lf/lfrc ~/.config/lf/lfrc.bak && mv -f ./config/lfrc ~/.config/lf/lfrc`

<!-- The FAQ section is optional. Remove if needed.-->

## 🙋 FAQ

- Q: **_"How can I do X?"_**\
  A: ...

## 💝 Thanks to

- [Human](https://github.com/catppuccin)

&nbsp;

<p align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" />
</p>

<p align="center">
	Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
</p>

<p align="center">
	<a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a>
</p>
