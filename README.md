<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://i3wm.org/i3status/">i3status</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
	<a href="https://github.com/juadde/i3status/stargazers"><img src="https://img.shields.io/github/stars/juadde/i3status?labelColor=363a4f&color=b7bdf8&style=for-the-badge"></a>
	<a href="https://github.com/juadde/i3status/issues"><img src="https://img.shields.io/github/issues/juadde/i3status?labelColor=363a4f&color=f5a97f&style=for-the-badge"></a>
	<a href="https://github.com/juadde/i3status/contributors"><img src="https://img.shields.io/github/contributors/juadde/i3status?labelColor=363a4f&color=a6da95&style=for-the-badge"></a>
</p>

<p align="center">
	<img src="assets/preview.webp"/>
</p>

## Previews

<details>
<summary>🌻 Latte</summary>
<img src="assets/latte.webp"/>
</details>
<details>
<summary>🪴 Frappé</summary>
<img src="assets/frappe.webp"/>
</details>
<details>
<summary>🌺 Macchiato</summary>
<img src="assets/macchiato.webp"/>
</details>
<details>
<summary>🌿 Mocha</summary>
<img src="assets/mocha.webp"/>
</details>

## Usage

1. Locate your i3status configuration file, should be from one of the following path as said in the [manpage](https://i3wm.org/i3status/manpage.html):
	- ~/.config/i3status/config (or $XDG_CONFIG_HOME/i3status/config if set)
	- /etc/xdg/i3status/config (or $XDG_CONFIG_DIRS/i3status/config if set)
	- ~/.i3status.conf
	- /etc/i3status.conf

2. Copy the contents of your flavor of choice from [`themes/`](./themes/) to your i3status configuration file. Your `general` bloc should ressemble the following (here for mocha):
```c
general {
        colors = true
        color_good = "#a6e3a1"
        color_degraded = "#fab387"
        color_bad = "#f38ba8"
        interval = 5
}
```

## 💝 Thanks to

- [juadde](https://github.com/juadde)

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
