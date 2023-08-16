# AstroNvim User Configuration Example

## 🛠️ Installation

#### Get choco and install those damn dependancies! 
Run in admin  (windows)
```shell
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```
 (windows)
```shell
choko install python
choco install neovim
choko install zig
choco install nodejs.install
```
#### Set up python
```shell
python -m pip install virtualenv
pip3 install --user --upgrade pynvim
```


#### Make a backup of your current nvim and shared folder if applicable

```shell
mv ~/.config/nvim ~/.config/nvim.bak
mv ~/.local/share/nvim ~/.local/share/nvim.bak
```

#### Clone AstroNvim
(linux)
```shell
git clone https://github.com/AstroNvim/AstroNvim ~/.config/nvim
```
(Windows)
```shell
git clone --depth 1 https://github.com/AstroNvim/AstroNvim $env:LOCALAPPDATA\nvim
nvim
```

#### Clone the repository
(linux)
```shell
git clone https://github.com/fredriknk/astrovim_config ~/.config/nvim/lua/user
```
(Windows)
```shell
git clone https://github.com/fredriknk/astrovim_config  $env:LOCALAPPDATA\nvim\lua\user
```

#### Start AstroVim

```shell
nvim
```
