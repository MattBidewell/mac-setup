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
cd ../
```

## 3 Add dotfiles
```sh
git clone https://github.com/MattBidewell/dot-files
cd dot-files
# copy the files from here that you want to your root
```

## 4 Setup GPG

If starting fresh with Yubikey and GPG then follow this [tutorial](https://developer.okta.com/blog/2021/07/07/developers-guide-to-gpg) from the start.

Else jump to [using gpg keys on multiple computers](https://developer.okta.com/blog/2021/07/07/developers-guide-to-gpg#use-your-gpg-key-on-multiple-computers).

