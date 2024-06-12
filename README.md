# My Oh-My-Posh Theme

Welcome to my custom `oh-my-posh` themes repository! This repository contains my personalized themes for `oh-my-posh`, a prompt theme engine for any shell. These themes are designed to enhance your terminal experience by providing a visually appealing and informative prompt.

## Table of Contents

<!-- vim-markdown-toc GFM -->

* [Tokyo Night Color Palette](#tokyo-night-color-palette)
* [Preview](#preview)
    * [Theme: tokyo-night-merkks](#theme-tokyo-night-merkks)
    * [Theme: v2-tokyo-night-merkks](#theme-v2-tokyo-night-merkks)
* [Installation](#installation)
    * [Prerequisites](#prerequisites)
    * [Clone the Repository](#clone-the-repository)
    * [Apply the Theme](#apply-the-theme)
    * [Customization](#customization)
    * [Acknowledgements](#acknowledgements)

<!-- vim-markdown-toc -->

## Tokyo Night Color Palette

These themes use the Tokyo Night color palette, which provides a dark, soothing, and visually appealing color scheme. This palette is perfect for prolonged use, reducing eye strain and improving readability.

[Color Palette](https://lospec.com/palette-list/tokyo-night)

## Preview

### Theme: tokyo-night-merkks

Looks nice with [tmux-tokyo-night](https://github.com/fabioluciano/tmux-tokyo-night)

![Theme Preview1](./Preview/tokyo-night-merkks.png)

### Theme: v2-tokyo-night-merkks

![Theme Preview2](./Preview/v2-tokyo-night-merkks.png)

## Installation

### Prerequisites

- Ensure you have `oh-my-posh` installed. You can find installation instructions in the [official oh-my-posh documentation](https://ohmyposh.dev/docs/).

### Clone the Repository

```bash
git clone https://github.com/merkksgit/omp-tokyo-night-merkks.git
```

### Apply the Theme

1. Copy the theme file to your oh-my-posh themes directory. For example:

```bash
cp your-repo-name/my-custom-theme.json $POSH_THEMES_PATH
```

2. Edit your shell configuration file to use the new theme. For example, add the following line to your .bashrc, .zshrc, or equivalent configuration file:

```bash
eval "$(oh-my-posh init bash --config $POSH_THEMES_PATH/tokyo-night-merkks.omp.json)"
```

3. Reload your shell configuration:

```bash
source ~/.bashrc  # or source ~/.zshrc
```

### Customization

Feel free to customize the theme to your liking. The theme file (tokyo-night-merkks.omp.json) contains various settings for prompt elements such as colors, segments, and symbols. Refer to the oh-my-posh [documentation](https://ohmyposh.dev/docs/) for more information on how to customize your theme.

### Acknowledgements

- [oh-my-posh](https://github.com/JanDeDobbeleer/oh-my-posh) - The prompt theme engine that powers this theme.

- [Tokyo Night](https://github.com/enkia/tokyo-night-vscode-theme) - The color palette inspiration for this theme.








