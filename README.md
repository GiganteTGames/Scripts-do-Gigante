# Script Após formatação do Linux
 Script utilizado por [Gigante TGames](https://gitlab.com/GiganteTGames) para instalações de frameworks e programas essenciais.

## Install Git
---

```
sudo apt install git -y

```



## Install Snapd 
---

```
sudo rm /etc/apt/preferences.d/nosnap.pref
sudo apt update
sudo apt install snapd -y

```

## Install NodeJS
---

```
sudo apt install wget
wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.34.0/install.sh | bash
source ~/.profile
nvm ls-remote
nvm install 15.14.0

```

## Install Flutter
---

```
snap install flutter --classic   

```
## Install Android Studio
---

```
snap install android-studio --classic

```
## Install Visual Studio Code
---

```
snap install code --classic

```
## Install Chromium
---

```
 sudo snap install chromium

```


