# Hi Anologicon or `your-name-here`

Here we are again, if you need help to remember your favorites configs (if is favorite why you need help to remember?!);

First, you need open the json file to see the recomendations. But wee need build a markdown file in the future.

Here are the most values links to help you:


## Links

### Linux Mint - chose Xfce

https://linuxmint.com/download.php

### Ocs-url (helper)

https://www.pling.com/p/1136805/

### Icons

https://www.xfce-look.org/s/XFCE/p/1279924

### Cursor

https://www.xfce-look.org/p/1197198/

### Linux Mint Theme

https://www.xfce-look.org/p/1239855/

### Power Level 9 K

https://github.com/Powerlevel9k/powerlevel9k

### zsh and plugins

https://blog.rocketseat.com.br/terminal-com-oh-my-zsh-spaceship-dracula-e-mais/

### O-my-zsh config

https://dev.to/manan30/what-is-the-best-zshrc-config-you-have-seen-14id

Remember the most important part is:

```
#Customise the Powerlevel9k prompts
POWERLEVEL9K_LEFT_PROMPT_ELEMENTS=(
ssh
dir
vcs
newline
status
)
POWERLEVEL9K_RIGHT_PROMPT_ELEMENTS=()
POWERLEVEL9K_PROMPT_ADD_NEWLINE=true
POWERLEVEL9K_DIR_WRITABLE_FORBIDDEN_BACKGROUND=yellow
POWERLEVEL9K_DIR_WRITABLE_FORBIDDEN_FOREGROUND=black

#History setup
HISTFILE=$HOME/.zsh_history
HISTSIZE=100000
SAVEHIST=$HISTSIZ

# Aliases

alias grep=ack
alias digitalocean="ssh digitalocean"
alias ls="colorls"
alias python="python3"
alias pip="pip3"
alias easy-install="easy_install-3.7"
alias config="vi $HOME/.zshrc"
alias projects="cd $HOME/Spaces/Projects"
alias reload="source $HOME/.zshrc"

# Git aliases
alias gi="git init"
alias gs="git status -sbu"
alias gco="git checkout"
alias gcob="git checkout -b"
alias gp="git push"
alias gm="git merge"
alias ga="git add ."
alias gcm="git commit -m"
alias gpl="git pull"
alias gst="git stash"
alias gstl="git stash list"
alias glg='git log --graph --oneline --decorate --all'

```

### FiraCode
https://github.com/tonsky/FiraCode

### Docker

https://computingforgeeks.com/install-docker-and-docker-compose-on-linux-mint-19/

### Docker-compose

https://docs.docker.com/compose/install/


see you ;)
