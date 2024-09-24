1) Install neovim 0.10+ from PreBuilt archive
```bash
curl -LO https://github.com/neovim/neovim/releases/latest/download/nvim-linux64.tar.gz
sudo rm -rf /opt/nvim
sudo tar -C /opt -xzf nvim-linux64.tar.gz
```
2) Install NerdFont in terminal
3) `sudo apt install ripgrep`
4) Add nvim binary to zsh (`~/.zshrc`)
```bash
export PATH="$PATH:/opt/nvim-linux64/bin"
```
5) Install this config
```
git clone https://github.com/Armatofik/nvim_config.git ~/.config/nvim
```
6) Run `nvim` and `:MasonInstallAll` after finish preInstall
