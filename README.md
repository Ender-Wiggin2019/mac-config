# Personal Mac Setup

## Prerequisites

- Node.js
- Python

## Tools

### Install Homebrew

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### Install Oh My Zsh

[Oh My Zsh](https://ohmyz.sh/)

> If don't have zsh installed, you can install it with `brew install zsh`

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### Install Taskfile

[Taskfile](https://taskfile.dev/installation/)

```bash
brew install go-task/tap/go-task
```

### Install Whistle

[Whistle](https://wproxy.org/whistle/install.html)

```bash
brew install whistle
```

## Theme and Appearance

### Install Fonts

[0xProto Nerd Font](https://www.nerdfonts.com/font-downloads)
[LxgwWenKai](https://github.com/lxgw/LxgwWenKai/releases)
[LxgwWenkaiTC](https://github.com/lxgw/LxgwWenkaiTC/releases)

### Install Starship

[Starship](https://starship.rs/guide/)

```bash
curl -sS https://starship.rs/install.sh | sh
```

## Programming Languages

### Python Setup

[uv](https://docs.astral.sh/uv/)

```bash
brew install uv
```

or

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

```bash
echo 'eval "$(uv generate-shell-completion zsh)"' >> ~/.zshrc
echo 'eval "$(uv generate-shell-completion zsh)"' >> ~/.zshrc
```
