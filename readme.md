``` bash
$ pyenv install 3.8.6
$ pyenv virtualenv 3.8 meu_ambiente
$ pyenv activate my_sort
$ pip install poetry==1.0.2
$ poetry new ambiente
$ poetry add
$ pyenv virtualenv-delete <name>
```

# Intalação zsh e pyenv
``` bash

$ sudo apt-get update; sudo apt-get install make build-essential libssl-dev zlib1g-dev \
libbz2-dev libreadline-dev libsqlite3-dev wget curl llvm \
libncursesw5-dev xz-utils tk-dev libxml2-dev libxmlsec1-dev libffi-dev liblzma-dev

$ sudo apt install git-all

$ curl -L https://github.com/pyenv/pyenv-installer/raw/master/bin/pyenv-installer | bash

$ sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
$ sudo apt install zsh
$ chsh -s /usr/bin/zsh
$ sudo chsh -s $(which zsh)
$ echo $SHELL
```
