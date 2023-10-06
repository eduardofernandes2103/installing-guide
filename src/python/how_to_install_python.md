# NVM

To install python we need to install some libs, open terminal end type this script:

    sudo apt install -y make build-essential libssl-dev zlib1g-dev libbz2-dev libreadline-dev libsqlite3-dev wget curl llvm libncurses5-dev libncursesw5-dev xz-utils tk-dev

    sudo apt update && sudo apt upgrade

    git clone https://github.com/asdf-vm/asdf.git ~/.asdf --branch v0.13.1

------------------------------------------------------

# 1-> Bashrc: 

    code ~/.bashrc

# 2-> Add this in ~/.bashrc: 

    . $HOME/.asdf/asdf.sh

    . $HOME/.asdf/completions/asdf.bash

# 3-> update your .bashrc: 

    source ~/.bashrc

------------------------------------------------------

# ASDF

    asdf plugin-add python

    asdf install python 3.9.6

    asdf global python 3.9.6

# If you install a new lib in ASDF try this:

   asdf reshim