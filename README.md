# SETUP

This is a setup guide with some config files to setup a new Macbook with my configuration.

## 1 Downloads

App store:

- 1Password
- Slack
- Harvest

Other:

- [Google Chrome](https://www.google.com/chrome/)
- [VScode](https://code.visualstudio.com/download)
- [iTerm2](https://iterm2.com/)
- [Spectacle](https://www.spectacleapp.com/)
- [Spotify](https://www.spotify.com/us/download/other/)
- [Alfred](https://www.alfredapp.com/)
- [Postgres.app](https://postgresapp.com/)
- [Postico](https://eggerapps.at/postico/)

## 2 oh-my-zsh

```bash
# Install oh-my-zsh
# command line dev tools and git are installed along the way
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

Place [node theme](./node.zsh-theme) on `~/.oh-my-zsh/themes`, and then configure it on `.zshrc`:

```bash
ZSH_THEME="node"
```

* iTerm palette: Import [this](./palette.itermcolors) from iTerm settings
* iTerm font: [Fira Code](https://github.com/tonsky/FiraCode)

### 2.1 Keys
Setup SSH keys for Github [Docs](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh)

## 3 CLI Tools

- [brew](https://brew.sh/)
- [nvm](https://github.com/nvm-sh/nvm)
- [rbenv](https://github.com/rbenv/rbenv)

## 4 VSCode config

Font: [Victor Mono](https://rubjo.github.io/victor-mono/)

Extensions:

- Vim
- Auto Close Tag
- Code Spell Checker
- GitLens
- Community Material Theme
- Material Theme Icons
- Guides
- Rainbow Brackets
- Move TS
- Ruby
- endwise
- SCSS Intellisense
- Sort lines
- Vetur

Config file: [settings.json](./vscode-settings.json)

---

Last update: March 31st 2021
