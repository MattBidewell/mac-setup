# Mac-setup

## 1 Install Homebrew

```sh
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

## 2 install Brewfile

```sh
git clone https://github.com/MattBidewell/mac-setup
cd mac-setup
brew bundle
```

## 3 Add dotfiles

```bash
bash <(curl -fsSL ...)
```

## 4 Setup GPG
Follow https://developer.okta.com/blog/2021/07/07/developers-guide-to-gpg for using existing Yubikey
