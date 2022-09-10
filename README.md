# Python Installation
Installing Python Tools without using Homebrew

1. Uninstalling Homebrew: `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/uninstall.sh)"`
2. Installing neccessary packages: 
 *  `sudo apt-get update`
 *  `sudo apt-get install make build-essential libssl-dev zlib1g-dev libbz2-dev libreadline-dev libsqlite3-dev wget curl llvm libncursesw5-dev xz-utils tk-dev libxml2-dev libxmlsec1-dev libffi-dev liblzma-dev`
*  `sudo apt-get install zlib1g-dev`
3. Installing pyenv:
 * `git clone https://github.com/pyenv/pyenv.git ~/.pyenv`
 * `echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.bash_profile`
 * `echo 'export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.bash_profile`
 * `echo -e 'if command -v pyenv 1>/dev/null 2>&1; then\n eval "$(pyenv init -)"\nfi' >> ~/.bash_profile`
 
 4. Installing Python 3.9.5
  * `pyenv install 3.9.5`
  * `pyenv global 3.9.5`
  * `python --version`
 
 5. Installing Poetry:
  * `curl -sSL https://install.python-poetry.org | python3 -`
  * `poetry --version`
Note:
To get the latest Poetry Version: [Poetry Installation Doc](https://python-poetry.org/docs/#installing-with-the-official-installer)
