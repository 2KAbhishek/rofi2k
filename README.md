<div align = "center">

<h1><a href="https://github.com/2kabhishek/rofi2k">rofi2k</a></h1>

<a href="https://github.com/2KAbhishek/rofi2k/blob/main/LICENSE">
<img alt="License" src="https://img.shields.io/github/license/2kabhishek/rofi2k?style=flat&color=eee&label="> </a>

<a href="https://github.com/2KAbhishek/rofi2k/graphs/contributors">
<img alt="People" src="https://img.shields.io/github/contributors/2kabhishek/rofi2k?style=flat&color=ffaaf2&label=People"> </a>

<a href="https://github.com/2KAbhishek/rofi2k/stargazers">
<img alt="Stars" src="https://img.shields.io/github/stars/2kabhishek/rofi2k?style=flat&color=98c379&label=Stars"></a>

<a href="https://github.com/2KAbhishek/rofi2k/network/members">
<img alt="Forks" src="https://img.shields.io/github/forks/2kabhishek/rofi2k?style=flat&color=66a8e0&label=Forks"> </a>

<a href="https://github.com/2KAbhishek/rofi2k/watchers">
<img alt="Watches" src="https://img.shields.io/github/watchers/2kabhishek/rofi2k?style=flat&color=f5d08b&label=Watches"> </a>

<a href="https://github.com/2KAbhishek/rofi2k/pulse">
<img alt="Last Updated" src="https://img.shields.io/github/last-commit/2kabhishek/rofi2k?style=flat&color=e06c75&label="> </a>

<h3>Your Universal Launchpad 🛸🚀</h3>

<figure>
  <img src= "images/screenshot.jpg" alt="rofi2k Demo">
  <br/>
  <figcaption>rofi2k screenshot</figcaption>
</figure>

</div>

rofi2k is an universal application launcher based on rofi, has modern and minimalistic aesthetics.

## ✨ Features

- Launch any application on your system
- Window switcher with workspace support
- Explore and edit all files on your system
- Search and insert emojis

## Setup

### ⚡ Requirements

- [rofi](https://github.com/davatorium/rofi)
- [rofi-emoji](https://github.com/Mange/rofi-emoji) for using emoji search
- [rofi-calc](https://github.com/svenstaro/rofi-calc) for using calculator

### 🚀 Installation

```bash
git clone https://github.com/2kabhishek/rofi2k
# Install
ln -sfnv $PWD/rofi2k ~/.config/rofi
# Run
rofi -show
```

If you already have a rofi config, append the lines in `config.rasi` and copy over `themes`.

### 💻 Usage

To run rofi do `rofi -show mode`

#### 🤖 Modes

- drun: Launch apps
- window: Window switcher
- filebrowser: File explorer
- run: Launch commands
- emoji: Emoji search
- calc: Calculator
- ssh: Manage SSH sessions
- combi: Combo modes
- keys: Keyboard shortcuts

By default drun, window, filebrowser and run modes are enabled, to add more simply edit the [config.rasi](./config.rasi) file

#### ⌨️ Keybindings

You can invoke `rofi` directly from the command line, but it is recommended to have a keybinding configured.

Here's my recommended key bindings

| Keybinding | Description | Command |
| ---------- | ----------- | --------|
| <kbd>Super</kbd> + <kbd>Space</kbd> | Application Launcher | `rofi -show drun` |
| <kbd>Super</kbd> + <kbd>Tab</kbd> | Window Switcher | `rofi -show window` |
| <kbd>Super</kbd> + <kbd>.</kbd> | Emoji Search | `rofi -show emoji` |

## What's Next

Planning to add more useful panels.

##  Behind The Code

### 🌈 Inspiration

rofi2k was inspired by posts on r/unixporn and a need for a functional application launcher.

### 💡 Challenges/Learnings

- Battling my OCD of trying to get everything just right. 😆
- Learned about the rofi ecosystem

### 🧰 Tooling

- [dots2k](https://github.com/2kabhishek/dots2k) — Dev Environment
- [nvim2k](https://github.com/2kabhishek/nvim2k) — Personalized Editor
- [awesome2k](https://github.com/2kabhishek/awesome2k) — Tiling Window Manager

<hr>

<div align="center">

<strong>⭐ hit the star button if you found this useful ⭐</strong><br>

<a href="https://github.com/2KAbhishek/BareMinimum">Source</a>
| <a href="https://2kabhishek.github.io/blog" target="_blank">Blog </a>
| <a href="https://twitter.com/2kabhishek" target="_blank">Twitter </a>
| <a href="https://linkedin.com/in/2kabhishek" target="_blank">LinkedIn </a>
| <a href="https://2kabhishek.github.io/links" target="_blank">More Links </a>
| <a href="https://2kabhishek.github.io/projects" target="_blank">Other Projects </a>

</div>

