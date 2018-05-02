# development setup

## Installing custom terminal

Get the fileme me.terminal at Terminal folder and import in your terminal application on Mac OS in

* terminal > Preferences > Cog icon > Import

Install zsh and zsh-completions using Homebrew and curl settings:

```
brew install zsh zsh-completions

curl -L https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh | sh

chsh -s /usr/local/bin/zsh

vi ~/.zshrc 
```

Change default line

```
ZSH_THEME="robbyrussell" >> ZSH_THEME="ys"
```

## Installing custom PHP Storm theme

* Open PHP Storm preferences
* Select Scheme
* Import Scheme...
* Select phpstorm/Template.icls


Enjoy
