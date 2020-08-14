# Zsh (Oh My Zsh)

## zsh shell

- Install Zsh:  
`sudo apt install zsh`  
`which zsh` # out put should be something like /usr/bin/zsh

- Make zsh default shell:  
`chsh -s /usr/bin/zsh \$USER`

- Close shell:  
`exit`

- Open shell again, and run:  
`echo $SHELL` # output should be something like /usr/bin/zsh

## Oh My Zsh

- Install prerequired tools:  
`sudo apt install wget git`

- Download the installer script and execute it:  
`wget https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh -O - | zsh`

- Copy the template .zshrc.zsh-template configuration file to the home directory .zshrc and apply the configuration:  
`cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc`
`source ~/.zshrc`

- Close shell:  
`exit`

- Open shell again:  
`echo $SHELL` # output should be something like /usr/bin/zsh

## Oh My Zsh Themes

- View all themes:  
`https://github.com/ohmyzsh/ohmyzsh/wiki/Themes`

- View all themes available in the system, typically the same themes above:  
`ls -la ~/.oh-my-zsh/themes/`

- Change the theme:  
`vi ~/.zshrc`

- Change (ZSH_THEME='risto') to (ZSH_THEME='#theme name here'), tyoically line 11:  
`source ~/.zshrc`

## Oh My Zsh Plugins

- Available plugins:  
`https://github.com/ohmyzsh/ohmyzsh/wiki/Plugins`

- Add a plugin:  
`vi ~/.zshrc`

- Add the plugin name to the following list plugins=(git) typically line 71:  
`source ~/.zshrc`

## Thanx
