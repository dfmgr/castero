## castero  
  
TUI podcast client for the terminal  
  
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/dfmgr/castero/raw/main/install.sh)"
```

Manual install:
  
requires:

Debian based:

```shell
apt install mpv libmpv-dev python3-pip python3-setuptools
```  

Fedora Based:

```shell
yum install mpv mpv-libs-devel python3-pip python3-setuptools
```  

Arch Based:

```shell
pacman -S mpv python-pip python-setuptools python-cjkwrap
```  

MacOS:  

```shell
brew install mpv mpv-libs-devel python3-pip python3-setuptools
```
  
PIP:  

```shell
sudo -H pip3 install --upgrade castero
```

```shell
mv -fv "$HOME/.config/castero" "$HOME/.config/castero.bak"
git clone https://github.com/dfmgr/castero "$HOME/.config/castero"
```
  
<p align=center>
  <a href="https://github.com/xgi/castero" target="_blank" rel="noopener noreferrer">castero site</a>
</p>  
